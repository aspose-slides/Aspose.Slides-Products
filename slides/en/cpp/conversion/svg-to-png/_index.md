---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert SVG to PNG in C++
url: /cpp/conversion/svg-to-png/
keywords: SVG to PNG, Convert SVG to PNG, C++ API, C++ Library, SVG, PNG
description: Convert SVG to PNG in C++. Use Aspose.Slides for C++ to place an SVG image on a slide and render it as a PNG file.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert SVG to PNG in C++" h2="Convert SVG images to PNG using Aspose.Slides for C++ without Microsoft PowerPoint." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert SVG to PNG Using C++" variant="code" %}}

To convert SVG to PNG, create a `Presentation`, add the SVG image to a slide, render the slide with `GetImage`, and save the rendered image with `ImageFormat::Png`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="SVG to PNG C++ Conversion Source Code" >}}
```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

auto svgContent = File::ReadAllText(u"image.svg");
auto svgImage = MakeObject<SvgImage>(svgContent);
auto presentationImage = presentation->get_Images()->AddImage(svgImage);
slide->get_Shapes()->AddPictureFrame(
    ShapeType::Rectangle,
    0,
    0,
    presentationImage->get_Width(),
    presentationImage->get_Height(),
    presentationImage);

auto image = slide->GetImage(2.0, 2.0);
image->Save(u"image.png", ImageFormat::Png);
image->Dispose();

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert SVG to PNG in C++" %}}

[Aspose.Slides for C++](/slides/cpp/) can add SVG images to slides and render those slides as PNG files. Use this approach when you need to convert an SVG asset to a raster image in a C++ application.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert SVG to PNG Using Aspose.Slides for C++ API" intro="These are the steps to convert SVG to PNG in C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for C++](/slides/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a library reference to your C++ project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` instance and add the SVG image to a slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render the slide with `GetImage` and save the image with `ImageFormat::Png`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert SVG to Other Supported Formats" subTitle="You can also convert SVG images and save them to other file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
