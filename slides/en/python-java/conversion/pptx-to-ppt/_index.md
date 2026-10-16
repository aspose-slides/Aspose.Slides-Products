---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTX to PPT in Python
url: /python-java/conversion/pptx-to-ppt/
keywords: Python PPTX conversion, PPTX to PPT, PowerPoint 97-2003 presentation, legacy PowerPoint conversion, Aspose.Slides for Python via Java
description: Convert PPTX presentations to legacy PowerPoint PPT files in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTX to PPT in Python" h2="Save an Open XML presentation in the legacy PowerPoint 97-2003 format with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTX to PPT using Python" variant="code" %}}

Create a `Presentation` from the PPTX file, then call `save` with `SaveFormat.Ppt`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPTX to PPT" >}}
```python
presentation = Presentation("presentation.pptx")
try:
    presentation.save("presentation.ppt", SaveFormat.Ppt)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTX to PPT in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load an Open XML PowerPoint presentation (PPTX) and save it in the legacy PowerPoint 97-2003 presentation format (PPT). The conversion preserves supported content and layout, but features unavailable in the older format may be simplified. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPTX to PPT in Python" intro="Follow these steps to convert an Open XML PowerPoint presentation to the legacy PPT format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPTX file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Ppt` to create the PPT presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPTX to Other Supported Formats" subTitle="You can also convert PPTX presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
