---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPT to Word in C#
url: /net/conversion/ppt-to-word/
keywords: Convert PPT to Word, PPT to Word, PPT to DOC, PowerPoint to Word, C# API, .NET Library
description: Convert PPT to Word in C#. Use Aspose.Slides for .NET and Aspose.Words for .NET to render PowerPoint slides as images in a DOCX document.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPT to Word in C#" h2="Render PowerPoint slides as images in Word using Aspose.Slides for .NET and Aspose.Words for .NET." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Word Using Aspose.Slides and Aspose.Words" %}}

[Aspose.Slides for .NET](/slides/net/) can render presentation slides as images, while [Aspose.Words for .NET](https://products.aspose.com/words/net/) can insert those images into a Word document and save it in DOCX format.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Convert PowerPoint to Word in C#" %}}
You can convert PPT to Word with the following C# code:

{{% blocks/products/pf/agp/code-block title="C# code for converting PowerPoint to Word" offSpacer="true" %}}
```cs
using Aspose.Slides;
using Aspose.Words;
using System.IO;

using var presentation = new Presentation("template.ppt");
var wordDocument = new Aspose.Words.Document();
var documentBuilder = new DocumentBuilder(wordDocument);

foreach (var slide in presentation.Slides)
{
    using var slideImage = slide.GetImage(1f, 1f);
    using var imageStream = new MemoryStream();
    slideImage.Save(imageStream, ImageFormat.Png);
    imageStream.Position = 0;

    documentBuilder.InsertImage(imageStream);
    documentBuilder.InsertBreak(BreakType.PageBreak);
}

wordDocument.Save("document.docx");
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to Convert PPT to Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install `Aspose.Slides for .NET` and `Aspose.Words for .NET`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PPT file with a `Presentation` object.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a Word `Document` and `DocumentBuilder`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render slide images with `GetImage` and insert them with `DocumentBuilder`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the Word document as DOCX.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="ppt-to-word" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert PowerPoint to files in other formats." >}}


{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Bitmap Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-emf/" name="PPT TO EMF" description="Enhanced Metafile Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-gif/" name="PPT TO GIF" description="Graphics Interchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-html/" name="PPT TO HTML" description="Hypertext Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" description="JPEG Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-odp/" name="PPT TO ODP" description="OpenDocument Presentation Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-otp/" name="PPT TO OTP" description="OpenDocument Presentation Template" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-pdf/" name="PPT TO PDF" description="Portable Document Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-png/" name="PPT TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-pot/" name="PPT TO POT" description="PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-potm/" name="PPT TO POTM" description="PowerPoint Macro-Enabled Template" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-potx/" name="PPT TO POTX" description="PowerPoint Open XML Template" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-pps/" name="PPT TO PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Macro-Enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="PowerPoint Open XML Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Macro-Enabled Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Open XML Presentation Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-svg/" name="PPT TO SVG" description="Scalable Vector Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-swf/" name="PPT TO SWF" description="SWF Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Tagged Image File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-video/" name="PPT TO VIDEO" description="Video Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/ppt-to-xps/" name="PPT TO XPS" description="XML Paper Specification" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
