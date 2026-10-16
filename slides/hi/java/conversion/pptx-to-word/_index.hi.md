---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: जावा में पीपीटीएक्स को वर्ड में कनवर्ट करें
url: /hi/java/conversion/pptx-to-word/
keywords: PPTX को Word, PPTX को Word, PPTX को DOC, PowerPoint को Word, Java API, Java लाइब्रेरी में कनवर्ट करें
description: जावा में पीपीटीएक्स को वर्ड में कनवर्ट करें। PowerPoint को Word में बदलने के लिए Java लाइब्रेरी API का उपयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="जावा में पीपीटीएक्स को वर्ड में कनवर्ट करें" h2="Microsoft PowerPoint या Office के बिना Java कोड का उपयोग करके PowerPoint को Word में परिवर्तित करने के लिए शक्तिशाली क्रॉस-प्लेटफ़ॉर्म Java API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="जावा में PowerPoint को Word में कनवर्ट करें" variant="code" %}}

आप कोड की कुछ पंक्तियों के साथ जल्दी से PPTX को Word में बदल सकते हैं

{{< blocks/products/pf/slides-design-update-10-2026/code title="PowerPoint को Word में बदलने के लिए Java कोड" >}}
```java
Presentation pres = new Presentation(inputPres);
try {
    Document doc = new Document();
    DocumentBuilder builder = new DocumentBuilder(doc);
    for (ISlide slide : pres.getSlides())
    {
        // generates and inserts slide image
        BufferedImage bitmap = slide.getThumbnail(1, 1);

        builder.insertImage(bitmap);

        // inserts slide's texts
        for (IShape shape : slide.getShapes())
        {
            if (shape instanceof AutoShape)
            {
                builder.writeln(((AutoShape)shape).getTextFrame().getText());
            }
        }

        builder.insertBreak(BreakType.PAGE_BREAK);
    }
    doc.save(outputDoc);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides और Aspose.Words का उपयोग करके PowerPoint को Word में कनवर्ट करें" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) और [**Aspose.Words for Java**](https://products.aspose.com/ Words/java/) शक्तिशाली Java लाइब्रेरी हैं जिनका उपयोग PowerPoint प्रस्तुतियों, Word दस्तावेज़ों और अन्य फ़ाइलों में हेरफेर करने और उन्हें बदलने के लिए किया जाता है। जब आप PowerPoint को Word में कनवर्ट करते हैं, तो आप अनिवार्य रूप से किसी Word दस्तावेज़ में किसी प्रस्तुति की स्लाइड्स की सामग्री को पृष्ठों पर ले जा रहे होते हैं।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="पीपीटीएक्स को वर्ड में कैसे बदलें" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for Java** और **Aspose.Words for Java** इंस्टॉल करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेजेंटेशन क्लास और डॉक क्लास का एक उदाहरण बनाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पीपीटीएक्स प्रस्तुति को लोड करें जिसे आप वर्ड में कनवर्ट करना चाहते हैं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}स्लाइड्स की सामग्री के आधार पर चित्र और टेक्स्ट उत्पन्न करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}परिणामी Word दस्तावेज़ को सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="मुफ्त ऑनलाइन कनवर्टर"
  description="[पायथन में पीपीटी को एचटीएमएल में कैसे बदलें](https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित रूपांतरण" subTitle="आप PowerPoint को अन्य स्वरूपों में फ़ाइलों में भी रूपांतरित कर सकते हैं" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
