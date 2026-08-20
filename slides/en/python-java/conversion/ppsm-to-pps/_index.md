---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSM to PPS in Python
url: /python-java/conversion/ppsm-to-pps/
keywords: Python PPSM conversion, PPSM to PPS, PowerPoint slide show conversion, PowerPoint 97-2003 slide show, Aspose.Slides for Python via Java
description: Convert PPSM files to PowerPoint 97-2003 PPS slide shows in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSM to PPS in Python" h2="Save a macro-enabled Open XML slide show in the binary PowerPoint 97-2003 PPS format." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSM to PPS in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can load a macro-enabled PowerPoint slide show (`.ppsm`) and save it as a binary PowerPoint 97-2003 slide show (`.pps`) without Microsoft PowerPoint. The output remains a slide show file and opens directly in slide show mode in compatible applications.

The conversion changes the Open XML package to the legacy binary format while retaining presentation content such as slides, layouts, themes, and supported multimedia. Load the source file with `Presentation`, then call `save` with `SaveFormat.Pps`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="How to Convert PPSM to PPS in Python" %}}
Load the source PPSM file into a `Presentation`, then save it with `SaveFormat.Pps`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPSM to PPS" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppsm")
try:
    presentation.save("presentation.pps", SaveFormat.Pps)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Steps to Convert PPSM to PPS in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="The conversion loads the macro-enabled Open XML slide show and writes its content in the binary PowerPoint 97-2003 PPS format." >}}

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
Call `save` with `SaveFormat.Pps` and a `.pps` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSM to Other Supported Formats" subTitle="You can also convert PPSM presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
