---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert JPG to Image in C++
url: /cpp/conversion/jpg-to-image/
keywords: JPG to Image, Convert JPG to Image, C++ API, C++ Library, JPG, Image
description: Convert JPG to image in C++. Use the C++ library API to convert JPG files to images.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert JPG to Image in C++" h2="Convert JPG files to images using Aspose.Slides for C++ without Microsoft PowerPoint." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert JPG to Image Using C++" variant="code" %}}

To convert JPG to another image format, create a new Presentation, add the JPG file to its image collection, place it on a slide with `AddPictureFrame`, and render the slide in the required image format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ code for converting JPG into Image" >}}
```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

auto imageData = File::ReadAllBytes(u"image.jpg");
auto presentationImage = presentation->get_Images()->AddImage(imageData);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, presentationImage);

// Convert the slide to an image.
auto slideImage = slide->GetImage(2.0f, 2.0f);

// Save the image in PNG format.
slideImage->Save(u"slide.png", ImageFormat::Png);
slideImage->Dispose();

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert JPG to Image in C++" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a presentation processing API that can import JPG files into slides and render the result as image files.

Aspose.Slides for C++ can convert JPG content to images and other presentation-related formats.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert JPG to Image Using Aspose.Slides for C++ API" intro="These are the steps to convert JPG to Image in C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for C++**](/slides/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a library reference (import the library) to your C++ project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source JPG file in C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the result as an image file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free Online Converter"
  description="Convert presentations and slides online." >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert JPG to Other Supported Formats" subTitle="You can also convert JPG files and save them to other file formats. See all supported formats below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
