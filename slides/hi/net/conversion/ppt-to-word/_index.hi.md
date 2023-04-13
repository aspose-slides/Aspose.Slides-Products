---
title: सी # में पीपीटी को वर्ड में कनवर्ट करें
url: /hi/net/conversion/ppt-to-word/
keywords: PPT को Word में, PPT को Word में, PPT को DOC में, PowerPoint को Word में, C# API, .NET लाइब्रेरी में कन्वर्ट करें
description: सी # में पीपीटी को वर्ड में कनवर्ट करें। PowerPoint को Word में बदलने के लिए .NET लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="सी # में पीपीटी को वर्ड में कनवर्ट करें" h2="शक्तिशाली क्रॉस-प्लेटफ़ॉर्म .NET API, NET फ्रेमवर्क, .NET Core, Windows Azure, Mono या Xamarin प्लेटफ़ॉर्म पर C# कोड का उपयोग करके PowerPoint को Word में कनवर्ट करने के लिए" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides और Aspose.Words का उपयोग करके PowerPoint को Word में कनवर्ट करें" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hi/net/) और [**Aspose.Words for .NET**](https://products.aspose. com/words/net/) शक्तिशाली .NET लाइब्रेरी हैं जिनका उपयोग PowerPoint प्रस्तुतियों, Word दस्तावेज़ों और अन्य फ़ाइलों में हेरफेर करने और उन्हें बदलने के लिए किया जाता है। जब आप PowerPoint को Word में कनवर्ट करते हैं, तो आप अनिवार्य रूप से किसी Word दस्तावेज़ में किसी प्रस्तुति की स्लाइड्स की सामग्री को पृष्ठों पर ले जा रहे होते हैं।

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PowerPoint को Word में C# में कनवर्ट करें" %}}
आप कोड की केवल कुछ पंक्तियों के साथ PPT को Word में शीघ्रता से रूपांतरित कर सकते हैं

{{% blocks/products/pf/agp/code-block title="PowerPoint को Word में कनवर्ट करने के लिए C# कोड" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
var doc = new Document();
var builder = new DocumentBuilder(doc);
foreach (var slide in presentation.Slides)
{
    // generates and inserts slide image
    using var bitmap = slide.GetThumbnail(1, 1);
    using var stream = new MemoryStream();
    bitmap.Save(stream, ImageFormat.Png);
    stream.Seek(0, SeekOrigin.Begin);
    using var skBitmap = SKBitmap.Decode(stream);
    builder.InsertImage(skBitmap);

    // inserts slide texts
    foreach (var shape in slide.Shapes)
    {
        if (shape is AutoShape autoShape)
        {
            builder.Writeln(autoShape.TextFrame.Text);
        }
    }

    builder.InsertBreak(BreakType.PageBreak);
}
doc.Save("document.docx");
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="पीपीटी को वर्ड में कैसे बदलें" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for .NET** और **Aspose.Words for .NET** इंस्टॉल करें 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपनी परियोजना में दो पुस्तकालयों को संदर्भ के रूप में जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रेजेंटेशन क्लास और डॉक क्लास का एक उदाहरण बनाएँ।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
उस PPT प्रस्तुति को लोड करें जिसे आप Word में बदलना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
स्लाइड्स की सामग्री के आधार पर चित्र और टेक्स्ट उत्पन्न करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणामी Word दस्तावेज़ को सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="मुफ्त ऑनलाइन कनवर्टर" sectionDescription="[पायथन में पीपीटी को एचटीएमएल में कैसे बदलें](https://products.aspose.com/slides/hi/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप PowerPoint को अन्य स्वरूपों में फ़ाइलों में भी रूपांतरित कर सकते हैं" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}