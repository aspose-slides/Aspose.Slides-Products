---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTM to POTM in Python
url: /python-java/conversion/pptm-to-potm/
keywords: Python PPTM conversion, PPTM to POTM, macro-enabled PowerPoint template, presentation format conversion, Aspose.Slides for Python via Java
description: Convert PPTM files to POTM format in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTM to POTM in Python" h2="Save a macro-enabled PowerPoint presentation as a macro-enabled PowerPoint template with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPTM to POTM in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a macro-enabled PowerPoint presentation (`.pptm`) and save it as a macro-enabled PowerPoint template (`.potm`) without Microsoft PowerPoint. The conversion retains supported slide content, layouts, and formatting in the target Open XML format. Because POTM is macro-enabled, supported VBA project data can remain in the output.

Load the source file with `Presentation`, then call `save` with `SaveFormat.Potm`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPTM to POTM using Python" %}}
Create a `Presentation` from the source PPTM file, then call `save` with `SaveFormat.Potm`.

{{% blocks/products/pf/agp/code-block title="Python tutorial for converting PPTM into POTM" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pptm")
try:
    presentation.save("presentation.potm", SaveFormat.Potm)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPTM to POTM in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to save a PowerPoint PPTM presentation as a macro-enabled PowerPoint template." >}}

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
Call `save` with `SaveFormat.Potm` and a `.potm` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPTM to Other Supported Formats" subTitle="You can also convert PPTM presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
