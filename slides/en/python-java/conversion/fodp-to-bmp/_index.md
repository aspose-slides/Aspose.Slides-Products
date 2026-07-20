---
title: Convert FODP to BMP in Python
url: /python-java/conversion/fodp-to-bmp/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, FODP to BMP conversion, Python presentation library
description: Convert FODP presentation slides to BMP images in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert FODP Slides to BMP Images in Python" h2="Render every slide in an FODP presentation as a BMP image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert FODP to BMP in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load an FODP presentation, render its slides, and save each rendered slide as a BMP image. The conversion does not require Microsoft PowerPoint, LibreOffice, or OpenOffice.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert FODP to BMP using Python" %}}
Create a `Presentation` from the FODP file, access each slide through a variable, call `getImage`, and save the rendered image with `ImageFormat.Bmp`.

{{% blocks/products/pf/agp/code-block title="Python code for converting FODP slides to BMP" offSpacer="true" %}}

```python
presentation = Presentation("presentation.fodp")
try:
    slide_count = presentation.getSlides().size()

    for slide_index in range(slide_count):
        slide = presentation.getSlides().get_Item(slide_index)
        slide_image = slide.getImage(2, 2)
        try:
            file_path = f"slide-{slide_index + 1}.bmp"
            slide_image.save(file_path, ImageFormat.Bmp)
        finally:
            slide_image.dispose()
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert FODP slides to BMP in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to render the slides in an FODP presentation as separate BMP images." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source FODP file with `Presentation` and access each slide through a variable.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `getImage` for each slide and save the result with `ImageFormat.Bmp`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert FODP to Other Supported Formats" subTitle="You can also convert FODP presentations to other supported file formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-pdf/" name="FODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-png/" name="FODP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-jpg/" name="FODP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-potm/" name="FODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-svg/" name="FODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
