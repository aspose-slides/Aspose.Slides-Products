---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTM to SVG in Python
url: /python-java/conversion/pptm-to-svg/
keywords: Python PPTM conversion, PPTM to SVG, PowerPoint slide to SVG, presentation slide to vector image, Aspose.Slides for Python via Java
description: Convert PPTM presentation slides to SVG images in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTM Slides to SVG Images in Python" h2="Export every slide in a macro-enabled PowerPoint presentation as a separate SVG image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to SVG using Python" variant="code" %}}

Create a `Presentation` from the PPTM file, access each slide through a variable, and call `writeAsSvgToBytes` to create the SVG data.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPTM slides to SVG" >}}
```python
presentation = Presentation("presentation.pptm")
try:
    slide_count = presentation.getSlides().size()

    for slide_index in range(slide_count):
        slide = presentation.getSlides().get_Item(slide_index)
        file_path = f"slide-{slide_index + 1}.svg"
        svg_data = bytes(slide.writeAsSvgToBytes())

        with open(file_path, "wb") as output_file:
            output_file.write(svg_data)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to SVG in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a macro-enabled PowerPoint presentation (`.pptm`) and export each slide as a separate Scalable Vector Graphics (`.svg`) image. Each SVG contains a static rendering of one slide; VBA macros and interactive slide-show behavior are not included. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPTM slides to SVG in Python" intro="Follow these steps to export the slides in a PowerPoint PPTM presentation as separate SVG images." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPTM file with `Presentation` and access each slide through a variable.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `writeAsSvgToBytes` for each slide and write the returned data to an SVG file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPTM to Other Supported Formats" subTitle="You can also convert PPTM presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
