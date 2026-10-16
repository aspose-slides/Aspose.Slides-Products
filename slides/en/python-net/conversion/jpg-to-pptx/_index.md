---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert JPG to PPTX in Python
url: /python-net/conversion/jpg-to-pptx/
keywords: Convert JPG to PPTX, JPG to PPTX, PowerPoint, JPG, PPTX, Python API, Python Library
description: Convert JPG images to PPTX in Python. Use the Aspose.Slides Python API to place a JPG image on a slide and save it as a PowerPoint presentation.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert JPG to PPTX in Python" h2="Create a PowerPoint presentation from a JPG image with a cross-platform Python API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert JPG to PPTX in Python" variant="code" %}}

Create a `Presentation`, add the source JPG image to its first `Slide`, and save the result in the PowerPoint Open XML format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting JPG to PPTX" >}}
```python
with slides.Presentation() as presentation:
    slide = presentation.slides[0]

    with slides.Images.from_file("image.jpg") as source_image:
        presentation_image = presentation.images.add_image(source_image)

    presentation.slide_size.set_size(
        presentation_image.width,
        presentation_image.height,
        slides.SlideSizeScaleType.DO_NOT_SCALE,
    )

    slide.shapes.add_picture_frame(
        slides.ShapeType.RECTANGLE,
        0,
        0,
        presentation_image.width,
        presentation_image.height,
        presentation_image,
    )
    presentation.save("image.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert JPG to PPTX Using Aspose.Slides" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you create a PowerPoint presentation from a JPG image. Add the image to `Presentation.images`, place it on a slide with `ShapeCollection.add_picture_frame`, and call `Presentation.save` with `SaveFormat.PPTX`.

The resulting PPTX file contains one slide whose size matches the source image. This workflow preserves the image's aspect ratio and does not require Microsoft PowerPoint or another presentation application.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert JPG to PPTX in Python" intro="Follow these steps to convert JPG to PPTX in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and access its first `Slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the JPG image with `Images.from_file` and add it to `Presentation.images`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Match the slide size to the image and add a picture frame with `ShapeCollection.add_picture_frame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Presentation.save` with the output file path and `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported PowerPoint Conversions" subTitle="You can also convert files in other formats to PowerPoint." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
