---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to PPT in Python
url: /python-net/conversion/pdf-to-ppt/
keywords: PDF to PPT, Convert PDF to PPT, Python API, Python Library, PDF, PPT
description: Convert PDF files to PPT presentations in Python. Use the Aspose.Slides Python API to import PDF pages and save them in PowerPoint 97-2003 format.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to PPT in Python" h2="Import PDF pages and save them as a PowerPoint 97-2003 presentation with a cross-platform Python library" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to PPT using Python" variant="code" %}}

Create a `Presentation`, remove its default blank slide, import the PDF pages with `SlideCollection.add_from_pdf`, and save the result with `SaveFormat.PPT`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PDF into PPT" >}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to PPT in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you convert PDF files to PPT presentations programmatically. The API imports each PDF page as a slide with `SlideCollection.add_from_pdf`, then writes the presentation in the PowerPoint 97-2003 format.

The conversion requires no Microsoft PowerPoint, Adobe Acrobat, or other presentation software. You can also try the PDF-to-PPT workflow in the [online conversion app](https://products.aspose.app/slides/conversion).

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PDF to PPT Using Aspose.Slides for Python" intro="These are the steps to convert PDF to PPT in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and remove its default blank slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the source PDF by using `SlideCollection.add_from_pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the presentation by using `Presentation.save` with `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF and save it in other file formats. See the supported formats below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
