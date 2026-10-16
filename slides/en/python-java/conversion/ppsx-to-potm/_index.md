---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSX to POTM in Python
url: /python-java/conversion/ppsx-to-potm/
keywords: Python PPSX conversion, PPSX to POTM, PowerPoint template conversion, macro-enabled PowerPoint template, Aspose.Slides for Python via Java
description: Convert PPSX slide shows to macro-enabled POTM template files in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPSX to POTM in Python" h2="Save a PowerPoint slide show as a macro-enabled Open XML presentation template." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="How to Convert PPSX to POTM in Python" variant="code" %}}

Load the source PPSX file into a `Presentation`, then save it with `SaveFormat.Potm`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPSX to POTM" >}}
```python
presentation = Presentation("presentation.ppsx")
try:
    presentation.save("presentation.potm", SaveFormat.Potm)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSX to POTM in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can load a PowerPoint Slide Show (`.ppsx`) and save it as a macro-enabled PowerPoint Template (`.potm`) without Microsoft PowerPoint. POTM is an Open XML template format that can store VBA projects; converting a macro-free PPSX file does not add a VBA project to the output.

The conversion retains presentation content such as slides, layouts, themes, and supported multimedia. Load the source file with `Presentation`, then call `save` with `SaveFormat.Potm`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps to Convert PPSX to POTM in Python" intro="The conversion loads the PowerPoint slide show and writes its content in the macro-enabled Open XML POTM template format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Python via Java](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure JPype and make the Aspose.Slides package available to your Python project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` from the source `.ppsx` file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Potm` and a `.potm` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
