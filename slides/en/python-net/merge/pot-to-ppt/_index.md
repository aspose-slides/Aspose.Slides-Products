---
title: Merge POT Files to PPT with Python
url: /python-net/merge/pot-to-ppt/
keywords: Merge POT to PPT, Join POT to PPT, Combine POT to PPT, PowerPoint, Presentation, PPT, Python, Aspose
description: Merge multiple POT files in Python and save the combined presentation as a PPT file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge POT Files to PPT in Python" h2="Combine POT presentations and save the result as PPT with Aspose.Slides for Python via .NET—no Microsoft PowerPoint or OpenOffice installation required." >}}

{{% blocks/products/pf/feature-page-section h2="Merge POT to PPT in Python" %}}

[**Aspose.Slides for Python via .NET**](/slides/python-net/) lets you merge multiple POT files by cloning slides from each source file into a destination `Presentation`. The `add_clone` method appends a copy of each slide while preserving its content, layout, and styling. You can then save the combined presentation in `PPT` format.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge POT files to PPT using Python" %}}
Open the first POT file as the destination `Presentation`, open the second file as the source, and pass each source slide to `add_clone`.

{{% blocks/products/pf/agp/code-block title="Python code to merge multiple POT files into one PPT file" offSpacer="true" %}}

```python
with slides.Presentation("first.pot") as destination_presentation:
    with slides.Presentation("second.pot") as source_presentation:
        for slide in source_presentation.slides:
            destination_presentation.slides.add_clone(slide)

    destination_presentation.save("merged.ppt", slides.export.SaveFormat.PPT)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Merge POT Files to PPT with Aspose.Slides for Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge two POT files and save the result as PPT in Python." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via .NET**](/slides/python-net/) with `pip`.
```bash
pip install aspose.slides
```
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the first POT file as the destination `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the second POT file as the source `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
For each source slide, call [`add_clone`](https://reference.aspose.com/slides/python-net/aspose.slides/slidecollection/add_clone/) on the destination presentation's `slides` collection.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.PPT` to write the merged presentation to a PPT file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Save Merged POT Files in Other Supported Formats" subTitle="You can also combine POT files and save the result in any of the formats listed below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-pptx/" name="POT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-pdf/" name="POT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-html/" name="POT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-png/" name="POT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pot-to-bmp/" name="POT TO BMP" >}}
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
