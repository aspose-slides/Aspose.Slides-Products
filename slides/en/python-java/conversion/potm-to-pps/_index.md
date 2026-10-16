---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POTM to PPS in Python
url: /python-java/conversion/potm-to-pps/
keywords: Python POTM conversion, POTM to PPS, PowerPoint slide show conversion, macro-enabled POTM, Aspose.Slides for Python via Java
description: Convert POTM files to PPS slide shows in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert POTM Files to PPS in Python" h2="Save a macro-enabled POTM file as a legacy PowerPoint slide show with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTM to PPS using Python" variant="code" %}}

Create a `Presentation` from the POTM file, then call `save` with `SaveFormat.Pps`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting POTM to PPS" >}}
```python
presentation = Presentation("presentation.potm")
try:
    presentation.save("presentation.pps", SaveFormat.Pps)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTM to PPS in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a macro-enabled POTM file and save it as a PPS slide show. PPS is the legacy binary PowerPoint Show format and opens directly in Slide Show view. To preserve VBA macros, save the file as PPSM instead. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert POTM to PPS in Python" intro="Follow these steps to save a POTM file as a PPS slide show." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source POTM file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Pps` to create the PPS slide show.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert POTM to Other Supported Formats" subTitle="You can also convert POTM files to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
