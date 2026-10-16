---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PNG to JPG in C++
url: /cpp/conversion/png-to-jpg/
keywords: PNG to JPG, Convert PNG to JPG, C++ API, C++ Library, PNG, JPG
description: Convert PNG to JPG in C++. Use the C++ library API to add PNG images to slides and render them as JPG images.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PNG to JPG in C++" h2="Convert PNG images to JPG using Aspose.Slides for C++ without Microsoft PowerPoint." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to JPG Using C++" variant="code" %}}

To convert PNG to JPG, create a `Presentation`, add the PNG image to a slide, render the slide, and save the image in JPG format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ code for converting PNG into JPG" >}}
```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);
auto slideSize = presentation->get_SlideSize()->get_Size();

auto imageData = File::ReadAllBytes(u"image.png");
auto presentationImage = presentation->get_Images()->AddImage(imageData);
slide->get_Shapes()->AddPictureFrame(
    ShapeType::Rectangle,
    0,
    0,
    slideSize.get_Width(),
    slideSize.get_Height(),
    presentationImage);

auto slideImage = slide->GetImage(2.0f, 2.0f);
slideImage->Save(u"document.jpg", ImageFormat::Jpeg);
slideImage->Dispose();

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to JPG in C++" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a presentation processing API that can create slides from images and render slides as image files. Using **Aspose.Slides for C++**, developers can convert PNG images to JPG with just a few lines of C++ code.

Aspose.Slides for C++ can place PNG images on slides and render the result as JPG and other related formats.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PNG to JPG using Aspose.Slides for C++ API" intro="These are the steps to convert PNG to JPG in C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for C++**](/slides/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a library reference to your C++ project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` instance and add the PNG image to a slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render the slide and save it as a JPG image.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="png-to-jpg"
  title="Free Online Converter"
  description="Convert presentations and slides online." >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PNG to Other Supported Formats" subTitle="You can also convert PNG images and save them to other file formats. See all supported formats below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
