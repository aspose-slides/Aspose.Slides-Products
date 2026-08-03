---
title: Merge PPTM Files and Export to SVG Using Python
url: /python-net/merge/pptm-to-svg/
keywords: Merge PPTM to SVG, Join PPTM to SVG, Combine PPTM to SVG, PowerPoint, Presentation, SVG, Python, Aspose
description: Merge multiple PPTM presentations in Python and export each slide as a separate SVG image.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PPTM Files and Export to SVG in Python" h2="Combine macro-enabled PowerPoint presentations and render the merged slides as SVG images with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Merge PPTM to SVG in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you merge macro-enabled PowerPoint (PPTM) presentations by cloning slides from one presentation into another. After combining the slides with `SlideCollection.add_clone`, call `Slide.write_as_svg` to export each merged slide as a separate SVG image.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge PPTM files to SVG using Python" %}}
Open the destination and source PPTM presentations, append a clone of each source slide, and render every slide in the merged presentation as a separate SVG image.

{{% blocks/products/pf/agp/code-block title="Python code for merging PPTM files and exporting the slides as SVG images" offSpacer="true" %}}

```python
with slides.Presentation("destination.pptm") as destination_presentation:
    with slides.Presentation("source.pptm") as source_presentation:
        for slide in source_presentation.slides:
            destination_presentation.slides.add_clone(slide)

    for slide in destination_presentation.slides:
        file_path = f"merged-slide-{slide.slide_number}.svg"
        with open(file_path, "wb") as output_stream:
            slide.write_as_svg(output_stream)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge PPTM files and export to SVG with Aspose.Slides for Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge two PPTM files and export the merged slides as SVG images." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install Aspose.Slides for Python via .NET by following the [installation guide](https://docs.aspose.com/slides/python-net/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Make the `aspose.slides` namespace available in your Python project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the destination and source PPTM files as `Presentation` instances.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Iterate through the source slides and call [`SlideCollection.add_clone`](https://reference.aspose.com/slides/python-net/aspose.slides/slidecollection/add_clone/) for each slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
For each merged slide, open a binary output stream and call [`Slide.write_as_svg`](https://reference.aspose.com/slides/python-net/aspose.slides/slide/write_as_svg/) to create a separate SVG file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Export PPTM to Other Supported Formats" subTitle="You can also combine PPTM presentations and save them in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-pptx/" name="PPTM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-ppt/" name="PPTM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-pdf/" name="PPTM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-html/" name="PPTM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-png/" name="PPTM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-bmp/" name="PPTM TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-jpg/" name="PPTM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-fodp/" name="PPTM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-gif/" name="PPTM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-odp/" name="PPTM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-otp/" name="PPTM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-pot/" name="PPTM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-potm/" name="PPTM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-potx/" name="PPTM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-pps/" name="PPTM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-ppsm/" name="PPTM TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-ppsx/" name="PPTM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-tiff/" name="PPTM TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-xps/" name="PPTM TO XPS" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
