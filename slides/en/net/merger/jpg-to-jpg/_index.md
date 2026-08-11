---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge JPG Images in C#
url: /net/merger/jpg-to-jpg/
keywords: Merge JPG, JPG to JPG, Join JPG, Combine JPG, C# API, .NET Library
description: Merge JPG images in C#. Use the .NET library API to combine JPG files and render the result as a JPG image.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge JPG in C#" h2="Combine JPG images with a cross-platform .NET API." >}}

{{% blocks/products/pf/feature-page-section h2="Merge JPG to JPG using Aspose.Slides" %}}

[**Aspose.Slides for .NET**](/slides/net/) lets you create, convert, merge, and manipulate presentations, images, and other files. You can place multiple JPG images on a slide and render the result as a JPG image.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge JPG to JPG in C#" %}}
Using [**Aspose.Slides for .NET**](/slides/net/), you can add JPG images to a `Presentation` object and render the merged slide with `GetImage`.

{{% blocks/products/pf/agp/code-block title="C# code for merging JPG to JPG" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
var slide = presentation.Slides[0];

var firstImageData = File.ReadAllBytes("image1.jpg");
var firstPresentationImage = presentation.Images.AddImage(firstImageData);
slide.Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 360, 270, firstPresentationImage);

var secondImageData = File.ReadAllBytes("image2.jpg");
var secondPresentationImage = presentation.Images.AddImage(secondImageData);
slide.Shapes.AddPictureFrame(ShapeType.Rectangle, 360, 0, 360, 270, secondPresentationImage);

using var image = slide.GetImage(1f, 1f);
image.Save("merged.jpg", ImageFormat.Jpeg);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge JPG in C#" >}}


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

{{% blocks/products/pf/agp/step-autogen %}}
Add the source JPG images to a slide as picture frames.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render the slide with `GetImage` and save the JPG image.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Merge JPG Images Online" sectionDescription="Combine files online with Aspose.Slides Merger." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge other files" subTitle="You can also combine files in other formats to get a single file" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/png-to-pdf/" name="PNG TO PDF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
