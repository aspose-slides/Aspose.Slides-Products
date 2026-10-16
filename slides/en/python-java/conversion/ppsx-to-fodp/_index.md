---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSX to FODP in Python
url: /python-java/conversion/ppsx-to-fodp/
keywords: Python PPSX conversion, PPSX to FODP, PowerPoint to FODP, slide show to FODP, Aspose.Slides for Python via Java
description: Convert PPSX files to FODP presentations in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPSX Files to FODP in Python" h2="Export a PowerPoint slide show as a Flat OpenDocument Presentation with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSX to FODP using Python" variant="code" %}}

Create a `Presentation` from the PPSX file, then call `save` with `SaveFormat.Fodp`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPSX to FODP" >}}
```python
presentation = Presentation("presentation.ppsx")
try:
    presentation.save("presentation.fodp", SaveFormat.Fodp)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSX to FODP in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PowerPoint Slide Show (`.ppsx`) and export it as a Flat OpenDocument Presentation (FODP). FODP stores the presentation in a single, uncompressed XML document. Microsoft PowerPoint, LibreOffice, and OpenOffice are not required for the conversion.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPSX to FODP in Python" intro="Follow these steps to export a PPSX file as a Flat OpenDocument Presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Python via Java](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPSX file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Fodp` to create the FODP file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
