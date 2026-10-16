---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert JPG to Image in Python
url: /python-net/conversion/jpg-to-image/
keywords: JPG to Image, Convert JPG to Image, Python API, Python Library, JPG, Image
description: Convert JPG to image in Python. Use the Aspose.Slides Python API to load a JPEG file and save it in another supported image format.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert JPG to Image in Python" h2="Convert JPG files to other image formats with a cross-platform Python API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert JPG to an Image Using Python" variant="code" %}}

Load the JPG file as an `IImage` and save it in the required image format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting JPG to an image" >}}
```python
with slides.Images.from_file("image.jpg") as image:
    image.save("image.png", slides.ImageFormat.PNG)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert JPG to Image in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) provides image I/O operations that let you load a JPG file and save it in another supported raster format. Use `Images.from_file` to create an `IImage` object, then call `IImage.save` with the required `ImageFormat` value.

The example below converts a JPEG image to PNG. You can produce BMP, GIF, TIFF, or another supported format by changing the output extension and the `ImageFormat` value.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert JPG to an Image Using the Aspose.Slides Python API" intro="Follow these steps to convert JPG to an image in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides` package in your Python module.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the JPG file by using `Images.from_file`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `IImage.save` with the output file path and the required `ImageFormat` value.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert JPG to Other Supported Formats" subTitle="You can also convert JPG files and save them in other supported formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
