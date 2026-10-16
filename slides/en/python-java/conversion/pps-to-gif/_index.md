---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPS to GIF in Python
url: /python-java/conversion/pps-to-gif/
keywords: Python PPS conversion, PPS to GIF, PowerPoint to GIF, slide show to animated GIF, Aspose.Slides for Python via Java
description: Convert PPS files to animated GIF images in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPS Files to Animated GIF in Python" h2="Export the slides and transitions in a PowerPoint PPS slide show to a single animated GIF with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPS to GIF using Python" variant="code" %}}

Create a `Presentation` from the PPS file and call `save` with `SaveFormat.Gif` to create an animated GIF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPS to animated GIF" >}}
```python
presentation = Presentation("presentation.pps")
try:
    presentation.save("presentation.gif", SaveFormat.Gif)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPS to GIF in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PowerPoint 97–2003 slide show (`PPS`) and export it as an animated `GIF`. The resulting file presents the slides as animation frames and can include slide transitions supported by the GIF exporter. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPS to animated GIF in Python" intro="Follow these steps to export a PowerPoint 97–2003 slide show as a single animated GIF." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPS file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Gif` to generate the animated GIF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPS to Other Supported Formats" subTitle="You can also convert PPS slide shows to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
