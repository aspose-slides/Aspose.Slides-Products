---
title: Merge PNG to PDF in C#
url: /net/merger/png-to-pdf/
keywords: PNG to PDF, Merge PNG to PDF, Join PNG to PDF, PDF, PNG, C# API, .NET Library
description: Merge PNG images to PDF in C#. Use the .NET library API to combine PNG files into a single PDF document.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PNG to PDF in C#" h2="Combine PNG images into PDF documents with a cross-platform .NET API." >}}

{{% blocks/products/pf/feature-page-section h2="Merge PNG to PDF using Aspose.Slides" %}}

[**Aspose.Slides for .NET**](/slides/net/) lets you create, convert, merge, and manipulate presentations, PDFs, images, and other files. You can place PNG images on slides and save the result as a single PDF document.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge PNG to PDF in C#" %}}
Using [**Aspose.Slides for .NET**](/slides/net/), you can add PNG images to a `Presentation` object and save the presentation with `SaveFormat.Pdf`.

{{% blocks/products/pf/agp/code-block title="C# code for merging PNG to PDF" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
presentation.Slides.RemoveAt(0);

var layoutSlide = presentation.LayoutSlides[0];

foreach (var imagePath in new[] { "image1.png", "image2.png" })
{
    var slide = presentation.Slides.AddEmptySlide(layoutSlide);

    var imageData = File.ReadAllBytes(imagePath);
    var presentationImage = presentation.Images.AddImage(imageData);
    slide.Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, presentationImage);
}

presentation.Save("merged.pdf", SaveFormat.Pdf);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge PNG to PDF in C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install **Aspose.Slides for .NET**. See [**Installation**](https://docs.aspose.com/slides/net/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` object.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Add each source PNG image to a slide as a picture frame.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the presentation with `SaveFormat.Pdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="png" sectionTitle="Merge PNG Images Online" sectionDescription="Combine files online with Aspose.Slides Merger." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge other files" subTitle="You can also combine files in other formats to get a single file" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/merger/html-to-image/" name="HTML TO IMAGE" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}