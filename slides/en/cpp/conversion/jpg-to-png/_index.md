---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert JPG to PNG in C++
url: /cpp/conversion/jpg-to-png/
keywords: JPG to PNG, Convert JPG to PNG, C++ API, C++ Library, JPG, PNG
description: Convert JPG to PNG in C++. Use the C++ library API to convert JPG files to PNG images.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert JPG to PNG in C++" h2="Convert JPG files to PNG images using Aspose.Slides for C++ without Microsoft PowerPoint." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert JPG to PNG Using C++" variant="code" %}}

To convert JPG to PNG, create a new Presentation, add the JPG file to its image collection, place it on a slide with `AddPictureFrame`, and render the slide as a PNG image.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ code for converting JPG into PNG" >}}
```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

auto imageData = File::ReadAllBytes(u"image.jpg");
auto presentationImage = presentation->get_Images()->AddImage(imageData);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, presentationImage);

// Render the slide to an image.
auto slideImage = slide->GetImage(2.0f, 2.0f);

// Save the image in PNG format.
slideImage->Save(u"slide.png", ImageFormat::Png);
slideImage->Dispose();

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert JPG to PNG in C++" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a presentation processing API that can import JPG files into slides and render the result as PNG images. Using **Aspose.Slides for C++**, developers can convert JPG files to PNG images with just a few lines of C++ code.

Aspose.Slides for C++ can convert JPG content to PNG images and other presentation-related formats.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert JPG to PNG using Aspose.Slides for C++ API" intro="These are the steps to convert JPG to PNG in C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for C++**](/slides/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a library reference to your C++ project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source JPG file in C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the result as a PNG image.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free Online Converter"
  description="Convert presentations and slides online." >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert JPG to Other Supported Formats" subTitle="You can also convert JPG files and save them to other file formats. See all supported formats below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
