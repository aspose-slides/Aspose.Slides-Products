---
title: Merge PDF Files in Python
url: /python-net/merge/pdf/
keywords: Merge PDF, Join PDF, Combine PDF, PDF Files, Python API, Python Library
description: Merge PDF files in Python by importing their pages as slides and exporting the combined content as a PDF document.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PDF Files in Python" h2="Import pages from multiple PDF files and export the combined content as one PDF document with Python" >}}

{{% blocks/products/pf/feature-page-section h2="Merge PDF in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you combine PDF files by importing their pages into a `Presentation`. `SlideCollection.add_from_pdf` converts each PDF page into a slide and appends it to the presentation.

After all source files are imported, call `Presentation.save` with `SaveFormat.PDF` to export the slides as one PDF document. Microsoft PowerPoint and Adobe Acrobat are not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge PDF files using Python" %}}
Create a presentation without its default blank slide, import the source PDF files in the required order, and export the combined slides as one PDF document.

{{% blocks/products/pf/agp/code-block title="Python code for merging PDF files" offSpacer="true" %}}


```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document1.pdf")
    presentation.slides.add_from_pdf("document2.pdf")

    presentation.save("merged.pdf", slides.export.SaveFormat.PDF)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge PDF using Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to merge PDF files in Python." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create an empty `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Remove the default blank slide from the presentation.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Pass each source PDF file to `SlideCollection.add_from_pdf` in the required order.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save` with the output file path and `SaveFormat.PDF`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Export PDF to Other Supported Formats" subTitle="You can also combine PDF files and save the imported pages in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/pdf-to-xps/" name="PDF TO XPS" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
