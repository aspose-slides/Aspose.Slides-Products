---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPS to POT in Python
url: /python-java/conversion/pps-to-pot/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, PPS to POT conversion, Python presentation library
description: Convert PPS files to the PowerPoint 97-2003 POT format in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPS to POT in Python" h2="Save a PowerPoint Show in the binary PowerPoint 97-2003 POT format." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPS to POT in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can load a PowerPoint Show (`.pps`) file and save it in the binary POT format used by PowerPoint 97-2003. The conversion does not require Microsoft PowerPoint.

The library retains the presentation content and layout while changing the file format. Load the source file with `Presentation`, then call `save` with `SaveFormat.Pot`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="How to Convert PPS to POT in Python" %}}
Load the source PPS file into a `Presentation`, then save it with `SaveFormat.Pot`.

{{% blocks/products/pf/agp/code-block title="Python tutorial for converting PPS into POT" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pps")
try:
    presentation.save("presentation.pot", SaveFormat.Pot)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Steps to Convert PPS to POT in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="The conversion loads the PowerPoint Show and writes its content in the PowerPoint 97-2003 POT format." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [Aspose.Slides for Python via Java](/slides/python-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure JPype and make the Aspose.Slides package available to your Python project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` from the source `.pps` file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Pot` and a `.pot` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPS to Other Supported Formats" subTitle="You can also convert PPS files to the formats listed below." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
