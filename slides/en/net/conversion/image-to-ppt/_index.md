---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert Image to PPT in C#
url: /net/conversion/image-to-ppt/
keywords: Convert Image to PPT, Image to PPT, PowerPoint, Image, PPT, C# API, .NET Library
description: Convert an image to PPT in C# using Aspose.Slides for .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert Image to PPT in C#" h2="Convert images to PPT presentations in C# using server-side Aspose.Slides APIs." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert Image to PPT in C#" variant="code" %}}

Use [Aspose.Slides for .NET](/slides/net/) to convert an image to a PPT presentation with a few lines of C# code:

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# code for converting Image to PPT" >}}
```cs
using var presentation = new Presentation();

var imageBytes = File.ReadAllBytes("image.jpg");
var presentationImage = presentation.Images.AddImage(imageBytes);

var slide = presentation.Slides[0];
slide.Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, presentationImage);

presentation.Save("Presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert Image to PPT using Aspose.Slides" %}}

[Aspose.Slides for .NET](/slides/net/) lets you create a PPT presentation from image files. The API adds the image to a slide and saves the result as a PowerPoint presentation.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert Image to PPT in C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for .NET**. See [**Installation**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the library as a reference in your project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the image file bytes.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `Save` method with `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free Online Converter"
  description="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported PowerPoint Conversions" subTitle="You can also convert files in other formats to PowerPoint" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
