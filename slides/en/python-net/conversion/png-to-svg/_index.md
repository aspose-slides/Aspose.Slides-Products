---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PNG to SVG in Python
url: /python-net/conversion/png-to-svg/
keywords: PNG to SVG, Convert PNG to SVG, Python API, Python Library, PNG, SVG
description: Convert PNG to SVG in Python. Use the Aspose.Slides Python API to place a PNG image on a slide and export the slide as SVG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PNG to SVG in Python" h2="Place a PNG image on a slide and export it as SVG with a cross-platform Python API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to SVG using Python" variant="code" %}}

Create a `Presentation`, add the PNG image to its first `Slide`, match the slide size to the image, and export the slide as SVG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PNG into SVG" >}}
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

    with open("image.svg", "wb") as output_stream:
        slide.write_as_svg(output_stream)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to SVG in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you place a PNG image on a `Slide` and export the slide by using `Slide.write_as_svg`. The generated SVG preserves the PNG as raster content inside the scalable slide representation.

This process does not trace or vectorize the PNG pixels. It creates an SVG file whose canvas matches the source image and can be displayed in browsers and other SVG-compatible applications.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PNG to SVG Using the Aspose.Slides Python API" intro="Follow these steps to convert PNG to SVG in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and access its first `Slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PNG with `Images.from_file`, add it to `Presentation.images`, and place it on the slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Slide.write_as_svg` with a writable binary stream.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PNG to Other Supported Formats" subTitle="You can also convert PNG images to other supported formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
