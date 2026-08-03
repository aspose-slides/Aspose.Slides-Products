---
title: Merge POTX Files and Save as PPS Using Python
url: /python-net/merge/potx-to-pps/
keywords: Merge POTX to PPS, Join POTX to PPS, Combine POTX to PPS, PowerPoint, Presentation, PPS, Python, Aspose
description: Merge multiple POTX presentation files in Python and save the combined presentation as a PPS file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge POTX Files and Save as PPS in Python" h2="Combine PowerPoint template files and save the merged presentation as a PowerPoint 97–2003 slide show with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Merge POTX to PPS in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you merge Microsoft PowerPoint Open XML Presentation Template (POTX) files by cloning slides from one `Presentation` into another. After combining the slides with `SlideCollection.add_clone`, save the destination presentation in PowerPoint 97–2003 Slide Show (PPS) format by passing `SaveFormat.PPS` to `Presentation.save`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge POTX Files to PPS Using Python" %}}
Open the destination and source POTX files, append a clone of each source slide, and save the merged presentation as a PPS file.

{{% blocks/products/pf/agp/code-block title="Python code for merging POTX files and saving the result as PPS" offSpacer="true" %}}

```python
with slides.Presentation("destination.potx") as destination_presentation:
    with slides.Presentation("source.potx") as source_presentation:
        for slide in source_presentation.slides:
            destination_presentation.slides.add_clone(slide)

    destination_presentation.save("merged_presentation.pps", slides.export.SaveFormat.PPS)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Merge POTX Files and Save as PPS with Aspose.Slides for Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge two POTX files and save the combined presentation as a PPS file." >}}

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
Open the destination and source POTX files as `Presentation` instances.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Iterate through the source slides and call [`SlideCollection.add_clone`](https://reference.aspose.com/slides/python-net/aspose.slides/slidecollection/add_clone/) for each slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save` with `SaveFormat.PPS` to write the merged presentation to a PPS file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Export POTX to Other Supported Formats" subTitle="You can also combine POTX presentations and save them in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-pptx/" name="POTX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-ppt/" name="POTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-pdf/" name="POTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-html/" name="POTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-png/" name="POTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-bmp/" name="POTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-jpg/" name="POTX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-fodp/" name="POTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-gif/" name="POTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-odp/" name="POTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-otp/" name="POTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-pot/" name="POTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-potm/" name="POTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-ppsm/" name="POTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-ppsx/" name="POTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-pptm/" name="POTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-svg/" name="POTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-tiff/" name="POTX TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/potx-to-xps/" name="POTX TO XPS" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
