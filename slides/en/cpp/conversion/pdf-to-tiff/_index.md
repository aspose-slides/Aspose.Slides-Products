---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to TIFF in C++
url: /cpp/conversion/pdf-to-tiff/
keywords: PDF to TIFF, Convert PDF to TIFF, C++ API, C++ Library, PDF, TIFF
description: Convert PDF to TIFF in C++. Use the C++ library API to import PDF files and save them as TIFF files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to TIFF in C++" h2="Convert PDF files to TIFF using Aspose.Slides for C++ without Adobe Acrobat or Microsoft PowerPoint." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to TIFF Using C++" variant="code" %}}

To convert PDF to TIFF, create a `Presentation`, remove the default slide, import the PDF pages, and save the presentation in TIFF format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ code for converting PDF into TIFF" >}}
```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->RemoveAt(0);
presentation->get_Slides()->AddFromPdf(u"input.pdf");

presentation->Save(u"document.tiff", SaveFormat::Tiff);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to TIFF in C++" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a presentation processing API that can import PDF pages into a presentation and save the result as TIFF. Using **Aspose.Slides for C++**, developers can convert PDF files to TIFF with just a few lines of C++ code.

Aspose.Slides for C++ can convert PDF content to TIFF and other presentation-related formats.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PDF to TIFF using Aspose.Slides for C++ API" intro="These are the steps to convert PDF to TIFF in C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for C++**](/slides/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a library reference to your C++ project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Remove the default slide and import the source PDF file into the `Presentation` object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the presentation as a TIFF file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="pdf-to-tiff"
  title="Free Online Converter"
  description="Convert presentations and slides online." >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF files and save them to other file formats. See all supported formats below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
