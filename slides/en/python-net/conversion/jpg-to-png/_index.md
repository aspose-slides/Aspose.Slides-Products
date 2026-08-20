---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert JPG to PNG in Python
url: /python-net/conversion/jpg-to-png/
keywords: JPG to PNG, Convert JPG to PNG, Python API, Python Library, JPG, PNG
description: Convert JPG images to PNG in Python. Use the Aspose.Slides Python API to load a JPEG file and save it as a PNG image.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert JPG to PNG in Python" h2="Convert JPG images to PNG files with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Convert JPG to PNG in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) provides image I/O operations that let you load a JPG file and save it as a PNG image. Use `Images.from_file` to create an `IImage` object, then call `IImage.save` with `ImageFormat.PNG`.

The conversion changes the image encoding from JPEG to PNG. It does not require Microsoft PowerPoint or another presentation application.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JPG to PNG Using Python" %}}
Load the JPG file as an `IImage` and save it in PNG format.

{{% blocks/products/pf/agp/code-block title="Python code for converting JPG to PNG" offSpacer="true" %}}

```python
with slides.Images.from_file("image.jpg") as image:
    image.save("image.png", slides.ImageFormat.PNG)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Convert JPG to PNG Using the Aspose.Slides Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert JPG to PNG in Python." >}}

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
Call `IImage.save` with the output file path and `ImageFormat.PNG`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Convert JPG to Other Supported Formats" subTitle="You can also convert JPG files and save them in other supported formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
