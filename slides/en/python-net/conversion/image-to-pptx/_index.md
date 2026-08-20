---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert Image to PPTX in Python
url: /python-net/conversion/image-to-pptx/
keywords: Image to PPTX, Convert Image to PPTX, Python API, Python Library, Image, PPTX
description: Convert images to PPTX in Python. Use the Aspose.Slides Python API to place an image on a slide and save it as a PowerPoint presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert Image to PPTX in Python" h2="Create a PowerPoint presentation from an image with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Convert Image to PPTX in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you create a PowerPoint presentation from a raster image. Add the image to `Presentation.images`, place it on a slide with `ShapeCollection.add_picture_frame`, and call `Presentation.save` with `SaveFormat.PPTX`.

The resulting PPTX file contains one slide whose size matches the source image. This workflow preserves the image's aspect ratio and does not require Microsoft PowerPoint or another presentation application.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert an Image to PPTX Using Python" %}}
Create a `Presentation`, add the source image to its first `Slide`, and save the result in the PowerPoint Open XML format.

{{% blocks/products/pf/agp/code-block title="Python code for converting an image to PPTX" offSpacer="true" %}}

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
    presentation.save("image.pptx", slides.export.SaveFormat.PPTX)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Convert an Image to PPTX Using the Aspose.Slides Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert an image to PPTX in Python." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and access its first `Slide`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source image with `Images.from_file`, add it to `Presentation.images`, and use its dimensions for the slide and picture frame.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save` with the output file path and `SaveFormat.PPTX`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Convert Images to Other Supported Formats" subTitle="You can also convert images and save them in other supported formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
