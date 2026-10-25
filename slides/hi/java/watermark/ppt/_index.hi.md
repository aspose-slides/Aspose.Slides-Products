---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java से PPT प्रेज़ेंटेशन फ़ाइलों में वॉटरमार्क जोड़ें
url: /hi/java/watermark/ppt/
description: Aspose.Slides for Java से Java में PPT प्रेज़ेंटेशन में टेक्स्ट और इमेज वॉटरमार्क जोड़ें।
keywords: PPT में वॉटरमार्क जोड़ें, PPT में टेक्स्ट वॉटरमार्क जोड़ें, PPT में इमेज वॉटरमार्क जोड़ें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java से PPT प्रेज़ेंटेशन में वॉटरमार्क जोड़ें" h2="ऐसे Java ऐप्लिकेशन बनाएँ जो सर्वर-साइड API से प्रेज़ेंटेशन फ़ाइलों में टेक्स्ट या इमेज वॉटरमार्क डालें।" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java के ज़रिए PPT प्रेज़ेंटेशन में वॉटरमार्क जोड़ें" variant="code" %}}

[Aspose.Slides for Java](/slides/hi/java/) से आप PPT प्रेज़ेंटेशन में टेक्स्ट और इमेज वॉटरमार्क जोड़ सकते हैं। मास्टर स्लाइड पर वॉटरमार्क शेप जोड़ें, ताकि वॉटरमार्क उन सभी स्लाइड पर दिखे जो उस मास्टर का उपयोग करती हैं।

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java से PPT में टेक्स्ट वॉटरमार्क जोड़ें" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Java से PPT प्रेज़ेंटेशन में इमेज वॉटरमार्क जोड़ें" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java से PPT में वॉटरमार्क कैसे जोड़ें" intro="PPT फ़ाइलों में टेक्स्ट या इमेज वॉटरमार्क जोड़ने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास से `PPT` फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`getMasters` मेथड से एक मास्टर स्लाइड चुनें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}वॉटरमार्क शेप जोड़ने के लिए `addAutoShape` मेथड कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}वॉटरमार्क टेक्स्ट जोड़ने के लिए `addTextFrame` मेथड कॉल करें या इमेज वॉटरमार्क के लिए `addImage` का उपयोग करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}वॉटरमार्क वाली प्रेज़ेंटेशन को PPT फ़ॉर्मैट में सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides से निर्मित" title="PPT फ़ाइलों में ऑनलाइन वॉटरमार्क जोड़ें" description="मुफ़्त Aspose.Slides Watermark ऐप [Aspose.Slides for Java](https://products.aspose.com/slides/hi/java/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPT फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Watermark खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides वॉटरमार्क कैसे जोड़ता है।
- अपनी PPT फ़ाइल में टेक्स्ट या इमेज वॉटरमार्क जोड़ें।
- वॉटरमार्क वाली फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="वॉटरमार्क के लिए अन्य समर्थित फ़ॉर्मैट" subTitle="Java से आप निम्नलिखित फ़ॉर्मैट में भी वॉटरमार्क जोड़ सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
