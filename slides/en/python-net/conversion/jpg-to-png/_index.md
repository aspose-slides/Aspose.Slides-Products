---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert JPG to PNG in Python
url: /python-net/conversion/jpg-to-png/
keywords: JPG to PNG, Convert JPG to PNG, Python API, Python Library, JPG, PNG
description: Convert JPG images to PNG in Python. Use the Aspose.Slides Python API to load a JPEG file and save it as a PNG image.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert JPG to PNG in Python" h2="Convert JPG images to PNG files with a cross-platform Python API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert JPG to PNG Using Python" variant="code" %}}

Load the JPG file as an `IImage` and save it in PNG format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting JPG to PNG" >}}
```python
with slides.Images.from_file("image.jpg") as image:
    image.save("image.png", slides.ImageFormat.PNG)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert JPG to PNG in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) provides image I/O operations that let you load a JPG file and save it as a PNG image. Use `Images.from_file` to create an `IImage` object, then call `IImage.save` with `ImageFormat.PNG`.

The conversion changes the image encoding from JPEG to PNG. It does not require Microsoft PowerPoint or another presentation application.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert JPG to PNG Using the Aspose.Slides Python API" intro="Follow these steps to convert JPG to PNG in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides` package in your Python module.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the JPG file by using `Images.from_file`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `IImage.save` with the output file path and `ImageFormat.PNG`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert JPG to Other Supported Formats" subTitle="You can also convert JPG files and save them in other supported formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
