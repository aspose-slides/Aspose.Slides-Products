---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPT to POTM in Python
url: /python-java/conversion/ppt-to-potm/
keywords: Python PPT conversion, PPT to POTM, PowerPoint to POTM, macro-enabled presentation format, Aspose.Slides for Python via Java
description: Convert PPT files to POTM format in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPT to POTM in Python" h2="Save a legacy PowerPoint presentation in the macro-enabled Open XML POTM format with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPT to POTM using Python" variant="code" %}}

Create a `Presentation` from the source PPT file, then call `save` with `SaveFormat.Potm`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPT to POTM" >}}
```python
presentation = Presentation("presentation.ppt")
try:
    presentation.save("presentation.potm", SaveFormat.Potm)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPT to POTM in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a legacy PowerPoint presentation (`.ppt`) and save it in the macro-enabled Open XML POTM format without Microsoft PowerPoint. POTM files can store VBA macros; converting a source file does not create new macros.

Load the source file with `Presentation`, then call `save` with `SaveFormat.Potm`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPT to POTM in Python" intro="Follow these steps to save a PowerPoint PPT presentation in the macro-enabled Open XML POTM format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPT file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Potm` and a `.potm` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPT to Other Supported Formats" subTitle="You can also convert PPT presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
