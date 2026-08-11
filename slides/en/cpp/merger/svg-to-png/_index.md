---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge SVG to PNG in C++
url: /cpp/merger/svg-to-png/
keywords: Merge SVG to PNG, SVG to PNG, Join SVG to PNG, Combine SVG to PNG, C++ API, C++ Library
description: Merge SVG files into a PNG image in C++. Use Aspose.Slides for C++ to place SVG images on a slide and render the result as PNG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge SVG to PNG in C++" h2="Use Aspose.Slides for C++ to combine SVG images and save the result as PNG." >}}

{{% blocks/products/pf/feature-page-section h2="Merge SVG to PNG using Aspose.Slides" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a C++ API for working with presentations and image content. You can read `SVG` files, add them to a slide as picture frames, and render the slide as a `PNG` image.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge SVG to PNG in C++" %}}
Using [**Aspose.Slides for C++**](/slides/cpp/), you can merge `SVG` files by creating `SvgImage` objects, adding them with `AddImage` and `AddPictureFrame`, rendering the slide with `GetImage`, and saving it with `ImageFormat::Png`.

{{% blocks/products/pf/agp/code-block title="C++ code for merging SVG to PNG" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

auto firstSvgContent = File::ReadAllText(u"first.svg");
auto firstSvgImage = MakeObject<SvgImage>(firstSvgContent);
auto firstPresentationImage = presentation->get_Images()->AddImage(firstSvgImage);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0, 0, 320, 240, firstPresentationImage);

auto secondSvgContent = File::ReadAllText(u"second.svg");
auto secondSvgImage = MakeObject<SvgImage>(secondSvgContent);
auto secondPresentationImage = presentation->get_Images()->AddImage(secondSvgImage);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0, 260, 320, 240, secondPresentationImage);

auto image = slide->GetImage(2.0, 2.0);
image->Save(u"merged.png", ImageFormat::Png);
image->Dispose();

presentation->Dispose();
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge SVG to PNG in C++" >}}

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
Read the source `SVG` files and place them with `AddPictureFrame`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render the slide with `GetImage` and save it with `ImageFormat::Png`.
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
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/html-to-image/" name="HTML TO IMAGE" >}}
  
{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
