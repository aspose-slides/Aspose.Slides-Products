---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert Image to PDF in C++
url: /cpp/conversion/image-to-pdf/
keywords: Image to PDF, Convert Image to PDF, C++ API, C++ Library, Image, PDF
description: Convert image to PDF in C++. Use the C++ library API to convert image files to PDF documents.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert Image to PDF in C++" h2="Convert image files to PDF documents using Aspose.Slides for C++ without Microsoft PowerPoint." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert Image to PDF Using C++" variant="code" %}}

To convert an image to PDF, create a new Presentation, add the image to its image collection, place it on a slide with `AddPictureFrame`, and save the presentation as a PDF document.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ code for converting Image into PDF" >}}
```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

auto imageData = File::ReadAllBytes(u"image.png");
auto presentationImage = presentation->get_Images()->AddImage(imageData);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, presentationImage);

presentation->Save(u"presentation.pdf", SaveFormat::Pdf);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert Image to PDF in C++" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a presentation processing API that can import images into slides and save the result as a PDF document.

Aspose.Slides for C++ can convert image content to PDF documents and other presentation-related formats.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert Image to PDF Using Aspose.Slides for C++ API" intro="These are the steps to convert Image to PDF in C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for C++**](/slides/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a library reference (import the library) to your C++ project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source image file in C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the result as a PDF file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert Image to Other Supported Formats" subTitle="You can also convert images and save them to other file formats. See all supported formats below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
