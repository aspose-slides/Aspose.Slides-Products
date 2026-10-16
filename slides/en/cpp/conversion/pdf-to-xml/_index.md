---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to XML in C++
url: /cpp/conversion/pdf-to-xml/
keywords: PDF to XML, Convert PDF to XML, PowerPoint XML Presentation, C++ API, C++ Library, PDF, XML
description: Import PDF pages into slides and save the result as a PowerPoint XML Presentation in C++ using Aspose.Slides for C++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to XML in C++" h2="Import PDF pages into slides and save the result as a PowerPoint XML Presentation." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to XML Using C++" variant="code" %}}

To convert PDF to PowerPoint XML, create a `Presentation`, remove the default slide, import the PDF pages, and save the presentation with `SaveFormat::Xml`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ code for converting PDF into a PowerPoint XML Presentation" >}}
```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->RemoveAt(0);
presentation->get_Slides()->AddFromPdf(u"input.pdf");

presentation->Save(u"document.xml", SaveFormat::Xml);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to XML in C++" %}}

[**Aspose.Slides for C++**](/slides/cpp/) is a presentation processing API that can import PDF pages into slides and save the resulting presentation in PowerPoint XML Presentation format.

The generated XML represents the imported presentation; it is not a generic XML representation of the source PDF. Aspose.Slides for C++ can also export the imported content to PowerPoint, PDF, images, and other supported formats.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PDF to PowerPoint XML using Aspose.Slides for C++ API" intro="These are the steps to import PDF pages and save them as a PowerPoint XML Presentation in C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for C++**](/slides/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a library reference to your C++ project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Remove the default slide and import the source PDF file into the `Presentation` object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the presentation with `SaveFormat::Xml` to create a PowerPoint XML Presentation file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="pdf-to-xml"
  title="Free Online Converter"
  description="Convert presentations and slides online." >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF files and save them to other file formats. See all supported formats below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
