---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSM to POT in Python
url: /python-java/conversion/ppsm-to-pot/
keywords: Python PPSM conversion, PPSM to POT, PowerPoint slide show to template, PowerPoint 97-2003 template, Aspose.Slides for Python via Java
description: Convert PPSM slide shows to PowerPoint 97-2003 POT files in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPSM to POT in Python" h2="Save a macro-enabled PowerPoint slide show in the binary PowerPoint 97-2003 POT format." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="How to Convert PPSM to POT in Python" variant="code" %}}

Load the source PPSM file into a `Presentation`, then save it with `SaveFormat.Pot`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPSM to POT" >}}
```python
presentation = Presentation("presentation.ppsm")
try:
    presentation.save("presentation.pot", SaveFormat.Pot)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSM to POT in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can load a macro-enabled PowerPoint slide show (`.ppsm`) and save it as a binary PowerPoint 97-2003 POT file without Microsoft PowerPoint. POT is a legacy presentation format that can contain VBA projects.

The conversion changes the file format while retaining presentation content such as slides, layouts, themes, and supported multimedia. Load the source file with `Presentation`, then call `save` with `SaveFormat.Pot`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps to Convert PPSM to POT in Python" intro="The conversion loads the macro-enabled PowerPoint slide show and writes its content in the binary PowerPoint 97-2003 POT format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Python via Java](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure JPype and make the Aspose.Slides package available to your Python project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` from the source `.ppsm` file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Pot` and a `.pot` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPSM to Other Supported Formats" subTitle="You can also convert PPSM presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
