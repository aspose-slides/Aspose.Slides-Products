---
title: Merge PPTX Files Using Python
url: /python-net/merge/pptx/
keywords: Merge PPTX, Join PPTX, Combine PPTX, PowerPoint, Presentation, Python, Aspose
description: Merge multiple PPTX presentations into a single file in Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PPTX Files in Python" h2="Build cross-platform Python applications that merge, inspect, create, and convert Microsoft PowerPoint and OpenDocument presentations without installing Microsoft PowerPoint or OpenOffice." >}}

{{% blocks/products/pf/feature-page-section h2="Merge PPTX in Python" %}}

[**Aspose.Slides for Python via .NET**](/slides/python-net/) is a presentation-processing library that can combine multiple PPTX files. To merge presentations, clone each slide from a source presentation into a destination presentation. The cloned slides retain their content, layouts, formatting, shapes, comments, and animations.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge PPTX files using Python" %}}
Open the destination and source presentations, clone each source slide into the destination presentation, and save the merged result as a PPTX file.

{{% blocks/products/pf/agp/code-block title="Python code to merge multiple PPTX files into one presentation" offSpacer="true" %}}

```python
with slides.Presentation("presentation1.pptx") as destination_presentation:
    with slides.Presentation("presentation2.pptx") as source_presentation:
        for slide in source_presentation.slides:
            destination_presentation.slides.add_clone(slide)

    destination_presentation.save("merged.pptx", slides.export.SaveFormat.PPTX)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge PPTX using Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge two PPTX files into one presentation in Python." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via .NET**](/slides/python-net/) from PyPI.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides` package into your Python project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the destination and source PPTX files with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Iterate through the source slides and append each one to the destination by calling [`add_clone`](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/add_clone/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.PPTX` to write the merged presentation to one PPTX file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Export PPTX to Other Supported Formats" subTitle="You can also combine PPTX presentations and export the result to other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptx-to-ppt/" name="PPTX TO PPT" >}}
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
