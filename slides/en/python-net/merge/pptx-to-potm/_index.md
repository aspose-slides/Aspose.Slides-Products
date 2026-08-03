---
title: Merge PPTX Files to POTM in Python
url: /python-net/merge/pptx-to-potm/
keywords: Merge PPTX to POTM, Join PPTX to POTM, Combine PPTX to POTM, PowerPoint, Presentation, POTM, Python, Aspose
description: Merge multiple PPTX files into one POTM file using Python and Aspose.Slides.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PPTX Files into POTM in Python" h2="Combine PowerPoint presentations and save the result as a POTM file with a fast, cross-platform Python API. Microsoft PowerPoint is not required." >}}

{{% blocks/products/pf/feature-page-section h2="Merge PPTX to POTM in Python" %}}

[**Aspose.Slides for Python via .NET**](/slides/python-net/) is a Python library for creating, editing, and converting presentation files. To merge `PPTX` presentations, clone each slide from a source `Presentation` into a destination presentation by calling [`add_clone`](https://reference.aspose.com/slides/python-net/aspose.slides/slidecollection/add_clone/) on its `slides` collection. Cloned slides retain their shapes, styles, text, formatting, comments, and animations. The combined presentation can then be saved as a `POTM` file.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge PPTX files to POTM using Python" %}}
Clone each slide from the source presentation into the destination presentation, then save the combined presentation in `POTM` format.

{{% blocks/products/pf/agp/code-block title="Python code to merge multiple PPTX files into one POTM file" offSpacer="true" %}}

```python
with slides.Presentation("presentation1.pptx") as destination_presentation:
    with slides.Presentation("presentation2.pptx") as source_presentation:
        for slide in source_presentation.slides:
            destination_presentation.slides.add_clone(slide)

    destination_presentation.save("merged.potm", slides.export.SaveFormat.POTM)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge PPTX to POTM using Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge two PPTX files and save the result as POTM in Python." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via .NET**](/slides/python-net/) with `pip install aspose-slides`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the first `PPTX` file into the destination `Presentation`, and load the second `PPTX` file into the source `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Iterate through the source presentation's `slides` collection.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Clone each source `Slide` into the destination presentation by calling [`add_clone`](https://reference.aspose.com/slides/python-net/aspose.slides/slidecollection/add_clone/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save` with `SaveFormat.POTM` to write the merged presentation to a `POTM` file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Export PPTX to Other Supported Formats" subTitle="You can also combine PPTX presentations and save the result in other supported formats." >}}

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
