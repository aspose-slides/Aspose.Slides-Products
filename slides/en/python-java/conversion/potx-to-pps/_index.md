---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POTX to PPS in Python
url: /python-java/conversion/potx-to-pps/
keywords: Python POTX conversion, POTX to PPS, PowerPoint slide show conversion, Open XML template to PPS, Aspose.Slides for Python via Java
description: Convert POTX files to legacy PPS slide shows in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert POTX Files to PPS in Python" h2="Save a PowerPoint Open XML template as a legacy PowerPoint slide show with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTX to PPS using Python" variant="code" %}}

Create a `Presentation` from the POTX file, then call `save` with `SaveFormat.Pps`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting POTX to PPS" >}}
```python
presentation = Presentation("presentation.potx")
try:
    presentation.save("presentation.pps", SaveFormat.Pps)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTX to PPS in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PowerPoint Open XML template (`POTX`) and save it as a legacy PowerPoint Show (`PPS`). A `PPS` file opens directly in Slide Show view in compatible applications. Microsoft PowerPoint is not required for the conversion.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert POTX to PPS in Python" intro="Follow these steps to save a POTX file as a legacy PPS slide show." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source POTX file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Pps` to create the PPS slide show.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert POTX to Other Supported Formats" subTitle="You can also convert POTX presentation templates to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
