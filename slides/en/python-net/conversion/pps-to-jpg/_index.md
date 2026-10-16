---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPS to JPG in Python
weight: 1600
url: /python-net/conversion/pps-to-jpg/
keywords: "Convert, PowerPoint, PPS, JPG, Presentation, Python"
description: Sample Python code for PPS-to-JPG conversion. Use the PowerPoint Python API to convert PPS slides to JPG images in batch.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPS to JPG in Python" h2="Powerful PowerPoint Python library for converting PPS to JPG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/python-net/"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPS to JPG in Python" %}}

Convert PPS slides to JPG images programmatically with [*Aspose.Slides for Python via .NET*](/slides/python-net/). A few lines of Python code are enough to load a PowerPoint Slide Show, render each slide, and save the resulting images in JPEG format.

Aspose.Slides for Python via .NET is a presentation-processing API that renders PPS slides as JPG images quickly and with high fidelity. Try the conversion in the free [online app](https://products.aspose.app/slides/conversion). The library also supports many other output formats.

You can install the library from [PyPI](https://pypi.org/project/aspose-slides/) using the following pip command:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
pip install aspose-slides
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Save PPS as JPG in Python" %}}

Use the free [online conversion app](https://products.aspose.app/slides/conversion) to see the PPS-to-JPG conversion process in action.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Convert PPS to JPG in Python" >}}
```python
image_scale = 2

with slides.Presentation("presentation.pps") as presentation:
    for slide in presentation.slides:
        file_path = "presentation_slide_{0}.jpg".format(slide.slide_number)

        with slide.get_image(image_scale, image_scale) as slide_image:
            slide_image.save(file_path, slides.ImageFormat.JPEG)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PPS to JPG in Python" intro="These are the steps to convert a PPS file to JPG using Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPS file into a `Presentation` instance.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through `Presentation.slides` and call `Slide.get_image` for each slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `IImage.save` with an output file path and `ImageFormat.JPEG`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the Python conversion example, make sure your environment meets these requirements." %}}

- A supported Windows, Linux, or macOS environment; see [System Requirements](https://docs.aspose.com/slides/python-net/system-requirements/).
- Python 3.5 or later.
- Aspose.Slides for Python via .NET installed in your environment.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert PPS to many other file formats. See other supported conversions below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
