---
title: Merge FODP Files and Export to JPG Using Python
url: /python-net/merge/fodp-to-jpg/
keywords: Merge FODP to JPG, Join FODP to JPG, Combine FODP to JPG, PowerPoint, Presentation, JPG, Python, Aspose
description: Merge multiple FODP presentations in Python and export each slide as a JPEG image.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge FODP Files and Export to JPG in Python" h2="Combine Flat OpenDocument Presentation files and render the merged slides as JPEG images with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Merge FODP to JPG in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you merge Flat OpenDocument Presentation (FODP) files by cloning slides from one presentation into another. After combining the slides with `SlideCollection.add_clone`, render each slide with `Slide.get_image` and save the resulting `IImage` object in JPEG format.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge FODP files to JPG using Python" %}}
Open the destination and source FODP presentations, append a clone of each source slide, and render every slide in the merged presentation as a separate JPEG image.

{{% blocks/products/pf/agp/code-block title="Python code for merging FODP files and exporting the slides as JPG images" offSpacer="true" %}}

```python
image_scale = 2

with slides.Presentation("destination.fodp") as destination_presentation:
    with slides.Presentation("source.fodp") as source_presentation:
        for slide in source_presentation.slides:
            destination_presentation.slides.add_clone(slide)

    for slide in destination_presentation.slides:
        file_path = f"merged_slide_{slide.slide_number}.jpg"
        with slide.get_image(image_scale, image_scale) as slide_image:
            slide_image.save(file_path, slides.ImageFormat.JPEG)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge FODP files and export to JPG with Aspose.Slides for Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge two FODP files and export the merged slides as JPG images." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install Aspose.Slides for Python via .NET by following the [installation guide](https://docs.aspose.com/slides/python-net/installation/).
```console
pip install aspose-slides
```
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Make the `aspose.slides` namespace available in your Python project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the destination and source FODP files as `Presentation` instances.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Iterate through the source slides and call [`SlideCollection.add_clone`](https://reference.aspose.com/slides/python-net/aspose.slides/slidecollection/) for each slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render each merged slide with `Slide.get_image`, then call `IImage.save` with `ImageFormat.JPEG` to create a separate JPG file for that slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Export FODP to Other Supported Formats" subTitle="You can also combine FODP presentations and save them in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-pdf/" name="FODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-png/" name="FODP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-bmp/" name="FODP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-potm/" name="FODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-svg/" name="FODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-tiff/" name="FODP TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/fodp-to-xps/" name="FODP TO XPS" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
