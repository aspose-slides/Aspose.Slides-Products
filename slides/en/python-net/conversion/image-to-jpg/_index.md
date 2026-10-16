---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert Image to JPG in Python
url: /python-net/conversion/image-to-jpg/
keywords: Image to JPG, Convert Image to JPG, Python API, Python Library, Image, JPG
description: Convert images to JPG in Python. Use the Aspose.Slides Python API to load a raster image and save it as a JPEG file.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert Image to JPG in Python" h2="Convert raster images to JPG files with a cross-platform Python API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert an Image to JPG Using Python" variant="code" %}}

Load the source image as an `IImage` and save it in JPEG format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting an image to JPG" >}}
```python
with slides.Images.from_file("image.png") as image:
    image.save("image.jpg", slides.ImageFormat.JPEG)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert Image to JPG in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) provides image I/O operations that let you load a supported raster image and save it as a JPG file. Use `Images.from_file` to create an `IImage` object, then call `IImage.save` with `ImageFormat.JPEG`.

The conversion works with common source formats such as PNG, BMP, GIF, and TIFF. It does not require Microsoft PowerPoint or another presentation application.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert an Image to JPG Using the Aspose.Slides Python API" intro="Follow these steps to convert an image to JPG in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides` package in your Python module.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source image by using `Images.from_file`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `IImage.save` with the output file path and `ImageFormat.JPEG`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert Images to Other Supported Formats" subTitle="You can also convert images and save them in other supported formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
