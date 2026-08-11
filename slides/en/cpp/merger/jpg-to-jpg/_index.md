---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge JPG Images in C++
url: /cpp/merger/jpg-to-jpg/
keywords: Merge JPG, JPG to JPG, Join JPG, Combine JPG, C++ API, C++ Library
description: Merge JPG images in C++. Use Aspose.Slides for C++ to place JPG images on a slide and render the result as a JPG file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge JPG Images in C++" h2="Use Aspose.Slides for C++ to combine JPG images in C++ applications." >}}

{{% blocks/products/pf/feature-page-section h2="Merge JPG to JPG using Aspose.Slides" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a C++ API for working with presentations and image content. You can add multiple `JPG` images to a slide as picture frames and render the slide as a single `JPG` file.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge JPG to JPG in C++" %}}
Using [**Aspose.Slides for C++**](/slides/cpp/), you can merge `JPG` images by adding them with `AddImage` and `AddPictureFrame`, rendering the slide with `GetImage`, and saving it with `ImageFormat::Jpeg`.

{{% blocks/products/pf/agp/code-block title="C++ code for merging JPG to JPG" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

auto firstImageData = File::ReadAllBytes(u"first.jpg");
auto firstImage = presentation->get_Images()->AddImage(firstImageData);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0, 0, 320, 240, firstImage);

auto secondImageData = File::ReadAllBytes(u"second.jpg");
auto secondImage = presentation->get_Images()->AddImage(secondImageData);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0, 260, 320, 240, secondImage);

auto image = slide->GetImage(2.0, 2.0);
image->Save(u"merged.jpg", ImageFormat::Jpeg);
image->Dispose();

presentation->Dispose();
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge JPG images in C++" >}}

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
Add the source `JPG` files with `AddImage` and place them with `AddPictureFrame`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render the slide with `GetImage` and save it with `ImageFormat::Jpeg`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget appName="merger" extension="" sectionTitle="Merge Files Online" sectionDescription="Merge presentations, documents, and images online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge other files" subTitle="You can also combine files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/merger/png-to-pdf/" name="PNG TO PDF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}