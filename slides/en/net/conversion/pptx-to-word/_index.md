---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTX to Word in C#
url: /net/conversion/pptx-to-word/
keywords: Convert PPTX to Word, PPTX to Word, PPTX to DOC, PowerPoint to Word, C# API, .NET Library
description: Convert PPTX to Word in C#. Use Aspose.Slides for .NET and Aspose.Words for .NET to render PowerPoint slides as images in a DOCX document.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTX to Word in C#" h2="Render PowerPoint slides as images in Word using Aspose.Slides for .NET and Aspose.Words for .NET." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Word Using Aspose.Slides and Aspose.Words" %}}

[Aspose.Slides for .NET](/slides/net/) can render presentation slides as images, while [Aspose.Words for .NET](https://products.aspose.com/words/net/) can insert those images into a Word document and save it in DOCX format.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Convert PowerPoint to Word in C#" %}}
You can convert PPTX to Word with the following C# code:

{{% blocks/products/pf/agp/code-block title="C# code for converting PowerPoint to Word" offSpacer="true" %}}
```cs
using Aspose.Slides;
using Aspose.Words;
using System.IO;

using var presentation = new Presentation("template.pptx");
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




{{< blocks/products/pf/feature-page-section  h2="How to Convert PPTX to Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install `Aspose.Slides for .NET` and `Aspose.Words for .NET`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PPTX file with a `Presentation` object.
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




{{< blocks/slides-app-widget  appName="conversion" extension="pptx-to-word" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert PowerPoint to files in other formats." >}}




{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
