---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPT to PPTM in Python
url: /python-java/conversion/ppt-to-pptm/
keywords: Python PPT conversion, PPT to PPTM, PowerPoint to PPTM, macro-enabled presentation format, Aspose.Slides for Python via Java
description: Convert PPT files to PPTM format in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPT to PPTM in Python" h2="Save a legacy PowerPoint presentation in the macro-enabled Open XML PPTM format with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPT to PPTM in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a legacy PowerPoint presentation (`.ppt`) and save it in the macro-enabled Open XML PPTM format without Microsoft PowerPoint. PPTM files can store VBA macros; converting a source file does not create new macros.

Load the source file with `Presentation`, then call `save` with `SaveFormat.Pptm`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPT to PPTM using Python" %}}
Create a `Presentation` from the source PPT file, then call `save` with `SaveFormat.Pptm`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPT to PPTM" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppt")
try:
    presentation.save("presentation.pptm", SaveFormat.Pptm)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPT to PPTM in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to save a PowerPoint PPT presentation in the macro-enabled Open XML PPTM format." >}}

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
Call `save` with `SaveFormat.Pptm` and a `.pptm` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPT to Other Supported Formats" subTitle="You can also convert PPT presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
