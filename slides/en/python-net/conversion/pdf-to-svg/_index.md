---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to SVG in Python
url: /python-net/conversion/pdf-to-svg/
keywords: PDF to SVG, Convert PDF to SVG, Python API, Python Library, PDF, SVG
description: Convert PDF pages to SVG images in Python. Use the Aspose.Slides Python API to import PDF pages and render each slide as scalable vector graphics.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to SVG in Python" h2="Import PDF pages and render them as scalable vector graphics with a cross-platform Python library" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to SVG using Python" variant="code" %}}

Create a `Presentation`, remove its default blank slide, import the PDF pages with `SlideCollection.add_from_pdf`, and call `Slide.write_as_svg` for each slide.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PDF into SVG" >}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")

    for slide in presentation.slides:
        file_path = f"slide_{slide.slide_number}.svg"
        with open(file_path, "wb") as output_stream:
            slide.write_as_svg(output_stream)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to SVG in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you convert PDF pages to SVG images programmatically. The API imports each PDF page as a slide with `SlideCollection.add_from_pdf`, then renders each slide by using `Slide.write_as_svg`.

SVG is a vector format, so every PDF page is written to a separate scalable image file. The conversion requires no Microsoft PowerPoint, Adobe Acrobat, or other presentation software.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PDF to SVG Using Aspose.Slides for Python" intro="These are the steps to convert PDF to SVG in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and remove its default blank slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the source PDF by using `SlideCollection.add_from_pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access each slide through a `Slide` variable and call `Slide.write_as_svg` with an output stream.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF and save it in other file formats. See the supported formats below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
