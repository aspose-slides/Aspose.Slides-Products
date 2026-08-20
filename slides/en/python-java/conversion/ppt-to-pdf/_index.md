---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPT to PDF in Python
url: /python-java/conversion/ppt-to-pdf/
keywords: Python PPT conversion, PPT to PDF, PowerPoint to PDF, presentation document conversion, Aspose.Slides for Python via Java
description: Convert PPT files to PDF documents in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPT to PDF in Python" h2="Export a legacy PowerPoint presentation as a portable PDF document with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPT to PDF in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can convert a legacy PowerPoint presentation (`.ppt`) to a PDF document without Microsoft PowerPoint. PDF output is convenient for sharing, printing, and archiving because it preserves the rendered appearance of the slides across devices.

For a standard conversion, load the PPT file with `Presentation` and call `save` with `SaveFormat.Pdf`. You can also supply `PdfOptions` when the output requires settings such as compliance, image quality, or hidden-slide handling.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPT to PDF using Python" %}}
Create a `Presentation` from the source PPT file, then call `save` with `SaveFormat.Pdf`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPT to PDF" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppt")
try:
    presentation.save("presentation.pdf", SaveFormat.Pdf)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPT to PDF in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to export a PowerPoint PPT presentation as a PDF document." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](/slides/python-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source PPT file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Pdf` and a `.pdf` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPT to Other Supported Formats" subTitle="You can also convert PPT presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
