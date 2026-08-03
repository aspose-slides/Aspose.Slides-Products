---
title: Merge POTM Files and Export to JPG Using Python
url: /python-net/merge/potm-to-jpg/
keywords: Merge POTM to JPG, Join POTM to JPG, Combine POTM to JPG, PowerPoint, Presentation, JPG, Python, Aspose
description: Merge multiple POTM presentation files in Python and export each slide as a JPEG image.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge POTM Files and Export to JPG in Python" h2="Combine macro-enabled PowerPoint template files and render the merged slides as JPEG images with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Merge POTM to JPG in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you merge POTM presentation files by cloning slides from one `Presentation` into another. After combining the slides with `SlideCollection.add_clone`, render each slide with `Slide.get_image` and save the resulting `IImage` object in JPEG format.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge POTM Files to JPG Using Python" %}}
Open the destination and source POTM files, append a clone of each source slide, and render every slide in the merged presentation as a separate JPEG image.

{{% blocks/products/pf/agp/code-block title="Python code for merging POTM files and exporting the slides as JPG images" offSpacer="true" %}}

```python
image_scale = 2

with slides.Presentation("destination.potm") as destination_presentation:
    with slides.Presentation("source.potm") as source_presentation:
        for slide in source_presentation.slides:
            destination_presentation.slides.add_clone(slide)

    for slide in destination_presentation.slides:
        file_path = f"merged_slide_{slide.slide_number}.jpg"
        with slide.get_image(image_scale, image_scale) as slide_image:
            slide_image.save(file_path, slides.ImageFormat.JPEG)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Merge POTM Files and Export to JPG with Aspose.Slides for Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge two POTM files and export the merged slides as JPG images." >}}

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
Open the destination and source POTM files as `Presentation` instances.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Iterate through the source slides and call [`SlideCollection.add_clone`](https://reference.aspose.com/slides/python-net/aspose.slides/slidecollection/add_clone/) for each slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render each merged slide with `Slide.get_image`, then call `IImage.save` with `ImageFormat.JPEG` to create a separate JPG file for that slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Export POTM to Other Supported Formats" subTitle="You can also combine POTM presentations and save them in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-pptx/" name="POTM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-ppt/" name="POTM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-pdf/" name="POTM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-html/" name="POTM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-png/" name="POTM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-bmp/" name="POTM TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-fodp/" name="POTM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-gif/" name="POTM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-odp/" name="POTM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-otp/" name="POTM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-pot/" name="POTM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-potx/" name="POTM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-pps/" name="POTM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-ppsm/" name="POTM TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-ppsx/" name="POTM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-pptm/" name="POTM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-svg/" name="POTM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-tiff/" name="POTM TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potm-to-xps/" name="POTM TO XPS" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
