---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPS to PPSM in Python
url: /python-java/conversion/pps-to-ppsm/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, PPS to PPSM conversion, Python presentation library
description: Convert PPS files to macro-enabled PPSM slide shows in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPS to PPSM in Python" h2="Save a binary PowerPoint Show in the macro-enabled Open XML PPSM format." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="How to Convert PPS to PPSM in Python" variant="code" %}}

Load the source PPS file into a `Presentation`, then save it with `SaveFormat.Ppsm`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python tutorial for converting PPS into PPSM" >}}
```python
presentation = Presentation("presentation.pps")
try:
    presentation.save("presentation.ppsm", SaveFormat.Ppsm)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPS to PPSM in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can convert a binary PowerPoint Show (`.pps`) file to the macro-enabled Open XML PPSM format without Microsoft PowerPoint. PPSM remains a slide show format and can store VBA macros.

The library retains the presentation content and layout while changing the file format. Load the source file with `Presentation`, then call `save` with `SaveFormat.Ppsm`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps to Convert PPS to PPSM in Python" intro="The conversion loads the binary PowerPoint Show and writes its content in the macro-enabled PPSM format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Python via Java](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure JPype and make the Aspose.Slides package available to your Python project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` from the source `.pps` file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Ppsm` and a `.ppsm` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPS to Other Supported Formats" subTitle="You can also convert PPS files to the formats listed below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
