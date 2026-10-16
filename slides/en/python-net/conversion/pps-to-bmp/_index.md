---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPS to BMP in Python
weight: 1550
url: /python-net/conversion/pps-to-bmp/
keywords: "Convert, PowerPoint, PPS, BMP, Presentation, Python"
description: Convert PPS slide shows to BMP images in Python. Use the Aspose.Slides Python API to render each slide as a separate BMP file.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPS to BMP in Python" h2="Python API for converting PPS slide shows to BMP images"
  apiReferenceLink="https://reference.aspose.com/slides/python-net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family/"
  downloadLink="https://releases.aspose.com/slides/python-net/"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPS to BMP in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you convert PPS slide shows to BMP images programmatically. Load the slide show, render each slide with `Slide.get_image`, and save the resulting `IImage` object in BMP format.

The API preserves slide content and formatting during rendering. You can test the conversion in your [browser](https://products.aspose.app/slides/conversion/pps-to-bmp) or use the Python API to process slide shows in your application.

Install the library from [PyPI](https://pypi.org/project/aspose-slides/) by using the following command:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
pip install aspose-slides
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Save PPS as BMP in Python" %}}

Use the [free online app](https://products.aspose.app/slides/conversion/pps-to-bmp) to see the PPS-to-BMP conversion process in action.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="This sample code shows how to convert PPS to BMP in Python" >}}
```python
image_scale = 2

with slides.Presentation("presentation.pps") as presentation:
    for slide in presentation.slides:
        file_path = f"presentation_slide_{slide.slide_number}.bmp"
        with slide.get_image(image_scale, image_scale) as slide_image:
            slide_image.save(file_path, slides.ImageFormat.BMP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PPS to BMP in Python" intro="Follow these steps to convert a PPS file to BMP using Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPS file into a `Presentation` instance.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through `Presentation.slides` and render each slide by using `Slide.get_image`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save each rendered image by using `IImage.save` with `ImageFormat.BMP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the Python conversion sample, make sure your environment meets these requirements." %}}

- Microsoft Windows, macOS, or 64-bit Linux (see the [system requirements](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.6 or later for this sample.
- Aspose.Slides for Python via .NET installed in your environment.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert PPS slide shows to many other file formats. See the supported conversions below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
