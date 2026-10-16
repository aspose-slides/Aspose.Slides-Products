---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POT to POTX in Python
url: /python-java/conversion/pot-to-potx/
keywords: Python POT conversion, POT to POTX, PowerPoint to POTX, PowerPoint presentation template, Aspose.Slides for Python via Java
description: Convert POT files to POTX presentation templates in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert POT Files to POTX in Python" h2="Save a binary PowerPoint template as an Open XML template with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POT to POTX using Python" variant="code" %}}

Create a `Presentation` from the POT file, then call `save` with `SaveFormat.Potx`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting POT to POTX" >}}
```python
presentation = Presentation("presentation.pot")
try:
    presentation.save("presentation.potx", SaveFormat.Potx)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POT to POTX in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a binary PowerPoint 97–2003 template (POT) and save it as an Open XML PowerPoint template (POTX). POTX is a macro-free format, so use POTM instead when the output must support VBA macros. Microsoft PowerPoint is not required for the conversion.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert POT to POTX in Python" intro="Follow these steps to convert a binary PowerPoint template to the POTX format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source POT file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Potx` to create the POTX file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert POT to Other Supported Formats" subTitle="You can also convert POT files to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
