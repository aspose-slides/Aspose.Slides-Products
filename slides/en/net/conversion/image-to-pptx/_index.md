---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert Image to PPTX in C#
url: /net/conversion/image-to-pptx/
keywords: Convert Image to PPTX, Image to PPTX, PowerPoint, Image, PPTX, C# API, .NET Library
description: Convert an image to PPTX in C# using Aspose.Slides for .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert Image to PPTX in C#" h2="Convert images to PPTX presentations in C# using server-side Aspose.Slides APIs." >}}

{{% blocks/products/pf/feature-page-section h2="Convert Image to PPTX using Aspose.Slides" %}}

[Aspose.Slides for .NET](/slides/net/) lets you create a PPTX presentation from image files. The API adds the image to a slide and saves the result as a PowerPoint presentation.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Convert Image to PPTX in C#" %}}
Use [Aspose.Slides for .NET](/slides/net/) to convert an image to a PPTX presentation with a few lines of C# code:

{{% blocks/products/pf/agp/code-block title="C# code for converting Image to PPTX" offSpacer="true" %}}
```cs
using var presentation = new Presentation();

var imageBytes = File.ReadAllBytes("image.jpg");
var presentationImage = presentation.Images.AddImage(imageBytes);

var slide = presentation.Slides[0];
slide.Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, presentationImage);

presentation.Save("Presentation.pptx", SaveFormat.Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to Convert Image to PPTX in C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for .NET**. See [**Installation**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` object.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the image file bytes.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Call the `Save` method with `SaveFormat.Pptx`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported PowerPoint Conversions" subTitle="You can also convert files in other formats to PowerPoint" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
