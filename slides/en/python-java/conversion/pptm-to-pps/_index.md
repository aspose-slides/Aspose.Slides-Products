---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTM to PPS in Python
url: /python-java/conversion/pptm-to-pps/
keywords: Python PPTM conversion, PPTM to PPS, PowerPoint slide show conversion, legacy PowerPoint format, Aspose.Slides for Python via Java
description: Convert PPTM files to PPS slide shows in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTM Files to PPS in Python" h2="Save a macro-enabled PPTM file as a legacy PowerPoint slide show with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to PPS using Python" variant="code" %}}

Create a `Presentation` from the PPTM file, then call `save` with `SaveFormat.Pps`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPTM to PPS" >}}
```python
presentation = Presentation("presentation.pptm")
try:
    presentation.save("presentation.pps", SaveFormat.Pps)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to PPS in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a macro-enabled PPTM presentation and save it as a PPS slide show. PPS is the legacy binary PowerPoint Show format and normally opens directly in Slide Show view. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPTM to PPS in Python" intro="Follow these steps to save a PPTM presentation as a PPS slide show." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPTM file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Pps` to create the PPS slide show.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPTM to Other Supported Formats" subTitle="You can also convert PPTM presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
