---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PNG to SVG in C++
url: /cpp/conversion/png-to-svg/
keywords: PNG to SVG, Convert PNG to SVG, C++ API, C++ Library, PNG, SVG
description: Convert PNG to SVG in C++. Use the C++ library API to add PNG images to slides and save slides as SVG files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PNG to SVG in C++" h2="Convert PNG images to SVG using Aspose.Slides for C++ without Microsoft PowerPoint." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to SVG Using C++" variant="code" %}}

To convert PNG to SVG, create a `Presentation`, add the PNG image to a slide, and write the slide to an SVG file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ code for converting PNG into SVG" >}}
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

auto fileStream = MakeObject<FileStream>(u"document.svg", FileMode::Create, FileAccess::Write);
slide->WriteAsSvg(fileStream);
fileStream->Dispose();

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to SVG in C++" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a presentation processing API that can create slides from images and write slides as SVG files. Using **Aspose.Slides for C++**, developers can convert PNG images to SVG with just a few lines of C++ code.

Aspose.Slides for C++ can place PNG images on slides and export the slides as SVG and other related formats.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PNG to SVG using Aspose.Slides for C++ API" intro="These are the steps to convert PNG to SVG in C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for C++**](/slides/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a library reference to your C++ project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` instance and add the PNG image to a slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Write the slide to an SVG file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="png-to-svg"
  title="Free Online Converter"
  description="Convert presentations and slides online." >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PNG to Other Supported Formats" subTitle="You can also convert PNG images and save them to other file formats. See all supported formats below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
