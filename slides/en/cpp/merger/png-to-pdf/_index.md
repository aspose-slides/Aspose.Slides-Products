---
title: Merge PNG to PDF in C++
url: /cpp/merger/png-to-pdf/
keywords: PNG to PDF, Merge PNG to PDF, Join PNG to PDF, PDF, PNG, C++ API, C++ Library
description: Merge PNG images into a PDF file in C++. Use Aspose.Slides for C++ to place PNG images on a slide and save the result as PDF.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PNG to PDF in C++" h2="Use Aspose.Slides for C++ to combine PNG images and save the result as PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Merge PNG to PDF using Aspose.Slides" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a C++ API for working with presentations, images, and `PDF` output. You can add `PNG` images to a slide as picture frames and save the presentation as a `PDF` file.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge PNG to PDF in C++" %}}
Using [**Aspose.Slides for C++**](/slides/cpp/), you can merge `PNG` images by adding them with `AddImage` and `AddPictureFrame`, then saving the presentation with `SaveFormat::Pdf`.

{{% blocks/products/pf/agp/code-block title="C++ code for merging PNG to PDF" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

auto firstImageData = File::ReadAllBytes(u"first.png");
auto firstImage = presentation->get_Images()->AddImage(firstImageData);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0, 0, 320, 240, firstImage);

auto secondImageData = File::ReadAllBytes(u"second.png");
auto secondImage = presentation->get_Images()->AddImage(secondImageData);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0, 260, 320, 240, secondImage);

presentation->Save(u"merged.pdf", SaveFormat::Pdf);
presentation->Dispose();
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge PNG to PDF in C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for C++**. See [**Installation**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` instance and access the slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Add the source `PNG` files with `AddImage` and place them with `AddPictureFrame`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the merged file with `SaveFormat::Pdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget appName="merger" extension="" sectionTitle="Merge Files Online" sectionDescription="Merge presentations, documents, and images online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge other files" subTitle="You can also combine files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/html-to-image/" name="HTML TO IMAGE" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}