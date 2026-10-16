---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to XML in Python
url: /python-net/conversion/pdf-to-xml/
keywords: PDF to XML, Convert PDF to XML, Python API, Python Library, PDF, XML
description: Convert PDF to XML in Python. Use the Aspose.Slides Python API to import PDF pages and save them as a PowerPoint XML Presentation.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to XML in Python" h2="Import PDF pages and save them in the PowerPoint XML Presentation format with a cross-platform Python API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to XML using Python" variant="code" %}}

Create a `Presentation`, remove its default blank slide, import the PDF pages, and save the presentation in the PowerPoint XML Presentation format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PDF into XML" >}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("document.xml", slides.export.SaveFormat.XML)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to XML in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you import PDF pages into a presentation and save the result as a PowerPoint XML Presentation. Use `SlideCollection.add_from_pdf` to create slides from the PDF pages, then call `Presentation.save` with `SaveFormat.XML`.

The output is a single XML presentation file that contains the imported pages as slides. This workflow does not require Microsoft PowerPoint, Adobe Acrobat, or another presentation application.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PDF to XML Using the Aspose.Slides Python API" intro="These are the steps to convert PDF to XML in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and remove its default blank slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the source PDF by using `SlideCollection.add_from_pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Presentation.save` with the output file path and `SaveFormat.XML`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF documents to other supported formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
