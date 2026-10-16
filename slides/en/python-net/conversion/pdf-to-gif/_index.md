---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to GIF in Python
weight: 700
url: /python-net/conversion/pdf-to-gif/
keywords: "Convert, PowerPoint, PDF, GIF, Presentation, Python"
description: Convert PDF files to animated GIFs in Python. Use the Aspose.Slides Python API to import PDF pages and export them as GIF frames.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to GIF in Python" h2="Python API for converting PDF pages to an animated GIF"
  apiReferenceLink="https://reference.aspose.com/slides/python-net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family/"
  downloadLink="https://releases.aspose.com/slides/python-net/"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to GIF in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you convert a PDF file to an animated GIF programmatically. Create a `Presentation`, import the PDF pages by using `SlideCollection.add_from_pdf`, and call `Presentation.save` with `SaveFormat.GIF`.

Each imported PDF page becomes a slide and then a frame in the output GIF. You can explore file conversion in your [browser](https://products.aspose.app/slides/conversion) or use the Python API in your application.

Install the library from [PyPI](https://pypi.org/project/aspose-slides/) by using the following command:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
pip install aspose-slides
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Save PDF as GIF in Python" %}}

Use the [free online converter](https://products.aspose.app/slides/conversion) to explore supported conversion options in your browser.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="This sample code shows how to convert PDF to GIF in Python" >}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("presentation.gif", slides.export.SaveFormat.GIF)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PDF to GIF in Python" intro="Follow these steps to convert a PDF file to GIF using Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and remove its default blank slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the PDF pages by using `SlideCollection.add_from_pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Presentation.save` with the output path and `SaveFormat.GIF`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the Python conversion sample, make sure your environment meets these requirements." %}}

- Microsoft Windows, macOS, or 64-bit Linux (see the [system requirements](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 or later.
- Aspose.Slides for Python via .NET installed in your environment.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert PDF documents to many other file formats. See the supported conversions below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
