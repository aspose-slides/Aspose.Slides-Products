---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert HTML to PNG in Python
url: /python-net/conversion/html-to-png/
keywords: HTML to PNG, Convert HTML to PNG, Python API, Python Library, HTML, PNG
description: Convert HTML content to PNG images in Python. Use the Aspose.Slides Python API to import HTML and render each generated slide as a PNG image.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert HTML to PNG in Python" h2="Import HTML content and render it as PNG images with a cross-platform Python API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert HTML to PNG using Python" variant="code" %}}

Create a `Presentation`, remove its default blank slide, import the HTML file, and render each generated `Slide` as a PNG image.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting HTML into PNG" >}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)

    with open("page.html", "rb") as html_stream:
        presentation.slides.add_from_html(html_stream)

    for slide in presentation.slides:
        file_path = f"slide_{slide.slide_number}.png"
        with slide.get_image(1, 1) as slide_image:
            slide_image.save(file_path, slides.ImageFormat.PNG)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert HTML to PNG in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you import HTML content into a presentation and render the resulting slides as PNG images. The API provides `SlideCollection.add_from_html` for importing HTML and `Slide.get_image` for rendering each slide.

The example below writes one PNG file for each slide created from the HTML document. This workflow does not require Microsoft PowerPoint or another presentation application.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert HTML to PNG using Aspose.Slides for Python API" intro="These are the steps to convert HTML to PNG in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and remove its default blank slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source HTML file and pass its stream to `SlideCollection.add_from_html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access each imported `Slide`, call `Slide.get_image`, and save the result with `ImageFormat.PNG`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert HTML to Other Supported Formats" subTitle="You can also import HTML content and save it in other supported formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
