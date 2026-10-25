---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C# से PPTX प्रेज़ेंटेशन में वॉटरमार्क जोड़ें
url: /hi/net/watermark/pptx/
description: Aspose.Slides for .NET से C# में PPTX प्रेज़ेंटेशन में टेक्स्ट और इमेज वॉटरमार्क जोड़ें।
keywords: PPTX में वॉटरमार्क जोड़ें, PPTX में टेक्स्ट वॉटरमार्क जोड़ें, PPTX में इमेज वॉटरमार्क जोड़ें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# से PPTX प्रेज़ेंटेशन में वॉटरमार्क जोड़ें" h2="ऐसे .NET ऐप्लिकेशन बनाएँ जो प्रेज़ेंटेशन फ़ाइलों में टेक्स्ट या इमेज वॉटरमार्क डालें।" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# के ज़रिए PPTX प्रेज़ेंटेशन में वॉटरमार्क जोड़ें" variant="code" %}}

[Aspose.Slides for .NET](/slides/hi/net/) से आप PPTX प्रेज़ेंटेशन में टेक्स्ट और इमेज वॉटरमार्क जोड़ सकते हैं। मास्टर स्लाइड पर वॉटरमार्क शेप जोड़ें, ताकि वॉटरमार्क उन सभी स्लाइड पर दिखे जो उस मास्टर का उपयोग करती हैं।

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# से PPTX में टेक्स्ट वॉटरमार्क जोड़ें" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C# से PPTX प्रेज़ेंटेशन में इमेज वॉटरमार्क जोड़ें" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# से PPTX में वॉटरमार्क कैसे जोड़ें" intro="PPTX फ़ाइलों में टेक्स्ट या इमेज वॉटरमार्क जोड़ने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास से `PPTX` फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation.Masters` कलेक्शन से एक मास्टर स्लाइड चुनें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}वॉटरमार्क शेप जोड़ने के लिए `AddAutoShape` मेथड कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}वॉटरमार्क टेक्स्ट जोड़ने के लिए `AddTextFrame` मेथड कॉल करें या इमेज वॉटरमार्क के लिए `AddImage` का उपयोग करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Pptx` से वॉटरमार्क वाली फ़ाइल सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides से निर्मित" title="PPTX फ़ाइलों में ऑनलाइन वॉटरमार्क जोड़ें" description="मुफ़्त Aspose.Slides Watermark ऐप [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPTX फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Watermark खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides वॉटरमार्क कैसे जोड़ता है।
- अपनी PPTX फ़ाइल में टेक्स्ट या इमेज वॉटरमार्क जोड़ें।
- वॉटरमार्क वाली फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="वॉटरमार्क के लिए अन्य समर्थित फ़ॉर्मैट" subTitle="C# से आप निम्नलिखित फ़ॉर्मैट में भी वॉटरमार्क जोड़ सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
