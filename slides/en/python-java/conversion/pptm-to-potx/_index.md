---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTM to POTX in Python
url: /python-java/conversion/pptm-to-potx/
keywords: Python PPTM conversion, PPTM to POTX, PowerPoint template conversion, presentation format conversion, Aspose.Slides for Python via Java
description: Convert PPTM files to POTX format in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTM to POTX in Python" h2="Save a macro-enabled PowerPoint presentation as a macro-free PowerPoint template with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to POTX using Python" variant="code" %}}

Create a `Presentation` from the source PPTM file, then call `save` with `SaveFormat.Potx`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python tutorial for converting PPTM into POTX" >}}
```python
presentation = Presentation("presentation.pptm")
try:
    presentation.save("presentation.potx", SaveFormat.Potx)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to POTX in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a macro-enabled PowerPoint presentation (`.pptm`) and save it as a PowerPoint Open XML template (`.potx`) without Microsoft PowerPoint. The conversion retains supported slide content, layouts, and formatting. POTX is a macro-free format, so the source presentation's VBA project is not included in the output.

Load the source file with `Presentation`, then call `save` with `SaveFormat.Potx`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPTM to POTX in Python" intro="Follow these steps to save a PowerPoint PPTM presentation as a macro-free PowerPoint template." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPTM file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Potx` and a `.potx` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPTM to Other Supported Formats" subTitle="You can also convert PPTM presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
