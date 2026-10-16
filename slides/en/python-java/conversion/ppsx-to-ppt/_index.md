---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSX to PPT in Python
url: /python-java/conversion/ppsx-to-ppt/
keywords: Python PPSX conversion, PPSX to PPT, PowerPoint presentation conversion, PowerPoint 97-2003, Aspose.Slides for Python via Java
description: Convert PPSX slide shows to legacy PPT presentations in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPSX to PPT in Python" h2="Save an Open XML PowerPoint slide show in the PowerPoint 97-2003 Presentation format." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="How to Convert PPSX to PPT in Python" variant="code" %}}

Load the source PPSX file into a `Presentation`, then save it with `SaveFormat.Ppt`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPSX to PPT" >}}
```python
presentation = Presentation("presentation.ppsx")
try:
    presentation.save("presentation.ppt", SaveFormat.Ppt)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSX to PPT in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can convert a PowerPoint Slide Show (`.ppsx`) to the PowerPoint 97-2003 Presentation (`.ppt`) format without Microsoft PowerPoint. The resulting PPT file opens as an editable presentation rather than directly as a slide show.

Load the source file with `Presentation`, then call `save` with `SaveFormat.Ppt`. Because PPT is an older format, features that it does not support cannot be represented in the output.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps to Convert PPSX to PPT in Python" intro="The conversion loads the Open XML PowerPoint slide show and writes its content in the legacy PPT presentation format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Python via Java](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure JPype and make the Aspose.Slides package available to your Python project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` from the source `.ppsx` file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Ppt` and a `.ppt` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
