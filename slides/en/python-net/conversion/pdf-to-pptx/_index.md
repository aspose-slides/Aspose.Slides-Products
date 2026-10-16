---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to PPTX in Python
url: /python-net/conversion/pdf-to-pptx/
keywords: PDF to PPTX, Convert PDF to PPTX, Python API, Python Library, PDF, PPTX
description: Convert PDF files to PPTX presentations in Python. Use the Aspose.Slides Python API to import PDF pages and save them in PowerPoint Open XML format.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to PPTX in Python" h2="Import PDF pages and save them as a PowerPoint Open XML presentation with a cross-platform Python library" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to PPTX using Python" variant="code" %}}

Create a `Presentation`, remove its default blank slide, import the PDF pages with `SlideCollection.add_from_pdf`, and save the result with `SaveFormat.PPTX`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PDF into PPTX" >}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to PPTX in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you convert PDF files to PPTX presentations programmatically. The API imports each PDF page as a slide with `SlideCollection.add_from_pdf`, then writes the presentation in PowerPoint Open XML format.

The conversion requires no Microsoft PowerPoint, Adobe Acrobat, or other presentation software. See the [presentation import guide](https://docs.aspose.com/slides/python-net/import-presentation/) for more details.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PDF to PPTX Using Aspose.Slides for Python" intro="These are the steps to convert PDF to PPTX in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and remove its default blank slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the source PDF by using `SlideCollection.add_from_pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the presentation by using `Presentation.save` with `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF and save it in other file formats. See the supported formats below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
