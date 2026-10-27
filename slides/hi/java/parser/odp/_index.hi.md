---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 5200
title: Java से ODP दस्तावेज़ों से टेक्स्ट निकालें
url: /hi/java/parser/odp/ 
description: Aspose.Slides for Java से Java में ODP फ़ाइलों से टेक्स्ट निकालें।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java में ODP फ़ाइलें पार्स करें" h2="Aspose.Slides for Java के सर्वर-साइड API से ODP दस्तावेज़ों से टेक्स्ट और प्रेज़ेंटेशन सामग्री निकालें।"
  apiHomeLink="/slides/java/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java से ODP फ़ाइल पार्स करें" %}}

ODP प्रेज़ेंटेशन पार्स करने और स्लाइड से टेक्स्ट निकालने के लिए [Aspose.Slides for Java](/slides/hi/java/) का उपयोग करें। Maven प्रोजेक्ट में लाइब्रेरी जोड़ने के लिए अपनी `pom.xml` फ़ाइल में नीचे दिया गया रिपॉज़िटरी और डिपेंडेंसी कॉन्फ़िगरेशन जोड़ें।

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="रिपॉज़िटरी" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="डिपेंडेंसी" >}}
```xml
<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP फ़ाइलें पार्स करें – Java" >}}
```java
Presentation presentation = new Presentation("demo.odp");
try {
    ISlide slide = presentation.getSlides().get_Item(0);
    ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

    for (ITextFrame textFrame : slideTextFrames) {
        for (IParagraph paragraph : textFrame.getParagraphs()) {
            for (IPortion portion : paragraph.getPortions()) {
                System.out.print(portion.getText());
                System.out.print(portion.getPortionFormat().getFontHeight());
                System.out.print(portion.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java में ODP फ़ाइलें कैसे पार्स करें" intro="Aspose.Slides for Java से कोड की कुछ पंक्तियों में ODP प्रेज़ेंटेशन से टेक्स्ट निकालें।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास से `ODP` फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पहली स्लाइड के टेक्स्ट फ़्रेम पाने के लिए `SlideUtil.getAllTextBoxes` मेथड कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}हर `ITextFrame`, `IParagraph` और `IPortion` ऑब्जेक्ट पर लूप चलाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}हर `IPortion` ऑब्जेक्ट से टेक्स्ट, फ़ॉन्ट आकार और फ़ॉन्ट नाम पढ़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएँ" intro="Aspose.Slides for Java प्रमुख प्लेटफ़ॉर्म और ऑपरेटिंग सिस्टम का समर्थन करता है। सुनिश्चित करें कि आपके एनवायरनमेंट में निम्नलिखित पूर्वापेक्षाएँ हैं।" %}}

- JSP/JSF ऐप्लिकेशन और डेस्कटॉप ऐप्लिकेशन के लिए Java Runtime Environment वाला Microsoft Windows या कोई संगत ऑपरेटिंग सिस्टम।
- [Maven](https://releases.aspose.com/java/repo/) से Aspose.Slides for Java का नवीनतम संस्करण।

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides से निर्मित" title="टेक्स्ट और इमेज ऑनलाइन निकालें" description="मुफ़्त Aspose.Slides Parser ऐप [Aspose.Slides for Java](https://products.aspose.com/slides/hi/java/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी ODP फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Parser खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides आपकी फ़ाइलें कैसे पढ़ता है।
- एक ODP फ़ाइल अपलोड करें और उसका टेक्स्ट और इमेज पाएँ।
- सब कुछ एक ZIP आर्काइव के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

ODP एक्सटेंशन वाली फ़ाइलें OpenDocument Presentation फ़ॉर्मैट का उपयोग करती हैं। ODP फ़ाइल ऐसी स्लाइड्स संग्रहीत करती है, जिनमें टेक्स्ट, इमेज, फ़ॉर्मैटिंग, एनिमेशन और अन्य प्रेज़ेंटेशन सामग्री हो सकती है।

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="पार्सिंग के लिए अन्य समर्थित फ़ॉर्मैट" subTitle="Java से आप अन्य प्रेज़ेंटेशन फ़ॉर्मैट भी पार्स कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/parser/ppt/" name="PPT" description="PowerPoint 97-2003 प्रेज़ेंटेशन" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/parser/pptx/" name="PPTX" description="PowerPoint Open XML प्रेज़ेंटेशन" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
