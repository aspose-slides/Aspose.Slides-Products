---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PNG to PPTX in Python
url: /python-net/conversion/png-to-pptx/
keywords: Convert PNG to PPTX, PNG to PPTX, PowerPoint, PNG, PPTX, Python API, Python Library
description: Convert PNG to PPTX in Python. Use the Aspose.Slides Python API to place a PNG image on a slide and save it as a PowerPoint presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PNG to PPTX in Python" h2="Place a PNG image on a slide and save it as PPTX with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Convert PNG to PPTX using Aspose.Slides" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you create a PowerPoint presentation from a PNG image. Add the image to `Presentation.images`, place it on a `Slide` with `ShapeCollection.add_picture_frame`, and save the presentation by using `SaveFormat.PPTX`.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Convert PNG to PPTX in Python" %}}
Create a `Presentation`, add the source PNG image to its first `Slide`, and save the result in the PowerPoint Open XML format.

{{% blocks/products/pf/agp/code-block title="Python code for converting PNG to PPTX" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="How to Convert PNG to PPTX Using the Aspose.Slides Python API" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert PNG to PPTX in Python." >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install [*Aspose.Slides for Python via .NET*](/slides/python-net/). See the [installation guide](https://docs.aspose.com/slides/python-net/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and access its first `Slide`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PNG image with `Images.from_file` and add it to `Presentation.images`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Match the slide size to the image and add a picture frame with `ShapeCollection.add_picture_frame`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save` with the output file path and `SaveFormat.PPTX`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}





{{< blocks/products/pf/agp/other-supported-section title="Other Supported PowerPoint Conversions" subTitle="You can also convert other supported formats to PowerPoint presentations." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
