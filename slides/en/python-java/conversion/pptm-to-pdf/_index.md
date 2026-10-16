---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTM to PDF in Python
url: /python-java/conversion/pptm-to-pdf/
keywords: Python PPTM conversion, PPTM to PDF, PowerPoint to PDF, presentation document conversion, Aspose.Slides for Python via Java
description: Convert PPTM files to PDF documents in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTM to PDF in Python" h2="Export a macro-enabled PowerPoint presentation as a portable PDF document with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to PDF using Python" variant="code" %}}

Create a `Presentation` from the source PPTM file, then call `save` with `SaveFormat.Pdf`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python tutorial for converting PPTM into PDF" >}}
```python
presentation = Presentation("presentation.pptm")
try:
    presentation.save("presentation.pdf", SaveFormat.Pdf)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to PDF in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can convert a macro-enabled PowerPoint presentation (`.pptm`) to a PDF document without Microsoft PowerPoint. PDF output preserves the rendered appearance of supported slide content for consistent sharing, printing, and archiving. Because PDF is a fixed-layout document format, the output does not contain the source presentation's VBA project or interactive slide behavior.

For a standard conversion, load the PPTM file with `Presentation` and call `save` with `SaveFormat.Pdf`. You can also use `PdfOptions` when you need to control settings such as compliance, image quality, or hidden-slide handling.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPTM to PDF in Python" intro="Follow these steps to export a PowerPoint PPTM presentation as a PDF document." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPTM file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Pdf` and a `.pdf` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPTM to Other Supported Formats" subTitle="You can also convert PPTM presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
