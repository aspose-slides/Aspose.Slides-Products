---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTM to SVG in Python
weight: 2610
url: /python-net/conversion/pptm-to-svg/
keywords: "Convert, PowerPoint, PPTM, SVG, Presentation, Python"
description: Convert PPTM presentation slides to SVG images in Python. Use the Aspose.Slides Python API to export each slide as a separate scalable vector graphic.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTM to SVG in Python" h2="Python API for converting PPTM presentation slides to SVG images"
  apiReferenceLink="https://reference.aspose.com/slides/python-net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family/"
  downloadLink="https://releases.aspose.com/slides/python-net/"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to SVG in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you convert PPTM presentation slides to SVG images programmatically. Load the presentation, iterate through its slides, and call `Slide.write_as_svg` for each slide.

SVG is a resolution-independent vector format suitable for web pages and scalable graphics. Each slide is exported to a separate SVG file. You can test the conversion in your [browser](https://products.aspose.app/slides/conversion) or use the Python API in your application.

Install the library from [PyPI](https://pypi.org/project/aspose-slides/) by using the following command:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
pip install aspose-slides
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Save PPTM as SVG in Python" %}}

Use the [free online app](https://products.aspose.app/slides/conversion) to see the PPTM-to-SVG conversion process in action.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="This sample code shows how to convert PPTM to SVG in Python" >}}
```python
with slides.Presentation("presentation.pptm") as presentation:
    for slide in presentation.slides:
        file_path = f"presentation_slide_{slide.slide_number}.svg"
        with open(file_path, "wb") as output_stream:
            slide.write_as_svg(output_stream)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PPTM to SVG in Python" intro="Follow these steps to convert a PPTM file to SVG using Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPTM file into a `Presentation` instance.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through `Presentation.slides` and open a binary output stream for each SVG file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Slide.write_as_svg` to write each slide to its output stream.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the Python conversion sample, make sure your environment meets these requirements." %}}

- Microsoft Windows, macOS, or 64-bit Linux (see the [system requirements](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.6 or later for this sample.
- Aspose.Slides for Python via .NET installed in your environment.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert PPTM presentations to many other file formats. See the supported conversions below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
