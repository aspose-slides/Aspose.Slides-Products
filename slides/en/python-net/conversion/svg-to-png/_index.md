---
title: Convert SVG to PNG in Python
url: /python-net/conversion/svg-to-png/
keywords: SVG to PNG, Convert SVG to PNG, Python API, Python Library, SVG, PNG
description: Convert SVG images to PNG files in Python. Use the Aspose.Slides Python API to rasterize scalable vector graphics as PNG images.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert SVG to PNG in Python" h2="Cross-platform Python API for rasterizing SVG images as PNG files without presentation software" >}}

{{% blocks/products/pf/feature-page-section h2="Convert SVG to PNG in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you import SVG content into a presentation and render it as a PNG image. Create an `SvgImage`, add it to `Presentation.images`, place it on a `Slide`, and render the slide by using `Slide.get_image`.

SVG is a vector format, while PNG is a raster format. The output dimensions therefore depend on the SVG dimensions and the rendering scale used for the slide.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert SVG to PNG using Python" %}}
Read the SVG content, add it to a `Presentation`, size the slide to the imported image, and save the rendered `Slide` as a PNG file.

{{% blocks/products/pf/agp/code-block title="Python code for converting SVG into PNG" offSpacer="true" %}}

```python
with slides.Presentation() as presentation:
    slide = presentation.slides[0]

    with open("image.svg", "rt", encoding="utf-8") as input_stream:
        svg_content = input_stream.read()

    svg_image = slides.SvgImage(svg_content)
    presentation_image = presentation.images.add_image(svg_image)
    image_width = presentation_image.width
    image_height = presentation_image.height

    presentation.slide_size.set_size(
        image_width, image_height, slides.SlideSizeScaleType.DO_NOT_SCALE)

    slide.shapes.add_picture_frame(
        slides.ShapeType.RECTANGLE, 0, 0, image_width, image_height, presentation_image)

    with slide.get_image() as png_image:
        png_image.save("image.png", slides.ImageFormat.PNG)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Convert SVG to PNG Using the Aspose.Slides Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert SVG to PNG in Python." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Read the source SVG and create an `SvgImage`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Add the SVG to `Presentation.images`, place it on a `Slide`, and match the slide size to the image dimensions.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render the slide with `Slide.get_image` and save the result by using `IImage.save` with `ImageFormat.PNG`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Convert SVG to Other Supported Formats" subTitle="Explore other supported SVG conversion formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
