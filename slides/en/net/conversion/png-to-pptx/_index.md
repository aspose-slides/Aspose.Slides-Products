---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PNG to PPTX in C#
url: /net/conversion/png-to-pptx/
keywords: Convert PNG to PPTX, PNG to PPTX, PowerPoint, PNG, PPTX, C# API, .NET Library
description: Convert PNG to PPTX in C# using Aspose.Slides for .NET. Use the sample code in C# applications, including ASP.NET projects.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PNG to PPTX in C#" h2="Convert PNG files to PPTX in C# using server-side Aspose.Slides APIs." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PNG to PPTX using Aspose.Slides" %}}

[Aspose.Slides for .NET](/slides/net/) lets you add a PNG image to a slide and save the result as a PPTX file.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Convert PNG to PPTX in C#" %}}
Use [Aspose.Slides for .NET](/slides/net/) to convert a PNG image to a PPTX presentation in a few lines of C# code:

{{% blocks/products/pf/agp/code-block title="C# code for converting PNG to PPTX" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
var slide = presentation.Slides[0];

var imageData = File.ReadAllBytes("image.png");
var presentationImage = presentation.Images.AddImage(imageData);
slide.Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, presentationImage);

presentation.Save("presentation.pptx", SaveFormat.Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to convert PNG to PPTX in C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name=".NET developers can convert PNG files to PPTX in a few lines of code." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` object.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the PNG image to the presentation images collection.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Add the image to a slide with `Shapes.AddPictureFrame`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call the `Save` method with the output file path and `SaveFormat.Pptx`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported PowerPoint Conversions" subTitle="You can also convert files in other formats to PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
