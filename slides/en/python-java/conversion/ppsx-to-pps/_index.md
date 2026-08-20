---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSX to PPS in Python
url: /python-java/conversion/ppsx-to-pps/
keywords: Python PPSX conversion, PPSX to PPS, PowerPoint slide show conversion, PowerPoint 97-2003, Aspose.Slides for Python via Java
description: Convert PPSX slide shows to legacy PPS files in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSX to PPS in Python" h2="Save an Open XML PowerPoint slide show in the PowerPoint 97-2003 Slide Show format." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSX to PPS in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can convert a PowerPoint Slide Show (`.ppsx`) to the PowerPoint 97-2003 Slide Show (`.pps`) format without Microsoft PowerPoint. PPS is a legacy binary format intended to open directly as a slide show in compatible applications.

Load the source file with `Presentation`, then call `save` with `SaveFormat.Pps`. Because PPS is an older format, features that it does not support cannot be represented in the output.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="How to Convert PPSX to PPS in Python" %}}
Load the source PPSX file into a `Presentation`, then save it with `SaveFormat.Pps`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPSX to PPS" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppsx")
try:
    presentation.save("presentation.pps", SaveFormat.Pps)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Steps to Convert PPSX to PPS in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="The conversion loads the Open XML PowerPoint slide show and writes its content in the legacy PPS format." >}}

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
Call `save` with `SaveFormat.Pps` and a `.pps` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
