---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POTX to POTM in Python
url: /python-java/conversion/potx-to-potm/
keywords: Python POTX conversion, POTX to POTM, PowerPoint template conversion, macro-enabled template, Aspose.Slides for Python via Java
description: Convert POTX files to macro-enabled POTM templates in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert POTX Files to POTM in Python" h2="Save a PowerPoint Open XML template in the macro-enabled POTM format with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTX to POTM using Python" variant="code" %}}

Create a `Presentation` from the POTX file, then call `save` with `SaveFormat.Potm`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting POTX to POTM" >}}
```python
presentation = Presentation("presentation.potx")
try:
    presentation.save("presentation.potm", SaveFormat.Potm)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTX to POTM in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PowerPoint Open XML template (`POTX`) and save it in the macro-enabled template format (`POTM`). The conversion changes the file format but does not add VBA macros to the source content. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert POTX to POTM in Python" intro="Follow these steps to save a POTX file as a macro-enabled POTM template." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source POTX file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Potm` to create the POTM template.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert POTX to Other Supported Formats" subTitle="You can also convert POTX presentation templates to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
