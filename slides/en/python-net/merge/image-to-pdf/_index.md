---
lastmod: 2026-07-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge Images to PDF in Python
url: /python-net/merge/image-to-pdf/
keywords: Image to PDF, Merge Image to PDF, Join Image to PDF, PDF, Image, Python API, Python Library
description: Merge multiple images in Python and save the combined result as a single-page PDF document.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge Images to PDF in Python" h2="Combine multiple images and save the result as a PDF document with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Merge Images to PDF Using Aspose.Slides" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you place multiple images on one `Slide` and export the combined layout as a single-page PDF document. Load each source image with `Images.from_file`, add it to `Presentation.images`, create picture frames, and call `Presentation.save` with `SaveFormat.PDF`.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge Images into a PDF Document in Python" %}}
Create a `Presentation`, place the source images side by side on its first `Slide`, and export the slide as a one-page PDF document.

{{% blocks/products/pf/agp/code-block title="Python code for merging images into a PDF document" offSpacer="true" %}}

```python
with slides.Presentation() as presentation:
    slide = presentation.slides[0]

    with slides.Images.from_file("image1.png") as first_source_image:
        first_presentation_image = presentation.images.add_image(first_source_image)

    slide.shapes.add_picture_frame(
        slides.ShapeType.RECTANGLE, 0, 0, 360, 270, first_presentation_image)

    with slides.Images.from_file("image2.png") as second_source_image:
        second_presentation_image = presentation.images.add_image(second_source_image)

    slide.shapes.add_picture_frame(
        slides.ShapeType.RECTANGLE, 360, 0, 360, 270, second_presentation_image)

    presentation.save("merged.pdf", slides.export.SaveFormat.PDF)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to Merge Images into a PDF Document in Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to combine multiple images into one PDF document." >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides` module in your Python project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and access its first `Slide`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source images with `Images.from_file`, add them to `Presentation.images`, and arrange them in picture frames.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save` with `SaveFormat.PDF` to create the combined PDF document.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}





{{< blocks/products/pf/agp/other-supported-section title="Merge Other Files" subTitle="You can also combine files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/png-to-pdf/" name="PNG TO PDF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
