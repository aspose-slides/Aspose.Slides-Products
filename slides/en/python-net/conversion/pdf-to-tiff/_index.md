---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to TIFF in Python
url: /python-net/conversion/pdf-to-tiff/
keywords: PDF to TIFF, Convert PDF to TIFF, Python API, Python Library, PDF, TIFF
description: Convert PDF files to multipage TIFF images in Python. Use the Aspose.Slides Python API to import PDF pages and export the presentation as TIFF.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to TIFF in Python" h2="Import PDF pages and save them as a multipage TIFF image with a cross-platform Python library" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to TIFF using Python" variant="code" %}}

Create a `Presentation`, remove its default blank slide, import the PDF pages with `SlideCollection.add_from_pdf`, and save the result with `SaveFormat.TIFF`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PDF into TIFF" >}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("document.tiff", slides.export.SaveFormat.TIFF)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to TIFF in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you convert PDF files to multipage TIFF images programmatically. The API imports each PDF page as a slide with `SlideCollection.add_from_pdf`, then writes all slides to a TIFF file with `Presentation.save`.

The conversion requires no Microsoft PowerPoint, Adobe Acrobat, or other presentation software. Each imported PDF page becomes one frame in the resulting TIFF image.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PDF to TIFF Using Aspose.Slides for Python" intro="These are the steps to convert PDF to TIFF in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and remove its default blank slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the source PDF by using `SlideCollection.add_from_pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the presentation by using `Presentation.save` with `SaveFormat.TIFF`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF and save it in other file formats. See the supported formats below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
