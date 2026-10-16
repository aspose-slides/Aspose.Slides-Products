---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to HTML in Python
url: /python-net/conversion/pdf-to-html/
keywords: PDF to HTML, Convert PDF to HTML, Python API, Python Library, PDF, HTML
description: Convert PDF files to HTML in Python. Use the Aspose.Slides Python API to import PDF pages and publish them as a self-contained HTML document.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to HTML in Python" h2="Import PDF pages and publish them as HTML with a cross-platform Python API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to HTML using Python" variant="code" %}}

Create a `Presentation`, remove its default blank slide, import the PDF pages, and save the presentation with `SaveFormat.HTML`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PDF into HTML" >}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("document.html", slides.export.SaveFormat.HTML)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to HTML in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you import PDF pages into a presentation and publish the result as HTML. The API provides `SlideCollection.add_from_pdf` for importing PDF content and `Presentation.save` with `SaveFormat.HTML` for creating the output document.

Each PDF page becomes a slide in the presentation before the presentation is exported as a self-contained HTML file. This workflow does not require Microsoft PowerPoint, Adobe Acrobat, or another presentation application.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PDF to HTML Using the Aspose.Slides Python API" intro="These are the steps to convert PDF to HTML in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and remove its default blank slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the source PDF by using `SlideCollection.add_from_pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Presentation.save` with the output path and `SaveFormat.HTML`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF documents to other supported formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
