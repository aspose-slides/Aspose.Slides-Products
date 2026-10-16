---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSX to PNG in Python
url: /python-java/conversion/ppsx-to-png/
keywords: Python PPSX conversion, PPSX to PNG, PowerPoint to PNG, slide show to PNG, Aspose.Slides for Python via Java
description: Convert PPSX presentation slides to PNG images in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPSX Slides to PNG Images in Python" h2="Render every slide in a PowerPoint slide show as a PNG image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="How to Convert PPSX to PNG in Python" variant="code" %}}

Load the PPSX file into a `Presentation`, render each slide with `getImage`, and save each result in PNG format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPSX slides to PNG" >}}
```python
presentation = Presentation("presentation.ppsx")
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSX to PNG in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can render the slides in a PowerPoint Slide Show (`.ppsx`) as PNG images without Microsoft PowerPoint. Because a PNG file stores one image, the conversion creates a separate output file for each slide. Animations, transitions, and other interactive behavior are not included in the images.

Use `Presentation.getSlides` to iterate through the source slides. For each `Slide`, call `getImage` and save the returned image with `ImageFormat.Png`. The scaling values passed to `getImage` control the output dimensions relative to the original slide size.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps to Convert PPSX to PNG in Python" intro="The conversion renders each slide in the PPSX presentation to a separate PNG image." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Python via Java](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure JPype and make the Aspose.Slides package available to your Python project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` from the source `.ppsx` file and determine the slide count.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access each `Slide`, call `getImage`, and save the result with `ImageFormat.Png`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
