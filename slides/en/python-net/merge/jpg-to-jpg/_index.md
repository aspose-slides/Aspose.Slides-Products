---
lastmod: 2026-07-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge JPG Images in Python
url: /python-net/merge/jpg-to-jpg/
keywords: Merge JPG, JPG to JPG, Join JPG, Combine JPG, Python API, Python Library
description: Merge multiple JPG images in Python and save the combined result as a single JPG file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge JPG Images in Python" h2="Combine multiple JPG images into one file with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Merge JPG to JPG Using Aspose.Slides" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you place multiple JPG images on one `Slide` and render the combined layout as a single JPG file. Load each source image with `Images.from_file`, add it to `Presentation.images`, create picture frames, and save the rendered `IImage` with `ImageFormat.JPEG`.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge JPG Images into One File in Python" %}}
Create a `Presentation`, place the source JPG images side by side on its first `Slide`, and render the slide as one JPG file.

{{% blocks/products/pf/agp/code-block title="Python code for merging JPG images into one JPG file" offSpacer="true" %}}
```python
with slides.Presentation() as presentation:
    slide = presentation.slides[0]

    with slides.Images.from_file("image1.jpg") as first_source_image:
        first_presentation_image = presentation.images.add_image(first_source_image)

    slide.shapes.add_picture_frame(
        slides.ShapeType.RECTANGLE, 0, 0, 360, 270, first_presentation_image)

    with slides.Images.from_file("image2.jpg") as second_source_image:
        second_presentation_image = presentation.images.add_image(second_source_image)

    slide.shapes.add_picture_frame(
        slides.ShapeType.RECTANGLE, 360, 0, 360, 270, second_presentation_image)

    with slide.get_image(1, 1) as combined_image:
        combined_image.save("merged.jpg", slides.ImageFormat.JPEG)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to Merge JPG Images in Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to combine multiple JPG images into one JPG file." >}}


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
Load the source JPG images with `Images.from_file`, add them to `Presentation.images`, and arrange them in picture frames.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render the `Slide` with `Slide.get_image`, then call `IImage.save` with `ImageFormat.JPEG`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}





{{< blocks/products/pf/agp/other-supported-section title="Merge Other Files" subTitle="You can also combine files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/png-to-pdf/" name="PNG TO PDF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
