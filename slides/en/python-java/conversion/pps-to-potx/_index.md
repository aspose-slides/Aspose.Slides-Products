---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPS to POTX in Python
url: /python-java/conversion/pps-to-potx/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, PPS to POTX conversion, Python presentation library
description: Convert PPS files to POTX files in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPS to POTX in Python" h2="Save a PowerPoint Show in the macro-free Open XML POTX format." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="How to Convert PPS to POTX in Python" variant="code" %}}

Load the source PPS file into a `Presentation`, then save it with `SaveFormat.Potx`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python tutorial for converting PPS into POTX" >}}
```python
presentation = Presentation("presentation.pps")
try:
    presentation.save("presentation.potx", SaveFormat.Potx)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPS to POTX in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can load a PowerPoint Show (`.pps`) file and save it in the macro-free POTX format without Microsoft PowerPoint. POTX uses the Open XML file structure and cannot store VBA macros.

The library retains the presentation content and layout while changing the file format. Load the source file with `Presentation`, then call `save` with `SaveFormat.Potx`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps to Convert PPS to POTX in Python" intro="The conversion loads the PowerPoint Show and writes its content in the macro-free POTX format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Python via Java](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure JPype and make the Aspose.Slides package available to your Python project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` from the source `.pps` file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Potx` and a `.potx` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPS to Other Supported Formats" subTitle="You can also convert PPS files to the formats listed below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
