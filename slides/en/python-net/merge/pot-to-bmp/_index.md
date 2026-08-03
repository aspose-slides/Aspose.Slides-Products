---
title: Merge POT Files and Export to BMP Using Python
url: /python-net/merge/pot-to-bmp/
keywords: Merge POT to BMP, Join POT to BMP, Combine POT to BMP, PowerPoint, Presentation, BMP, Python, Aspose
description: Merge multiple POT presentation files in Python and export each slide as a BMP image.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge POT Files and Export to BMP in Python" h2="Combine POT presentation files and render the merged slides as BMP images with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Merge POT to BMP in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you merge POT presentation files by cloning slides from one `Presentation` into another. After combining the slides with `SlideCollection.add_clone`, render each slide with `Slide.get_image` and save the resulting `IImage` object in BMP format.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge POT Files to BMP Using Python" %}}
Open the destination and source POT files, append a clone of each source slide, and render every slide in the merged presentation as a separate BMP image.

{{% blocks/products/pf/agp/code-block title="Python code for merging POT files and exporting the slides as BMP images" offSpacer="true" %}}

```python
image_scale = 2

with slides.Presentation("destination.pot") as destination_presentation:
    with slides.Presentation("source.pot") as source_presentation:
        for slide in source_presentation.slides:
            destination_presentation.slides.add_clone(slide)

    for slide in destination_presentation.slides:
        file_path = f"merged_slide_{slide.slide_number}.bmp"
        with slide.get_image(image_scale, image_scale) as slide_image:
            slide_image.save(file_path, slides.ImageFormat.BMP)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Merge POT Files and Export to BMP with Aspose.Slides for Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge two POT files and export the merged slides as BMP images." >}}

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
Open the destination and source POT files as `Presentation` instances.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Iterate through the source slides and call [`SlideCollection.add_clone`](https://reference.aspose.com/slides/python-net/aspose.slides/slidecollection/add_clone/) for each slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render each merged slide with `Slide.get_image`, then call `IImage.save` with `ImageFormat.BMP` to create a separate BMP file for that slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Export POT to Other Supported Formats" subTitle="You can also combine POT presentations and save them in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-pptx/" name="POT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-ppt/" name="POT TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-pdf/" name="POT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-html/" name="POT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-png/" name="POT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-jpg/" name="POT TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-fodp/" name="POT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-gif/" name="POT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-odp/" name="POT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-otp/" name="POT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-potm/" name="POT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-potx/" name="POT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-pps/" name="POT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-ppsm/" name="POT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-ppsx/" name="POT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-pptm/" name="POT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-svg/" name="POT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-tiff/" name="POT TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-xps/" name="POT TO XPS" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
