---
title: Merge SVG to PNG in C#
url: /net/merger/svg-to-png/
keywords: Merge SVG to PNG, SVG to PNG, Join SVG to PNG, Combine SVG to PNG, C# API, .NET Library
description: Merge SVG to PNG in C#. Use the .NET library API to combine SVG files and render the result as a PNG image.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge SVG to PNG in C#" h2="Combine SVG images and render the result as PNG with a cross-platform .NET API." >}}

{{% blocks/products/pf/feature-page-section h2="Merge SVG to PNG using Aspose.Slides" %}}

[**Aspose.Slides for .NET**](/slides/net/) lets you create, convert, merge, and manipulate presentations, images, and other files. You can place multiple SVG images on a slide and render the result as a PNG image.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge SVG to PNG in C#" %}}
Using [**Aspose.Slides for .NET**](/slides/net/), you can add SVG images to a `Presentation` object and render the merged slide with `GetImage`.

{{% blocks/products/pf/agp/code-block title="C# code for merging SVG to PNG" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
var slide = presentation.Slides[0];

var firstSvgImage = new SvgImage("image1.svg");
var firstPresentationImage = presentation.Images.AddImage(firstSvgImage);
slide.Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 360, 270, firstPresentationImage);

var secondSvgImage = new SvgImage("image2.svg");
var secondPresentationImage = presentation.Images.AddImage(secondSvgImage);
slide.Shapes.AddPictureFrame(ShapeType.Rectangle, 360, 0, 360, 270, secondPresentationImage);

using var image = slide.GetImage(1f, 1f);
image.Save("merged.png", ImageFormat.Png);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge SVG to PNG in C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install **Aspose.Slides for .NET**. See [**Installation**](https://docs.aspose.com/slides/net/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Add the library as a reference in your project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` object.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the source SVG images to a slide as picture frames.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Render the slide with `GetImage` and save the PNG image.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="png" sectionTitle="Merge SVG to PNG Online" sectionDescription="Combine files online with Aspose.Slides Merger." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge other files" subTitle="You can also combine files in other formats to get a single file" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/html-to-image/" name="HTML TO IMAGE" >}}
  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
