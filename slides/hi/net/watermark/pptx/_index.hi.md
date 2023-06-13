---
title: .NET का उपयोग करके PPTX प्रस्तुतिकरण फ़ाइलों में वॉटरमार्क जोड़ें
url: /hi/net/watermark/pptx/
keywords: वॉटरमार्क जोड़ें PPTX, टेक्स्ट वॉटरमार्क जोड़ें PPTX, छवि वॉटरमार्क जोड़ें PPTX
description: वॉटरमार्क को PPTX प्रस्तुतिकरण में जोड़ने के लिए C# स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C# का उपयोग करके PPTX प्रस्तुतिकरण में वॉटरमार्क जोड़ें" h2="सर्वर-साइड API का उपयोग करके PPT, PPTX, या ODP प्रस्तुति में टेक्स्ट या इमेज वॉटरमार्क डालने के लिए अपना खुद का .NET ऐप्लिकेशन बनाएं." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="C# द्वारा PPTX प्रस्तुतिकरण में वॉटरमार्क जोड़ें" %}}
{Product_name} का उपयोग करके, आप वॉटरमार्क को PPTX प्रस्तुतिकरण में जोड़ सकते हैं। वॉटरमार्क किसी भी प्रस्तुति का एक अनिवार्य हिस्सा हैं। इनका उपयोग प्रस्तुति की सामग्री को कॉपी किए जाने या अनुमति के बिना उपयोग किए जाने से बचाने के लिए किया जाता है। वॉटरमार्क एक दृश्य या अदृश्य छवि या पाठ है जिसे प्रस्तुति के शीर्ष पर रखा जाता है। इसका उपयोग प्रस्तुति के स्वामी की पहचान करने और अनधिकृत उपयोग को रोकने के लिए किया जा सकता है। वॉटरमार्क का उपयोग प्रस्तुति में एक पेशेवर स्पर्श जोड़ने और इसे और अधिक परिष्कृत दिखाने के लिए भी किया जा सकता है। 
{{% blocks/products/pf/agp/code-block title="C# का उपयोग करके PPTX में टेक्स्ट वॉटरमार्क जोड़ें" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");

    presentation.Save("watermark.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# का उपयोग करके PPTX प्रस्तुतिकरण में इमेज वॉटरमार्क जोड़ें" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);

    IPPImage image = presentation.Images.AddImage(File.ReadAllBytes("watermark.png"));

    watermarkShape.FillFormat.FillType = FillType.Picture;
    watermarkShape.FillFormat.PictureFillFormat.Picture.Image = image;
    watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

    presentation.Save("watermark2.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C# के द्वारा PPTX में वॉटरमार्क कैसे जोड़ें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये PPTX फ़ाइलों में टेक्स्ट वॉटरमार्क जोड़ने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति के उदाहरण के साथ PPTX लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
मास्टर प्रस्तुति का चयन करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddAutoShape पद्धति का उपयोग करके आकृति प्रकार जोड़ें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddTextFrame पद्धति का उपयोग करके वॉटरमार्क टेक्स्ट जोड़ें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम PPTX प्रारूप में सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित प्रारूप" subTitle="C# का उपयोग करके, आप निम्न स्वरूपों में वॉटरमार्क भी जोड़ सकते हैं:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}