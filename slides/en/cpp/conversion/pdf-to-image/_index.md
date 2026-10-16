---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to Image in C++
url: /cpp/conversion/pdf-to-image/
keywords: PDF to Image, Convert PDF to Image, C++ API, C++ Library, PDF, Image
description: Convert PDF to images in C++. Use the C++ library API to import PDF files and render slides as images.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to Image in C++" h2="Convert PDF files to images using Aspose.Slides for C++ without Adobe Acrobat or Microsoft PowerPoint." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to Image Using C++" variant="code" %}}

To convert PDF to images, create a `Presentation`, remove the default slide, import the PDF pages, and render each slide as an image.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ code for converting PDF into images" >}}
```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->RemoveAt(0);
presentation->get_Slides()->AddFromPdf(u"input.pdf");

auto slideCount = presentation->get_Slides()->get_Count();
for (int slideIndex = 0; slideIndex < slideCount; slideIndex++)
{
    auto currentSlide = presentation->get_Slide(slideIndex);
    if (currentSlide->get_Hidden())
    {
        continue;
    }

    auto slideImage = currentSlide->GetImage(2.0f, 2.0f);
    auto outputFilePath = String(u"slide_") + slideIndex + u".png";
    slideImage->Save(outputFilePath, ImageFormat::Png);
    slideImage->Dispose();
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to Image in C++" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a presentation processing API that can import PDF pages into slides and render those slides as images. Using **Aspose.Slides for C++**, developers can convert PDF files to images with just a few lines of C++ code.

Aspose.Slides for C++ can convert PDF content to images and other presentation-related formats.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PDF to Image using Aspose.Slides for C++ API" intro="These are the steps to convert PDF to Image in C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for C++**](/slides/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a library reference to your C++ project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Remove the default slide and import the source PDF file into the `Presentation` object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render each slide and save it as an image file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="pdf-to-image"
  title="Free Online Converter"
  description="Convert presentations and slides online." >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF files and save them to other file formats. See all supported formats below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
