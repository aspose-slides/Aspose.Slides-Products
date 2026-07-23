---
title: Convert JPG to Image in Python
url: /python-net/conversion/jpg-to-image/
keywords: JPG to Image, Convert JPG to Image, Python API, Python Library, JPG, Image
description: Convert JPG to image in Python. Use the Aspose.Slides Python API to load a JPEG file and save it in another supported image format.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert JPG to Image in Python" h2="Convert JPG files to other image formats with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Convert JPG to Image in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) provides image I/O operations that let you load a JPG file and save it in another supported raster format. Use `Images.from_file` to create an `IImage` object, then call `IImage.save` with the required `ImageFormat` value.

The example below converts a JPEG image to PNG. You can produce BMP, GIF, TIFF, or another supported format by changing the output extension and the `ImageFormat` value.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JPG to an Image Using Python" %}}
Load the JPG file as an `IImage` and save it in the required image format.

{{% blocks/products/pf/agp/code-block title="Python code for converting JPG to an image" offSpacer="true" %}}

```python
with slides.Images.from_file("image.jpg") as image:
    image.save("image.png", slides.ImageFormat.PNG)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Convert JPG to an Image Using the Aspose.Slides Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert JPG to an image in Python." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides` package in your Python module.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the JPG file by using `Images.from_file`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `IImage.save` with the output file path and the required `ImageFormat` value.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Convert JPG to Other Supported Formats" subTitle="You can also convert JPG files and save them in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
