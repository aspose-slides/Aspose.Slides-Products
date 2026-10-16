---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert HTML to TIFF in Python
url: /python-net/conversion/html-to-tiff/
keywords: HTML to TIFF, Convert HTML to TIFF, Python API, Python Library, HTML, TIFF
description: Convert HTML content to TIFF in Python. Use the Aspose.Slides Python API to import HTML and export the generated slides as a multipage TIFF image.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert HTML to TIFF in Python" h2="Import HTML content and export it as a multipage TIFF image with a cross-platform Python API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert HTML to TIFF using Python" variant="code" %}}

Create a `Presentation`, remove its default blank slide, import the HTML file, and save the generated slides as a multipage TIFF image.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting HTML into TIFF" >}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)

    with open("page.html", "rb") as html_stream:
        presentation.slides.add_from_html(html_stream)

    presentation.save("output.tiff", slides.export.SaveFormat.TIFF)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert HTML to TIFF in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you import HTML content into a presentation and export the resulting slides as a multipage TIFF image. The API provides `SlideCollection.add_from_html` for importing HTML and `Presentation.save` with `SaveFormat.TIFF` for creating the output file.

Each generated slide becomes a separate frame in the TIFF file. This workflow does not require Microsoft PowerPoint or another presentation application.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert HTML to TIFF using Aspose.Slides for Python API" intro="These are the steps to convert HTML to TIFF in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and remove its default blank slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source HTML file and pass its stream to `SlideCollection.add_from_html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Presentation.save` with the output file path and `SaveFormat.TIFF`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert HTML to Other Supported Formats" subTitle="You can also import HTML content and save it in other supported formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
