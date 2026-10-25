---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Extract Text from PPTX Files with Python
url: /python-net/parser/pptx/
keywords: parse PPTX with Python, PPTX parser Python, extract data from PPTX in Python, extract text from PPTX with Python
description: Extract text and text formatting details from PPTX presentations with Python.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Extract Text from PPTX Presentations with Python" h2="Build Python applications that extract text and text formatting details from PowerPoint presentations with Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Extract Text from a PPTX Presentation with Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/python-net/) provides the [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) static method on `SlideUtil`. It returns the `TextFrame` objects from an entire presentation and can include text from master slides. The following example extracts text and related font details from a PPTX presentation.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Extract Text from a PPTX Presentation - Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.pptx") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Extract Text from PPTX with Python" intro="Follow these steps to extract text from a PPTX file." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the PPTX file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `SlideUtil.get_all_text_frames` and specify whether to include master slides.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through the returned `TextFrame` objects.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through each text frame's `paragraphs` collection.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through each paragraph's `portions` collection.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Read the current portion's `text` and formatting properties.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Parsing Formats" subTitle="Use Python to extract text from other supported presentation formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/parser/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
