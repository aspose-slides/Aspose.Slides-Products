---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTX to PDF in Python
url: /python-java/conversion/pptx-to-pdf/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, PPTX to PDF conversion, Python presentation library
description: Convert PPTX presentations to PDF documents in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTX Presentations to PDF in Python" h2="Export a PowerPoint presentation as a fixed-layout PDF document with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTX to PDF using Python" variant="code" %}}

Create a `Presentation` from the PPTX file and call `save` with `SaveFormat.Pdf` to generate the PDF document.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPTX to PDF" >}}
```python
presentation = Presentation("presentation.pptx")
try:
    presentation.save("presentation.pdf", SaveFormat.Pdf)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTX to PDF in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PPTX presentation and export it as a PDF document. The PDF output retains the presentation's visual layout in a format suitable for sharing, printing, and archiving. The conversion does not require Microsoft PowerPoint.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPTX to PDF in Python" intro="Follow these steps to export a PPTX presentation as a PDF document." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPTX file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Pdf` to write the PDF document.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPTX to Other Supported Formats" subTitle="You can also convert PPTX presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
