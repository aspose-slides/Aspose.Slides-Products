---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTM to FODP in Python
url: /python-java/conversion/pptm-to-fodp/
keywords: Python PPTM conversion, PPTM to FODP, PowerPoint to FODP, flat OpenDocument presentation, Aspose.Slides for Python via Java
description: Convert PPTM files to FODP format in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTM to FODP in Python" h2="Save a macro-enabled PowerPoint presentation as a flat OpenDocument presentation with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to FODP using Python" variant="code" %}}

Create a `Presentation` from the source PPTM file, then call `save` with `SaveFormat.Fodp`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPTM to FODP" >}}
```python
presentation = Presentation("presentation.pptm")
try:
    presentation.save("presentation.fodp", SaveFormat.Fodp)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to FODP in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a macro-enabled PowerPoint presentation (`.pptm`) and save it as a flat OpenDocument presentation (`.fodp`). Unlike an ODP package, an FODP file stores the presentation in a single XML document. The FODP output does not retain the PPTM file's VBA project, and the conversion does not require Microsoft PowerPoint.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPTM to FODP in Python" intro="Follow these steps to save a PowerPoint PPTM presentation as a single-file FODP document." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPTM file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Fodp` and an `.fodp` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPTM to Other Supported Formats" subTitle="You can also convert PPTM presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
