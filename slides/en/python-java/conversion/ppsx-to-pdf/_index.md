---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSX to PDF in Python
url: /python-java/conversion/ppsx-to-pdf/
keywords: Python PPSX conversion, PPSX to PDF, PowerPoint to PDF, slide show to PDF, Aspose.Slides for Python via Java
description: Convert PPSX files to PDF documents in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPSX Files to PDF in Python" h2="Export a PowerPoint slide show as a portable PDF document with consistent slide rendering." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="How to Convert PPSX to PDF in Python" variant="code" %}}

Load the source PPSX file into a `Presentation`, then save it with `SaveFormat.Pdf`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPSX to PDF" >}}
```python
presentation = Presentation("presentation.ppsx")
try:
    presentation.save("presentation.pdf", SaveFormat.Pdf)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSX to PDF in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can convert a PowerPoint Slide Show (`.ppsx`) to a PDF document without Microsoft PowerPoint. PDF output is convenient for sharing, printing, and archiving because each slide is rendered as a fixed-layout page.

For a straightforward conversion, load the PPSX file with `Presentation` and call `save` with `SaveFormat.Pdf`. Animations, transitions, and other interactive slide show behavior do not remain interactive in the PDF.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps to Convert PPSX to PDF in Python" intro="The conversion loads the PowerPoint slide show and renders its slides as pages in a PDF document." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Python via Java](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure JPype and make the Aspose.Slides package available to your Python project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` from the source `.ppsx` file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Pdf` and a `.pdf` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
