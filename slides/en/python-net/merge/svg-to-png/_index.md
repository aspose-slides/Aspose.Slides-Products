---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge SVG Images into PNG in Python
url: /python-net/merge/svg-to-png/
keywords: Merge SVG to PNG, SVG to PNG, Join SVG to PNG, Combine SVG to PNG, Python API, Python Library
description: Merge multiple SVG images in Python and save the combined result as a single PNG file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge SVG Images into PNG in Python" h2="Combine multiple SVG images into one PNG file with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Merge SVG Images into PNG Using Aspose.Slides" %}}

[**Aspose.Slides for Python via .NET**](/slides/python-net/) lets you place multiple SVG images on one `Slide` and render the combined layout as a single PNG file. Read each SVG file as text, create an [`SvgImage`](https://reference.aspose.com/slides/python-net/aspose.slides/svgimage/), add it to `Presentation.images`, create picture frames, and save the image returned by [`Slide.get_image`](https://reference.aspose.com/slides/python-net/aspose.slides/slide/get_image/) with `ImageFormat.PNG`.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge SVG Images into One PNG File in Python" %}}
Create a `Presentation`, place the source SVG images side by side on its first `Slide`, and render the slide as one PNG file.

{{% blocks/products/pf/agp/code-block title="Python code for merging SVG images into one PNG file" offSpacer="true" %}}
```python
with slides.Presentation() as presentation:
    slide = presentation.slides[0]
    slide_width = presentation.slide_size.size.width
    slide_height = presentation.slide_size.size.height
    picture_width = slide_width / 2

    with open("image1.svg", "rt", encoding="utf-8") as first_svg_file:
        first_svg_content = first_svg_file.read()

    first_svg_image = slides.SvgImage(first_svg_content)
    first_presentation_image = presentation.images.add_image(first_svg_image)
    slide.shapes.add_picture_frame(
        slides.ShapeType.RECTANGLE, 0, 0, picture_width, slide_height, first_presentation_image)

    with open("image2.svg", "rt", encoding="utf-8") as second_svg_file:
        second_svg_content = second_svg_file.read()

    second_svg_image = slides.SvgImage(second_svg_content)
    second_presentation_image = presentation.images.add_image(second_svg_image)
    slide.shapes.add_picture_frame(
        slides.ShapeType.RECTANGLE, picture_width, 0, picture_width, slide_height, second_presentation_image)

    with slide.get_image(2, 2) as combined_image:
        combined_image.save("merged.png", slides.ImageFormat.PNG)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to Merge SVG Images into PNG in Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to combine multiple SVG images into one PNG file." >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install Aspose.Slides for Python via .NET by following the [installation guide](https://docs.aspose.com/slides/python-net/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Make the `aspose.slides` namespace available in your Python project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and access its first `Slide`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Read the source SVG files as text, create an `SvgImage` for each file, add the images to `Presentation.images`, and arrange them in picture frames.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render the `Slide` with `Slide.get_image`, then call `IImage.save` with `ImageFormat.PNG`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}





{{< blocks/products/pf/agp/other-supported-section title="Merge Other Files" subTitle="You can also combine files in other formats." >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/html-to-image/" name="HTML TO IMAGE" >}}
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
