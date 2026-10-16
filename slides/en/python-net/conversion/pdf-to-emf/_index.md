---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to EMF in Python
weight: 680
url: /python-net/conversion/pdf-to-emf/
keywords: "Convert, PowerPoint, PDF, EMF, Presentation, Python"
description: Convert PDF pages to EMF files in Python. Use the Aspose.Slides Python API to import a PDF and export each page as an Enhanced Metafile.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to EMF in Python" h2="Python API for converting PDF pages to EMF files"
  apiReferenceLink="https://reference.aspose.com/slides/python-net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family/"
  downloadLink="https://releases.aspose.com/slides/python-net/"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to EMF in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you convert PDF pages to EMF files programmatically. Import the PDF pages into a `Presentation` by using `SlideCollection.add_from_pdf`, then export each imported slide by using `Slide.write_as_emf`.

This workflow creates one EMF file for each page in the source PDF. You can test the conversion in your [browser](https://products.aspose.app/pdf/conversion/pdf-to-emf) or use the Python API in your application.

Install the library from [PyPI](https://pypi.org/project/aspose-slides/) by using the following command:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
pip install aspose-slides
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Save PDF as EMF in Python" %}}

Use the [free online app](https://products.aspose.app/pdf/conversion/pdf-to-emf) to see the PDF-to-EMF conversion process in action.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="This sample code shows how to convert PDF to EMF in Python" >}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")

    for slide in presentation.slides:
        file_path = f"document_page_{slide.slide_number}.emf"
        with open(file_path, "wb") as output_stream:
            slide.write_as_emf(output_stream)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PDF to EMF in Python" intro="Follow these steps to convert a PDF file to EMF using Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation`, remove its default slide, and import the PDF by using `SlideCollection.add_from_pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through `Presentation.slides` and open a binary output stream for each imported page.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Write each slide to its output stream by using `Slide.write_as_emf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the Python conversion sample, make sure your environment meets these requirements." %}}

- Microsoft Windows, macOS, or 64-bit Linux (see the [system requirements](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.6 or later for this sample.
- Aspose.Slides for Python via .NET installed in your environment.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert PDF documents to many other file formats. See the supported conversions below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
