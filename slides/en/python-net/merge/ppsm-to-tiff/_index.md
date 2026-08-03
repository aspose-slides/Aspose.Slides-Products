---
title: Merge PPSM Files to TIFF Using Python
url: /python-net/merge/ppsm-to-tiff/
keywords: Merge PPSM to TIFF, Join PPSM to TIFF, Combine PPSM to TIFF, PowerPoint, Presentation, TIFF, Python, Aspose
description: Merge multiple PPSM files and save the combined slides as a multi-page TIFF image in Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PPSM files to TIFF in Python" h2="Combine PPSM slide shows and save the result as a multi-page TIFF image with Aspose.Slides for Python via .NET. Microsoft PowerPoint and OpenOffice are not required." >}}

{{% blocks/products/pf/feature-page-section h2="Merge PPSM to TIFF in Python" %}}

[**Aspose.Slides for Python via .NET**](/slides/python-net/) lets you merge PPSM slide shows by cloning slides from a source `Presentation` into a destination `Presentation`. The cloned slides retain their layouts, shapes, styles, text, formatting, comments, and animations. The merged presentation can then be saved as one multi-page TIFF image.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge PPSM files to TIFF using Python" %}}
Clone each source slide with `add_clone`, then call `save` with `SaveFormat.TIFF`.

{{% blocks/products/pf/agp/code-block title="Python code to merge PPSM files into a multi-page TIFF image" offSpacer="true" %}}

```python
with slides.Presentation("presentation1.ppsm") as destination_presentation:
    with slides.Presentation("presentation2.ppsm") as source_presentation:
        for slide in source_presentation.slides:
            destination_presentation.slides.add_clone(slide)

    destination_presentation.save("merged_presentation.tiff", slides.export.SaveFormat.TIFF)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge PPSM to TIFF using Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge two PPSM files and save the result as TIFF in Python." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via .NET**](/slides/python-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides` package.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the destination and source PPSM files as `Presentation` instances.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Clone each source slide by using [`add_clone`](https://reference.aspose.com/slides/python-net/aspose.slides/slidecollection/add_clone/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the merged presentation as a multi-page TIFF image by using `SaveFormat.TIFF`.

{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Export PPSM to Other Supported Formats" subTitle="You can also merge PPSM files and export the result to other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-pptx/" name="PPSM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-ppt/" name="PPSM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-pdf/" name="PPSM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-html/" name="PPSM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-png/" name="PPSM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-bmp/" name="PPSM TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-jpg/" name="PPSM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-fodp/" name="PPSM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-gif/" name="PPSM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-odp/" name="PPSM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-otp/" name="PPSM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-pot/" name="PPSM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-potm/" name="PPSM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-potx/" name="PPSM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-pps/" name="PPSM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-pptm/" name="PPSM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-svg/" name="PPSM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/ppsm-to-xps/" name="PPSM TO XPS" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
