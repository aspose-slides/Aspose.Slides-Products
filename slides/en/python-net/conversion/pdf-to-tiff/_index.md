---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to TIFF in Python
url: /python-net/conversion/pdf-to-tiff/
keywords: PDF to TIFF, Convert PDF to TIFF, Python API, Python Library, PDF, TIFF
description: Convert PDF files to multipage TIFF images in Python. Use the Aspose.Slides Python API to import PDF pages and export the presentation as TIFF.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PDF to TIFF in Python" h2="Import PDF pages and save them as a multipage TIFF image with a cross-platform Python library" >}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to TIFF in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you convert PDF files to multipage TIFF images programmatically. The API imports each PDF page as a slide with `SlideCollection.add_from_pdf`, then writes all slides to a TIFF file with `Presentation.save`.

The conversion requires no Microsoft PowerPoint, Adobe Acrobat, or other presentation software. Each imported PDF page becomes one frame in the resulting TIFF image.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to TIFF using Python" %}}
Create a `Presentation`, remove its default blank slide, import the PDF pages with `SlideCollection.add_from_pdf`, and save the result with `SaveFormat.TIFF`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PDF into TIFF" offSpacer="true" %}}

```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("document.tiff", slides.export.SaveFormat.TIFF)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Convert PDF to TIFF Using Aspose.Slides for Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PDF to TIFF in Python." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and remove its default blank slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the source PDF by using `SlideCollection.add_from_pdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the presentation by using `Presentation.save` with `SaveFormat.TIFF`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF and save it in other file formats. See the supported formats below:" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
