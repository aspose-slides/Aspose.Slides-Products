---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPT to PPSM in Python
url: /python-java/conversion/ppt-to-ppsm/
keywords: Python PPT conversion, PPT to PPSM, PowerPoint to PPSM, macro-enabled slide show, Aspose.Slides for Python via Java
description: Convert PPT files to PPSM format in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPT to PPSM in Python" h2="Save a legacy PowerPoint presentation in the macro-enabled Open XML PPSM format with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPT to PPSM in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a legacy PowerPoint presentation (`.ppt`) and save it in the macro-enabled Open XML PPSM format without Microsoft PowerPoint. PPSM files can store VBA macros; converting a source file does not create new macros.

Load the source file with `Presentation`, then call `save` with `SaveFormat.Ppsm`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPT to PPSM using Python" %}}
Create a `Presentation` from the source PPT file, then call `save` with `SaveFormat.Ppsm`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPT to PPSM" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppt")
try:
    presentation.save("presentation.ppsm", SaveFormat.Ppsm)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPT to PPSM in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to save a PowerPoint PPT presentation in the macro-enabled Open XML PPSM format." >}}

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
Call `save` with `SaveFormat.Ppsm` and a `.ppsm` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPT to Other Supported Formats" subTitle="You can also convert PPT presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
