---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSX to POTX in Python
url: /python-java/conversion/ppsx-to-potx/
keywords: Python PPSX conversion, PPSX to POTX, PowerPoint template conversion, Open XML PowerPoint template, Aspose.Slides for Python via Java
description: Convert PPSX slide shows to POTX presentation template files in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSX to POTX in Python" h2="Save a PowerPoint slide show as a reusable Open XML presentation template." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSX to POTX in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can load a PowerPoint Slide Show (`.ppsx`) and save it as a PowerPoint Open XML Presentation Template (`.potx`) without Microsoft PowerPoint. POTX files are designed to provide reusable themes, layouts, and formatting and do not store VBA macros.

The conversion retains presentation content such as slides, layouts, themes, and supported multimedia. Load the source file with `Presentation`, then call `save` with `SaveFormat.Potx`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="How to Convert PPSX to POTX in Python" %}}
Load the source PPSX file into a `Presentation`, then save it with `SaveFormat.Potx`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPSX to POTX" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppsx")
try:
    presentation.save("presentation.potx", SaveFormat.Potx)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Steps to Convert PPSX to POTX in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="The conversion loads the PowerPoint slide show and writes its content in the Open XML POTX template format." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [Aspose.Slides for Python via Java](/slides/python-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure JPype and make the Aspose.Slides package available to your Python project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` from the source `.ppsx` file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Potx` and a `.potx` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
