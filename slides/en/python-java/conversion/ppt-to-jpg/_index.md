---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPT to JPG in Python
url: /python-java/conversion/ppt-to-jpg/
keywords: Python PPT conversion, PPT to JPG, PowerPoint to JPEG, presentation slide to image, Aspose.Slides for Python via Java
description: Convert PPT presentation slides to JPG images in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPT Slides to JPG Images in Python" h2="Render every slide in a legacy PowerPoint presentation as a JPEG image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPT to JPG using Python" variant="code" %}}

Load the PPT file into a `Presentation`, render each slide with `getImage`, and save each result in JPEG format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPT slides to JPG" >}}
```python
presentation = Presentation("presentation.ppt")
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPT to JPG in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can render slides from a legacy PowerPoint presentation (`.ppt`) as JPG images without Microsoft PowerPoint. Because a JPG file stores one image, the conversion creates a separate output file for each slide.

Access each slide through a variable, call `getImage`, and save the returned image with `ImageFormat.Jpeg`. The scaling values passed to `getImage` control the output dimensions relative to the original slide size.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPT slides to JPG in Python" intro="Follow these steps to render the slides in a PowerPoint PPT presentation as separate JPEG images." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPT file with `Presentation` and determine the slide count.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access each slide, call `getImage`, and save the result with `ImageFormat.Jpeg`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPT to Other Supported Formats" subTitle="You can also convert PPT presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
