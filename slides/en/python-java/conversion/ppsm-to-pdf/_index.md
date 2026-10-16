---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSM to PDF in Python
url: /python-java/conversion/ppsm-to-pdf/
keywords: Python PPSM conversion, PPSM to PDF, PowerPoint to PDF, macro-enabled slide show to PDF, Aspose.Slides for Python via Java
description: Convert PPSM files to PDF documents in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPSM Files to PDF in Python" h2="Export a macro-enabled PowerPoint slide show as a portable PDF document with consistent slide rendering." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="How to Convert PPSM to PDF in Python" variant="code" %}}

Load the source PPSM file into a `Presentation`, then save it with `SaveFormat.Pdf`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPSM to PDF" >}}
```python
presentation = Presentation("presentation.ppsm")
try:
    presentation.save("presentation.pdf", SaveFormat.Pdf)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSM to PDF in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can convert a macro-enabled PowerPoint slide show (`.ppsm`) to a PDF document without Microsoft PowerPoint. PDF output is suitable for sharing, printing, and archiving because it preserves the rendered appearance of the slides across devices. Macros and interactive behavior are not included in the PDF.

For a straightforward conversion, load the source file with `Presentation` and call `save` with `SaveFormat.Pdf`. PDF export options can be supplied when the output requires settings such as image quality, compliance level, or selected slide ranges.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps to Convert PPSM to PDF in Python" intro="The conversion loads the macro-enabled PowerPoint slide show and renders its slides into a PDF document." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Python via Java](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure JPype and make the Aspose.Slides package available to your Python project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` from the source `.ppsm` file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Pdf` and a `.pdf` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPSM to Other Supported Formats" subTitle="You can also convert PPSM presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
