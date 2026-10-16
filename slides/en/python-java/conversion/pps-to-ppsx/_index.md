---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPS to PPSX in Python
url: /python-java/conversion/pps-to-ppsx/
keywords: Python PPS conversion, PPS to PPSX, PowerPoint slide show conversion, Open XML slide show, Aspose.Slides for Python via Java
description: Convert PPS slide shows to PowerPoint PPSX files in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPS Slide Shows to PPSX in Python" h2="Save a legacy PowerPoint slide show in the Open XML PPSX format with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPS to PPSX using Python" variant="code" %}}

Create a `Presentation` from the PPS file, then call `save` with `SaveFormat.Ppsx`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPS to PPSX" >}}
```python
presentation = Presentation("presentation.pps")
try:
    presentation.save("presentation.ppsx", SaveFormat.Ppsx)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPS to PPSX in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a legacy binary PowerPoint slide show (PPS) and save it as a macro-free Open XML slide show (PPSX). The converted file retains the slide show document type and opens directly in slide show mode in compatible applications. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPS to PPSX in Python" intro="Follow these steps to convert a legacy PowerPoint slide show to the Open XML PPSX format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPS file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Ppsx` to create the PPSX slide show.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPS to Other Supported Formats" subTitle="You can also convert PPS slide shows to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
