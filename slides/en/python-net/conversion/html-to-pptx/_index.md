---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert HTML to PPTX in Python
url: /python-net/conversion/html-to-pptx/
keywords: Convert HTML to PPTX, HTML to PPTX, PowerPoint, HTML, PPTX, Python API, Python Library
description: Convert HTML content to PPTX in Python. Use the Aspose.Slides Python API to import HTML and save the generated slides as a PowerPoint presentation.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert HTML to PPTX in Python" h2="Import HTML content and save it as a PPTX presentation with a cross-platform Python API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert HTML to PPTX in Python" variant="code" %}}

Create a `Presentation`, remove its default blank slide, import the HTML file, and save the generated slides as a PPTX presentation.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting HTML to PPTX" >}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)

    with open("page.html", "rb") as html_stream:
        presentation.slides.add_from_html(html_stream)

    presentation.save("output.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert HTML to PPTX using Aspose.Slides" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you import supported HTML content into editable PowerPoint slides. Use `SlideCollection.add_from_html` to create slides from an HTML document, then call `Presentation.save` with `SaveFormat.PPTX` to write the result in the modern Office Open XML presentation format.

The generated presentation can contain text, images, and basic formatting imported from the HTML source. This workflow does not require Microsoft PowerPoint or another presentation application.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert HTML to PPTX in Python" intro="These are the steps to convert HTML to PPTX in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides` package in your Python module.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and remove its default blank slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source HTML file and pass its stream to `SlideCollection.add_from_html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Presentation.save` with the output file path and `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported PowerPoint Conversions" subTitle="You can also convert files in other formats to PowerPoint." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
