---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTM to PDF in Python
url: /python-java/conversion/pptm-to-pdf/
keywords: Python PPTM conversion, PPTM to PDF, PowerPoint to PDF, presentation document conversion, Aspose.Slides for Python via Java
description: Convert PPTM files to PDF documents in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTM to PDF in Python" h2="Export a macro-enabled PowerPoint presentation as a portable PDF document with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPTM to PDF in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can convert a macro-enabled PowerPoint presentation (`.pptm`) to a PDF document without Microsoft PowerPoint. PDF output preserves the rendered appearance of supported slide content for consistent sharing, printing, and archiving. Because PDF is a fixed-layout document format, the output does not contain the source presentation's VBA project or interactive slide behavior.

For a standard conversion, load the PPTM file with `Presentation` and call `save` with `SaveFormat.Pdf`. You can also use `PdfOptions` when you need to control settings such as compliance, image quality, or hidden-slide handling.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPTM to PDF using Python" %}}
Create a `Presentation` from the source PPTM file, then call `save` with `SaveFormat.Pdf`.

{{% blocks/products/pf/agp/code-block title="Python tutorial for converting PPTM into PDF" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pptm")
try:
    presentation.save("presentation.pdf", SaveFormat.Pdf)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPTM to PDF in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to export a PowerPoint PPTM presentation as a PDF document." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source PPTM file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Pdf` and a `.pdf` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPTM to Other Supported Formats" subTitle="You can also convert PPTM presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
