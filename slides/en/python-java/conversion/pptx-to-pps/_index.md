---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTX to PPS in Python
url: /python-java/conversion/pptx-to-pps/
keywords: Python PPTX conversion, PPTX to PPS, PowerPoint slide show, presentation conversion, Aspose.Slides for Python via Java
description: Convert PPTX presentations to PPS slide shows in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTX Presentations to PPS in Python" h2="Create a binary PowerPoint slide show from a PPTX file with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTX to PPS using Python" variant="code" %}}

Create a `Presentation` from the PPTX file and call `save` with `SaveFormat.Pps` to create the PPS slide show.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPTX to PPS" >}}
```python
presentation = Presentation("presentation.pptx")
try:
    presentation.save("presentation.pps", SaveFormat.Pps)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTX to PPS in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PPTX presentation and save it as a binary PowerPoint 97-2003 PPS slide show. A PPS file is designed to open directly in slide show mode in compatible applications. The conversion does not require Microsoft PowerPoint.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPTX to PPS in Python" intro="Follow these steps to convert a PPTX presentation to a binary PowerPoint slide show." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPTX file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Pps` to write the PPS slide show.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPTX to Other Supported Formats" subTitle="You can also convert PPTX presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
