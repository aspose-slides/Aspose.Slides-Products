---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POTM to PNG in Python
weight: 1200
url: /python-net/conversion/potm-to-png/
keywords: "Convert, PowerPoint, POTM, PNG, Presentation, Python"
description: Convert POTM slides to PNG images in Python with Aspose.Slides. Use the concise code example to automate POTM-to-PNG conversion.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert POTM to PNG in Python" h2="Python presentation library for converting POTM slides to PNG images"
  apiReferenceLink="https://reference.aspose.com/slides/python-net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/python-net/"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTM to PNG in Python" %}}

Use [*Aspose.Slides for Python via .NET*](/slides/python-net/) to convert POTM slides to PNG images programmatically. Load a macro-enabled PowerPoint template with `Presentation`, render each `Slide` by calling `get_image`, and save the result with `ImageFormat.PNG`.

Aspose.Slides performs the conversion without requiring Microsoft PowerPoint. You can evaluate POTM-to-PNG output with the free [online conversion app](https://products.aspose.app/slides/conversion/potm-to-png). The same API supports many other presentation and image formats.

Install the package from [PyPI](https://pypi.org/project/aspose-slides/) using `pip`:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
pip install aspose-slides
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Save POTM as PNG in Python" %}}

Try the free [online conversion app](https://products.aspose.app/slides/conversion/potm-to-png) to see the POTM-to-PNG conversion process.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code to convert POTM slides to PNG images" >}}
```python
image_scale = 2

with slides.Presentation("presentation.potm") as presentation:
    for slide in presentation.slides:
        file_path = f"presentation_slide_{slide.slide_number}.png"
        with slide.get_image(image_scale, image_scale) as image:
            image.save(file_path, slides.ImageFormat.PNG)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert POTM to PNG in Python" intro="These are the steps to convert a POTM file to PNG using Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the POTM file into a `Presentation` instance.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through `Presentation.slides` and render each `Slide` by calling `get_image`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save each rendered image to a separate PNG file by using `ImageFormat.PNG`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the Python conversion example, make sure your environment meets these requirements." %}}

- Windows, 64-bit Linux, or macOS (see the [system requirements](https://docs.aspose.com/slides/python-net/system-requirements/))
- Python 3.6 or later for this sample.
- Aspose.Slides for Python via .NET installed in your environment

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert POTM to many other file formats. See the supported conversions below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
