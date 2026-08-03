---
title: Merge PPTM Files to POT Using Python
url: /python-net/merge/pptm-to-pot/
keywords: Merge PPTM to POT, Join PPTM to POT, Combine PPTM to POT, PowerPoint, Presentation, POT, Python, Aspose
description: Merge multiple PPTM files and save the combined presentation as a POT file using Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PPTM Files into a POT File in Python" h2="Use Aspose.Slides for Python via .NET to combine PPTM presentations and save the merged slides as a POT file without Microsoft PowerPoint." >}}

{{% blocks/products/pf/feature-page-section h2="Merge PPTM to POT in Python" %}}

[**Aspose.Slides for Python via .NET**](/slides/python-net/) lets you combine PPTM presentations by cloning slides from a source presentation into a destination presentation. The [`SlideCollection.add_clone`](https://reference.aspose.com/slides/python-net/aspose.slides/slidecollection/add_clone/) method copies each slide and its associated layout and master data as needed, preserving the source slide's appearance. After adding the slides, use `Presentation.save` with `SaveFormat.POT` to create a single POT file.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge PPTM files to POT using Python" %}}
Open the destination and source PPTM files, clone each source slide into the destination presentation, and then save the result in POT format.

{{% blocks/products/pf/agp/code-block title="Python code to merge multiple PPTM files into one POT file" offSpacer="true" %}}

```python
with slides.Presentation("presentation1.pptm") as destination_presentation:
    with slides.Presentation("presentation2.pptm") as source_presentation:
        for source_slide in source_presentation.slides:
            destination_presentation.slides.add_clone(source_slide)

    destination_presentation.save("merged.pot", slides.export.SaveFormat.POT)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge PPTM to POT using Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge two PPTM files and save the result as a POT file in Python." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via .NET**](/slides/python-net/) with `pip install aspose.slides`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides` package and assign it the `slides` alias in your Python source file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Open one PPTM file as the destination `Presentation` and the other as the source `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Iterate through the source slides and add each slide to the destination by calling [`SlideCollection.add_clone`](https://reference.aspose.com/slides/python-net/aspose.slides/slidecollection/add_clone/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save` with the output file name and `SaveFormat.POT` to create the merged POT file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Export PPTM to Other Supported Formats" subTitle="You can also combine PPTM files and save the result in any of the formats listed below." >}}

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
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-potm/" name="PPTM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-potx/" name="PPTM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-pps/" name="PPTM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-ppsm/" name="PPTM TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-ppsx/" name="PPTM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-svg/" name="PPTM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-tiff/" name="PPTM TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pptm-to-xps/" name="PPTM TO XPS" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
