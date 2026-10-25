---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java से PPS फ़ाइल मेटाडेटा देखें या संपादित करें
url: /hi/java/metadata/pps/
description: Java में PPS मेटाडेटा देखें और संपादित करें। प्रेज़ेंटेशन की बिल्ट-इन और कस्टम प्रॉपर्टी अपडेट करने के लिए Aspose.Slides for Java का उपयोग करें।
keywords: PPS मेटाडेटा संपादित करें, PPS मेटाडेटा देखें, PPS प्रॉपर्टी संपादित करें, PPS प्रॉपर्टी देखें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java से PPS प्रॉपर्टी संपादित करें" h2="ऐसे Java ऐप्लिकेशन बनाएँ जो सर्वर-साइड API से प्रेज़ेंटेशन फ़ाइलों की बिल्ट-इन और कस्टम प्रॉपर्टी बदलें।" related="FODP,ODP,OTP,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java से PPS प्रॉपर्टी बदलें" variant="code" %}}

[Aspose.Slides for Java](/slides/hi/java/) से डेवलपर प्रेज़ेंटेशन की बिल्ट-इन और कस्टम प्रॉपर्टी तक पहुँच सकते हैं और उन्हें बदल सकते हैं। प्रेज़ेंटेशन फ़ाइल का `IDocumentProperties` ऑब्जेक्ट पाने के लिए `Presentation` ऑब्जेक्ट की `getDocumentProperties` मेथड का उपयोग करें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPS की बिल्ट-इन प्रॉपर्टी बदलें – Java" >}}
```java
Presentation presentation = new Presentation("Presentation.pps");
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.setAuthor("Aspose.Slides for Java");
    documentProperties.setTitle("Modifying Presentation Properties");
    documentProperties.setSubject("Aspose Subject");
    documentProperties.setComments("Aspose Description");
    documentProperties.setManager("Aspose Manager");

    presentation.save("DocProps.pps", SaveFormat.Pps);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="PPS में कस्टम प्रॉपर्टी जोड़ें – Java" >}}
```java
Presentation presentation = new Presentation();
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.set_Item("New Custom", 12);
    documentProperties.set_Item("My Name", "Aspose Metadata Editor");
    documentProperties.set_Item("Custom", 124);

    String customPropertyName = documentProperties.getCustomPropertyName(2);
    documentProperties.removeCustomProperty(customPropertyName);

    presentation.save("CustomDemo.pps", SaveFormat.Pps);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java में PPS मेटाडेटा कैसे देखें या संपादित करें" intro="PPS मेटाडेटा देखने या संपादित करने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास से `PPS` फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`IDocumentProperties` ऑब्जेक्ट पाने के लिए `getDocumentProperties` मेथड कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Author`, `Title`, `Subject` और `Comments` जैसी बिल्ट-इन प्रॉपर्टी पढ़ें या अपडेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`set_Item`, `getCustomPropertyName` और `removeCustomProperty` से कस्टम प्रॉपर्टी तक पहुँचें और उन्हें बदलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Aspose.Slides से निर्मित" title="PPS मेटाडेटा ऑनलाइन देखें और संपादित करें" description="मुफ़्त Aspose.Slides Metadata ऐप [Aspose.Slides for Java](https://products.aspose.com/slides/hi/java/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPS फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Metadata खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides प्रॉपर्टी कैसे पढ़ता और लिखता है।
- अपनी PPS फ़ाइल की बिल्ट-इन और कस्टम प्रॉपर्टी देखें और संपादित करें।
- अपडेट की गई फ़ाइल सहेजें और डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित मेटाडेटा फ़ॉर्मैट" subTitle="Java से आप निम्नलिखित फ़ॉर्मैट का मेटाडेटा भी प्रबंधित कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
