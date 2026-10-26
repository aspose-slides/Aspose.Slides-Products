---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java का उपयोग करके ODP प्रेज़ेंटेशन फ़ाइलों में टेक्स्ट खोजें
url: /hi/java/search/odp/
description: Aspose.Slides for Java का उपयोग करके Java में ODP प्रेज़ेंटेशन में टेक्स्ट खोजें।
keywords: ODP में शब्द खोजें, ODP में टेक्स्ट खोजें, ODP प्रेज़ेंटेशन का टेक्स्ट खोजें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java का उपयोग करके ODP में टेक्स्ट खोजें" h2="सर्वर-साइड API का उपयोग करके प्रेज़ेंटेशन फ़ाइलों में टेक्स्ट खोजने वाले Java एप्लिकेशन बनाएँ।" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java के माध्यम से ODP प्रेज़ेंटेशन में टेक्स्ट खोजें" variant="code" %}}

[Aspose.Slides for Java](/slides/hi/java/) का उपयोग करके, आप ODP प्रेज़ेंटेशन में टेक्स्ट खोज सकते हैं। टेक्स्ट फ़्रेम इकट्ठा करने के लिए `SlideUtil.getAllTextBoxes` मेथड का उपयोग करें, फिर `ITextFrame`, `IParagraph` और `IPortion` ऑब्जेक्ट की जाँच करें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java का उपयोग करके ODP प्रेज़ेंटेशन में टेक्स्ट खोजें" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java के माध्यम से ODP में टेक्स्ट कैसे खोजें" intro="ODP प्रेज़ेंटेशन में टेक्स्ट खोजने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास के साथ ODP फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}हर स्लाइड से टेक्स्ट फ़्रेम इकट्ठा करने के लिए `SlideUtil.getAllTextBoxes` मेथड कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}मेल खाने वाला टेक्स्ट ढूँढने के लिए `ITextFrame`, `IParagraph` और `IPortion` ऑब्जेक्ट की जाँच करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides से निर्मित" title="ODP फ़ाइलों में ऑनलाइन टेक्स्ट खोजें" description="मुफ़्त Aspose.Slides Search ऐप [Aspose.Slides for Java](https://products.aspose.com/slides/hi/java/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी ODP फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Search खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides टेक्स्ट कैसे ढूँढता है।
- अपनी ODP फ़ाइल में सादा टेक्स्ट या रेगुलर एक्सप्रेशन खोजें।
- मिले परिणामों को टेक्स्ट फ़ाइल के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="खोज के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="Java का उपयोग करके, आप निम्न फ़ॉर्मेट में भी टेक्स्ट खोज सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
