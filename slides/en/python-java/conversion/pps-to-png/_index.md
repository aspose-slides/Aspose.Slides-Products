---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPS to PNG in Python
url: /python-java/conversion/pps-to-png/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, PPS to PNG conversion, Python presentation library
description: Convert PPS slides to PNG images in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPS to PNG in Python" h2="Render every slide in a PowerPoint Show as a high-quality PNG image." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="How to Convert PPS to PNG in Python" variant="code" %}}

Load the PPS file into a `Presentation`, render each slide with `getImage`, and save each result in PNG format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python tutorial for converting PPS into PNG" >}}
```python
presentation = Presentation("presentation.pps")
try:
    slide_count = presentation.getSlides().size()

    for slide_index in range(slide_count):
        slide = presentation.getSlides().get_Item(slide_index)
        slide_image = slide.getImage(2.0, 2.0)
        try:
            slide_number = slide_index + 1
            file_path = f"slide-{slide_number}.png"
            slide_image.save(file_path, ImageFormat.Png)
        finally:
            slide_image.dispose()
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPS to PNG in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can render slides from a PowerPoint Show (`.pps`) file as PNG images without Microsoft PowerPoint. Because a PNG file stores a single image, the conversion creates a separate output file for each slide.

Use `Presentation.getSlides` to iterate through the source slides. For each `Slide`, call `getImage` and save the returned image with `ImageFormat.Png`. The scaling values passed to `getImage` control the output dimensions relative to the original slide size.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps to Convert PPS to PNG in Python" intro="The conversion renders each slide in the PPS presentation to a separate PNG image." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Python via Java](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure JPype and make the Aspose.Slides package available to your Python project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` from the source `.pps` file and determine the slide count.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access each `Slide`, call `getImage`, and save the result with `ImageFormat.Png`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPS to Other Supported Formats" subTitle="You can also convert PPS files to the formats listed below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
