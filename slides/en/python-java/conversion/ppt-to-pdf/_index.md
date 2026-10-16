---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPT to PDF in Python
url: /python-java/conversion/ppt-to-pdf/
keywords: Python PPT conversion, PPT to PDF, PowerPoint to PDF, presentation document conversion, Aspose.Slides for Python via Java
description: Convert PPT files to PDF documents in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPT to PDF in Python" h2="Export a legacy PowerPoint presentation as a portable PDF document with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPT to PDF using Python" variant="code" %}}

Create a `Presentation` from the source PPT file, then call `save` with `SaveFormat.Pdf`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPT to PDF" >}}
```python
presentation = Presentation("presentation.ppt")
try:
    presentation.save("presentation.pdf", SaveFormat.Pdf)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPT to PDF in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can convert a legacy PowerPoint presentation (`.ppt`) to a PDF document without Microsoft PowerPoint. PDF output is convenient for sharing, printing, and archiving because it preserves the rendered appearance of the slides across devices.

For a standard conversion, load the PPT file with `Presentation` and call `save` with `SaveFormat.Pdf`. You can also supply `PdfOptions` when the output requires settings such as compliance, image quality, or hidden-slide handling.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPT to PDF in Python" intro="Follow these steps to export a PowerPoint PPT presentation as a PDF document." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPT file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Pdf` and a `.pdf` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPT to Other Supported Formats" subTitle="You can also convert PPT presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
