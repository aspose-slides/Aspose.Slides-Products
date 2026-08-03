---
title: Search Text in PPT Presentations with Python
url: /python-net/search/ppt/
keywords: search text in PPT, find words in PPT, search PPT presentation with Python
description: Search for text in PPT presentations with Python and Aspose.Slides.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Search Text in PPT Presentations with Python" h2="Build Python applications that find text in PowerPoint presentations with Aspose.Slides." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides" subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Search Text in a PPT Presentation with Python" %}}
With [Aspose.Slides for Python via .NET](/slides/python-net/), you can use [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) to find text frames on each slide that contain a specified string.
{{% blocks/products/pf/agp/code-block title="Search Text in a PPT Presentation - Python" offSpacer="true" %}}

```python
with slides.Presentation("presentation.ppt") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Search Text in PPT via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to search for text in a PPT presentation." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the PPT file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Iterate through the slides and call [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) for each one.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Read the `text` property of each matching text frame.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Search" sectionDescription="Search for text in PPT presentations online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Search Formats" subTitle="Use Python to search for text in other supported presentation formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
