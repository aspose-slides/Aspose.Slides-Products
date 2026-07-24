---
title: Convert Image to JPG in Python
url: /python-net/conversion/image-to-jpg/
keywords: Image to JPG, Convert Image to JPG, Python API, Python Library, Image, JPG
description: Convert images to JPG in Python. Use the Aspose.Slides Python API to load a raster image and save it as a JPEG file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert Image to JPG in Python" h2="Convert raster images to JPG files with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Convert Image to JPG in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) provides image I/O operations that let you load a supported raster image and save it as a JPG file. Use `Images.from_file` to create an `IImage` object, then call `IImage.save` with `ImageFormat.JPEG`.

The conversion works with common source formats such as PNG, BMP, GIF, and TIFF. It does not require Microsoft PowerPoint or another presentation application.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert an Image to JPG Using Python" %}}
Load the source image as an `IImage` and save it in JPEG format.

{{% blocks/products/pf/agp/code-block title="Python code for converting an image to JPG" offSpacer="true" %}}

```python
with slides.Images.from_file("image.png") as image:
    image.save("image.jpg", slides.ImageFormat.JPEG)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Convert an Image to JPG Using the Aspose.Slides Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert an image to JPG in Python." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides` package in your Python module.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source image by using `Images.from_file`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `IImage.save` with the output file path and `ImageFormat.JPEG`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Convert Images to Other Supported Formats" subTitle="You can also convert images and save them in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
