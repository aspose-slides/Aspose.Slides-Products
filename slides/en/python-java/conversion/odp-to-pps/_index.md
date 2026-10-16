---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert ODP to PPS in Python
url: /python-java/conversion/odp-to-pps/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, ODP to PPS conversion, Python presentation library
description: Convert ODP presentations to legacy PowerPoint PPS slide shows in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert ODP Presentations to PPS in Python" h2="Save an ODP presentation as a legacy PowerPoint PPS slide show with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert ODP to PPS using Python" variant="code" %}}

Create a `Presentation` from the ODP file and call `save` with `SaveFormat.Pps` to create the PPS slide show.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting ODP to PPS" >}}
```python
presentation = Presentation("presentation.odp")
try:
    presentation.save("presentation.pps", SaveFormat.Pps)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert ODP to PPS in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load an ODP presentation and save it as a PowerPoint 97-2003 PPS slide show. The PPS format is intended to open directly in slide show mode in compatible applications. The conversion does not require Microsoft PowerPoint, LibreOffice, or OpenOffice.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert ODP to PPS in Python" intro="Follow these steps to convert an OpenDocument presentation to a legacy PowerPoint PPS slide show." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source ODP file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Pps` to write the PPS slide show.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert ODP to Other Supported Formats" subTitle="You can also convert ODP presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
