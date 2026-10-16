---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSM to POTM in Python
url: /python-java/conversion/ppsm-to-potm/
keywords: Python PPSM conversion, PPSM to POTM, macro-enabled PowerPoint file conversion, PowerPoint Open XML, Aspose.Slides for Python via Java
description: Convert PPSM slide shows to macro-enabled POTM files in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPSM to POTM in Python" h2="Save a macro-enabled PowerPoint slide show in the macro-enabled Open XML POTM format." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="How to Convert PPSM to POTM in Python" variant="code" %}}

Load the source PPSM file into a `Presentation`, then save it with `SaveFormat.Potm`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPSM to POTM" >}}
```python
presentation = Presentation("presentation.ppsm")
try:
    presentation.save("presentation.potm", SaveFormat.Potm)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSM to POTM in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can load a macro-enabled PowerPoint slide show (`.ppsm`) and save it in the macro-enabled Open XML POTM format without Microsoft PowerPoint. Both formats can store VBA projects, while POTM identifies the output as a PowerPoint template file.

The conversion retains presentation content such as slides, layouts, themes, and supported multimedia. Load the source file with `Presentation`, then call `save` with `SaveFormat.Potm`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps to Convert PPSM to POTM in Python" intro="The conversion loads the macro-enabled PowerPoint slide show and writes its content in the macro-enabled Open XML POTM format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Python via Java](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure JPype and make the Aspose.Slides package available to your Python project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` from the source `.ppsm` file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Potm` and a `.potm` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPSM to Other Supported Formats" subTitle="You can also convert PPSM presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
