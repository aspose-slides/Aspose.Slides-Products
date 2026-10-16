---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to XPS in Python
weight: 880
url: /python-net/conversion/pdf-to-xps/
keywords: "Convert, PowerPoint, PDF, XPS, Presentation, Python"
description: Convert PDF to XPS in Python. Use the Aspose.Slides Python API to import PDF pages and save them as an XPS document.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to XPS in Python" h2="Import PDF pages and save them as XPS with a cross-platform Python library"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to XPS in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you convert PDF documents to XPS programmatically. Import the source pages with `SlideCollection.add_from_pdf`, then call `Presentation.save` with `SaveFormat.XPS`.

Each PDF page becomes a slide in the presentation before the complete presentation is exported as one XPS document. You can also test the conversion in the [online conversion app](https://products.aspose.app/slides/conversion).

Install the library from [PyPI](https://pypi.org/project/Aspose.Slides/) by using the following `pip` command:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
pip install aspose-slides
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Save PDF as XPS in Python" %}}

Use the free online app to see the PDF-to-XPS conversion process in action.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="This sample code shows PDF to XPS Python Conversion" >}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("presentation.xps", slides.export.SaveFormat.XPS)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PDF to XPS in Python" intro="These are the steps to convert a PDF file to XPS using Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and remove its default blank slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the source PDF by using `SlideCollection.add_from_pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Presentation.save` with the output file path and `SaveFormat.XPS`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the Python conversion example, make sure your environment meets these requirements." %}}

- Windows, macOS, or a supported 64-bit Linux distribution. See the [system requirements](https://docs.aspose.com/slides/python-net/system-requirements/).
- Python 3.5 or later.
- Aspose.Slides for Python via .NET installed in your environment.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert PDF documents to other supported formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
