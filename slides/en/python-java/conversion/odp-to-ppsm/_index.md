---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert ODP to PPSM in Python
url: /python-java/conversion/odp-to-ppsm/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, ODP to PPSM conversion, Python presentation library
description: Convert ODP presentations to PPSM slide shows in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert ODP Presentations to PPSM in Python" h2="Save an ODP presentation as a macro-enabled PowerPoint slide show with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert ODP to PPSM using Python" variant="code" %}}

Create a `Presentation` from the ODP file and call `save` with `SaveFormat.Ppsm` to create the PPSM slide show.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting ODP to PPSM" >}}
```python
presentation = Presentation("presentation.odp")
try:
    presentation.save("presentation.ppsm", SaveFormat.Ppsm)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert ODP to PPSM in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load an ODP presentation and save it as a PPSM file. PPSM is the macro-enabled Office Open XML format for PowerPoint slide shows; converting an ODP file does not add VBA macros to it. The conversion does not require Microsoft PowerPoint, LibreOffice, or OpenOffice.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert ODP to PPSM in Python" intro="Follow these steps to convert an OpenDocument presentation to a macro-enabled PowerPoint slide show." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source ODP file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Ppsm` to write the PPSM slide show.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert ODP to Other Supported Formats" subTitle="You can also convert ODP presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
