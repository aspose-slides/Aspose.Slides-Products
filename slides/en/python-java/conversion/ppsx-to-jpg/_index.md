---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSX to JPG in Python
url: /python-java/conversion/ppsx-to-jpg/
keywords: Python PPSX conversion, PPSX to JPG, PowerPoint to JPG, slide show to JPEG, Aspose.Slides for Python via Java
description: Convert PPSX presentation slides to JPG images in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPSX Slides to JPG Images in Python" h2="Render every slide in a PowerPoint slide show as a JPEG image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="How to Convert PPSX to JPG in Python" variant="code" %}}

Load the PPSX file into a `Presentation`, render each slide with `getImage`, and save each result in JPEG format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPSX slides to JPG" >}}
```python
presentation = Presentation("presentation.ppsx")
try:
    slide_count = presentation.getSlides().size()

    for slide_index in range(slide_count):
        slide = presentation.getSlides().get_Item(slide_index)
        slide_image = slide.getImage(2.0, 2.0)
        try:
            slide_number = slide_index + 1
            file_path = f"slide-{slide_number}.jpg"
            slide_image.save(file_path, ImageFormat.Jpeg)
        finally:
            slide_image.dispose()
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSX to JPG in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can render the slides in a PowerPoint Slide Show (`.ppsx`) as JPG images without Microsoft PowerPoint. Because a JPG file stores one image, the conversion creates a separate output file for each slide. Animations, transitions, and other interactive behavior are not included in the images.

Use `Presentation.getSlides` to iterate through the source slides. For each `Slide`, call `getImage` and save the returned image with `ImageFormat.Jpeg`. The scaling values passed to `getImage` control the output dimensions relative to the original slide size.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps to Convert PPSX to JPG in Python" intro="The conversion renders each slide in the PPSX presentation to a separate JPEG image." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Python via Java](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure JPype and make the Aspose.Slides package available to your Python project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` from the source `.ppsx` file and determine the slide count.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access each `Slide`, call `getImage`, and save the result with `ImageFormat.Jpeg`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
