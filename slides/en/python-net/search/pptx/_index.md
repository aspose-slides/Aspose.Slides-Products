---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Search Text in PPTX Presentations with Python
url: /python-net/search/pptx/
keywords: search text in PPTX, find words in PPTX, search PPTX presentation with Python
description: Search for text in PPTX presentations with Python and Aspose.Slides.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Search Text in PPTX Presentations with Python" h2="Build Python applications that find text in PowerPoint presentations with Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Search Text in a PPTX Presentation with Python" variant="code" %}}

With [Aspose.Slides for Python via .NET](/slides/python-net/), you can use [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) to find text frames on each slide that contain a specified string.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Search Text in a PPTX Presentation - Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Search Text in PPTX via Python" intro="Follow these steps to search for text in a PPTX presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the PPTX file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through the slides and call [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) for each one.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Read the `text` property of each matching text frame.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Search Formats" subTitle="Use Python to search for text in other supported presentation formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
