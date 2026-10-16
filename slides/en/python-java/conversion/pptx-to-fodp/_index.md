---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTX to FODP in Python
url: /python-java/conversion/pptx-to-fodp/
keywords: Python PPTX conversion, PPTX to FODP, PowerPoint to Flat OpenDocument Presentation, presentation conversion, Aspose.Slides for Python via Java
description: Convert PPTX files to Flat OpenDocument Presentation (FODP) format in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTX to FODP in Python" h2="Export PowerPoint presentations to Flat OpenDocument Presentation format with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTX to FODP using Python" variant="code" %}}

Create a `Presentation` from the PPTX file, then call `save` with `SaveFormat.Fodp`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPTX to FODP" >}}
```python
presentation = Presentation("presentation.pptx")
try:
    presentation.save("presentation.fodp", SaveFormat.Fodp)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTX to FODP in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PowerPoint presentation (`.pptx`) and save it as a Flat OpenDocument Presentation (`.fodp`). FODP stores an OpenDocument presentation as a single uncompressed XML file, which is useful for source control and XML-based processing. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPTX to FODP in Python" intro="Follow these steps to export a PPTX file as a Flat OpenDocument Presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPTX file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Fodp` to create the FODP file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPTX to Other Supported Formats" subTitle="You can also convert PPTX presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
