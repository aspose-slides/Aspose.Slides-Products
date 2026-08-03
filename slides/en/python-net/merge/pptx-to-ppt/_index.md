---
title: Merge PPTX Files and Save as PPT Using Python
url: /python-net/merge/pptx-to-ppt/
keywords: Merge PPTX to PPT, Join PPTX to PPT, Combine PPTX to PPT, PowerPoint, Presentation, PPT, Python, Aspose
description: Merge multiple PPTX presentations in Python and save the result as a single PPT file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PPTX Files and Save as PPT in Python" h2="Combine PowerPoint presentations and save the merged slides as a PPT file with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Merge PPTX to PPT in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you merge PowerPoint Open XML Presentation (`PPTX`) files by cloning slides from one presentation into another. After combining the slides with `SlideCollection.add_clone`, call `Presentation.save` with `SaveFormat.PPT` to write the merged presentation in the PowerPoint 97–2003 Presentation format.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge PPTX files to PPT using Python" %}}
Open the destination and source `PPTX` presentations, append a clone of each source slide, and save the merged presentation as a single `PPT` file.

{{% blocks/products/pf/agp/code-block title="Python code for merging PPTX files into a single PPT presentation" offSpacer="true" %}}

```python
with slides.Presentation("destination.pptx") as destination_presentation:
    with slides.Presentation("source.pptx") as source_presentation:
        for slide in source_presentation.slides:
            destination_presentation.slides.add_clone(slide)

    destination_presentation.save("merged-presentation.ppt", slides.export.SaveFormat.PPT)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge PPTX files and save as PPT with Aspose.Slides for Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge two PPTX files and save the result as a single PPT presentation." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install Aspose.Slides for Python via .NET by following the [installation guide](https://docs.aspose.com/slides/python-net/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Make the `aspose.slides` namespace available in your Python project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the destination and source `PPTX` files as `Presentation` instances.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Iterate through the source slides and call [`SlideCollection.add_clone`](https://reference.aspose.com/slides/python-net/aspose.slides/slidecollection/add_clone/) for each slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save` with `SaveFormat.PPT` to write the merged presentation as a single `PPT` file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Export PPTX to Other Supported Formats" subTitle="You can also combine PPTX presentations and save them in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-jpg/" name="PPTX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-fodp/" name="PPTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-odp/" name="PPTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-otp/" name="PPTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-pot/" name="PPTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-potm/" name="PPTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-potx/" name="PPTX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-pps/" name="PPTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-ppsm/" name="PPTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-ppsx/" name="PPTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-pptm/" name="PPTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-tiff/" name="PPTX TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-xps/" name="PPTX TO XPS" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
