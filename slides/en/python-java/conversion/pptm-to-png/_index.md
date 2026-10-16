---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTM to PNG in Python
url: /python-java/conversion/pptm-to-png/
keywords: Python PPTM conversion, PPTM to PNG, PowerPoint to PNG, presentation slide to image, Aspose.Slides for Python via Java
description: Convert PPTM presentation slides to PNG images in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTM Slides to PNG Images in Python" h2="Render every slide in a macro-enabled PowerPoint presentation as a PNG image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to PNG using Python" variant="code" %}}

Load the PPTM file into a `Presentation`, render each slide with `getImage`, and save each result in PNG format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python tutorial for converting PPTM into PNG" >}}
```python
presentation = Presentation("presentation.pptm")
try:
    slide_count = presentation.getSlides().size()

    for slide_index in range(slide_count):
        slide = presentation.getSlides().get_Item(slide_index)
        slide_image = slide.getImage(2.0, 2.0)
        try:
            file_path = f"slide-{slide_index + 1}.png"
            slide_image.save(file_path, ImageFormat.Png)
        finally:
            slide_image.dispose()
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to PNG in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can render the slides in a macro-enabled PowerPoint presentation (`.pptm`) as PNG images without Microsoft PowerPoint. Because one PNG file stores one image, the conversion creates a separate output file for each slide. Animations, transitions, macros, and other interactive behavior are not included in the rendered images.

Access each slide through a variable, call `getImage`, and save the returned image with `ImageFormat.Png`. The scaling values passed to `getImage` control the output dimensions relative to the original slide size.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPTM slides to PNG images in Python" intro="Follow these steps to render the slides in a PowerPoint PPTM presentation as separate PNG images." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPTM file with `Presentation` and determine the slide count.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access each slide through a variable, call `getImage`, and save the result with `ImageFormat.Png`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPTM to Other Supported Formats" subTitle="You can also convert PPTM presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
