---
title: Convert PPTM to BMP in Python
url: /python-java/conversion/pptm-to-bmp/
keywords: Python PPTM conversion, PPTM to BMP, PowerPoint slide to BMP, presentation slide to image, Aspose.Slides for Python via Java
description: Convert PPTM presentation slides to BMP images in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTM Slides to BMP Images in Python" h2="Render every slide in a macro-enabled PowerPoint presentation as a BMP image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPTM to BMP in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a macro-enabled PowerPoint presentation (`.pptm`) and render each slide as a separate bitmap (`.bmp`) image. Animations, transitions, macros, and other interactive behavior are not included in the rendered images. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPTM to BMP using Python" %}}
Create a `Presentation` from the PPTM file, access each slide through a variable, call `getImage`, and save the rendered image with `ImageFormat.Bmp`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPTM slides to BMP" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pptm")
try:
    slide_count = presentation.getSlides().size()

    for slide_index in range(slide_count):
        slide = presentation.getSlides().get_Item(slide_index)
        slide_image = slide.getImage(2.0, 2.0)
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

{{< blocks/products/pf/feature-page-section  h2="How to convert PPTM slides to BMP in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to render the slides in a PowerPoint PPTM presentation as separate BMP images." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source PPTM file with `Presentation` and access each slide through a variable.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `getImage` for each slide and save the result with `ImageFormat.Bmp`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPTM to Other Supported Formats" subTitle="You can also convert PPTM presentations to other supported file formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-html/" name="PPTM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-png/" name="PPTM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-jpg/" name="PPTM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-fodp/" name="PPTM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-gif/" name="PPTM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-odp/" name="PPTM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-otp/" name="PPTM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-pot/" name="PPTM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-potm/" name="PPTM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-potx/" name="PPTM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-pps/" name="PPTM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-svg/" name="PPTM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
