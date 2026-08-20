---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POTM to PDF in Python
url: /python-java/conversion/potm-to-pdf/
keywords: Python POTM conversion, POTM to PDF, PowerPoint to PDF, macro-enabled template to PDF, Aspose.Slides for Python via Java
description: Convert POTM files to PDF documents in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert POTM Files to PDF in Python" h2="Render a macro-enabled PowerPoint template as a PDF document with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert POTM to PDF in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a macro-enabled POTM file and render it as a PDF document. The PDF preserves the visual layout of the slides in a fixed-layout format; VBA macros and interactive behavior are not included. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert POTM to PDF using Python" %}}
Create a `Presentation` from the POTM file, then call `save` with `SaveFormat.Pdf`.

{{% blocks/products/pf/agp/code-block title="Python code for converting POTM to PDF" offSpacer="true" %}}

```python
presentation = Presentation("presentation.potm")
try:
    presentation.save("presentation.pdf", SaveFormat.Pdf)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert POTM to PDF in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to render a POTM file as a PDF document." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source POTM file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Pdf` to create the PDF document.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert POTM to Other Supported Formats" subTitle="You can also convert POTM files to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
