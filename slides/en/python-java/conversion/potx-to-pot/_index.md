---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POTX to POT in Python
url: /python-java/conversion/potx-to-pot/
keywords: Python POTX conversion, POTX to POT, PowerPoint template conversion, Open XML template to POT, Aspose.Slides for Python via Java
description: Convert POTX files to legacy POT templates in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert POTX Files to POT in Python" h2="Save a PowerPoint Open XML template in the legacy POT format with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTX to POT using Python" variant="code" %}}

Create a `Presentation` from the POTX file, then call `save` with `SaveFormat.Pot`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting POTX to POT" >}}
```python
presentation = Presentation("presentation.potx")
try:
    presentation.save("presentation.pot", SaveFormat.Pot)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTX to POT in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PowerPoint Open XML template (`POTX`) and save it as a legacy PowerPoint 97-2003 template (`POT`). Features that the older binary format does not support may be changed during conversion. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert POTX to POT in Python" intro="Follow these steps to save a POTX file as a legacy POT template." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source POTX file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Pot` to create the POT template.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert POTX to Other Supported Formats" subTitle="You can also convert POTX presentation templates to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
