---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSM to PDF in Python
url: /python-java/conversion/ppsm-to-pdf/
keywords: Python PPSM conversion, PPSM to PDF, PowerPoint to PDF, macro-enabled slide show to PDF, Aspose.Slides for Python via Java
description: Convert PPSM files to PDF documents in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSM Files to PDF in Python" h2="Export a macro-enabled PowerPoint slide show as a portable PDF document with consistent slide rendering." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSM to PDF in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can convert a macro-enabled PowerPoint slide show (`.ppsm`) to a PDF document without Microsoft PowerPoint. PDF output is suitable for sharing, printing, and archiving because it preserves the rendered appearance of the slides across devices. Macros and interactive behavior are not included in the PDF.

For a straightforward conversion, load the source file with `Presentation` and call `save` with `SaveFormat.Pdf`. PDF export options can be supplied when the output requires settings such as image quality, compliance level, or selected slide ranges.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="How to Convert PPSM to PDF in Python" %}}
Load the source PPSM file into a `Presentation`, then save it with `SaveFormat.Pdf`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPSM to PDF" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppsm")
try:
    presentation.save("presentation.pdf", SaveFormat.Pdf)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Steps to Convert PPSM to PDF in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="The conversion loads the macro-enabled PowerPoint slide show and renders its slides into a PDF document." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [Aspose.Slides for Python via Java](/slides/python-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure JPype and make the Aspose.Slides package available to your Python project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` from the source `.ppsm` file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Pdf` and a `.pdf` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSM to Other Supported Formats" subTitle="You can also convert PPSM presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
