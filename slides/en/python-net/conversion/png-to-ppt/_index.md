---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PNG to PPT in Python
url: /python-net/conversion/png-to-ppt/
keywords: Convert PNG to PPT, PNG to PPT, PowerPoint, PNG, PPT, Python API, Python Library
description: Convert PNG to PPT in Python. Use the Aspose.Slides Python API to place a PNG image on a slide and save it as a PowerPoint presentation.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PNG to PPT in Python" h2="Place a PNG image on a slide and save it as PPT with a cross-platform Python API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to PPT in Python" variant="code" %}}

Create a `Presentation`, add the source PNG image to its first `Slide`, and save the result in the PowerPoint 97-2003 presentation format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PNG to PPT" >}}
```python
with slides.Presentation() as presentation:
    slide = presentation.slides[0]

    with slides.Images.from_file("image.png") as source_image:
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
    presentation.save("image.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to PPT using Aspose.Slides" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you create a PowerPoint presentation from a PNG image. Add the image to `Presentation.images`, place it on a `Slide` with `ShapeCollection.add_picture_frame`, and save the presentation by using `SaveFormat.PPT`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PNG to PPT Using the Aspose.Slides Python API" intro="Follow these steps to convert PNG to PPT in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/). See the [installation guide](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and access its first `Slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PNG image with `Images.from_file` and add it to `Presentation.images`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Match the slide size to the image and add a picture frame with `ShapeCollection.add_picture_frame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Presentation.save` with the output file path and `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported PowerPoint Conversions" subTitle="You can also convert other supported formats to PowerPoint presentations." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
