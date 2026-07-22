---
title: Convert PPT to JPG in Python
url: /python-java/conversion/ppt-to-jpg/
keywords: Python PPT conversion, PPT to JPG, PowerPoint to JPEG, presentation slide to image, Aspose.Slides for Python via Java
description: Convert PPT presentation slides to JPG images in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPT Slides to JPG Images in Python" h2="Render every slide in a legacy PowerPoint presentation as a JPEG image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPT to JPG in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can render slides from a legacy PowerPoint presentation (`.ppt`) as JPG images without Microsoft PowerPoint. Because a JPG file stores one image, the conversion creates a separate output file for each slide.

Access each slide through a variable, call `getImage`, and save the returned image with `ImageFormat.Jpeg`. The scaling values passed to `getImage` control the output dimensions relative to the original slide size.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPT to JPG using Python" %}}
Load the PPT file into a `Presentation`, render each slide with `getImage`, and save each result in JPEG format.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPT slides to JPG" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppt")
try:
    slide_count = presentation.getSlides().size()

    for slide_index in range(slide_count):
        slide = presentation.getSlides().get_Item(slide_index)
        slide_image = slide.getImage(2.0, 2.0)
        try:
            slide_number = slide_index + 1
            file_path = f"slide-{slide_number}.jpg"
            slide_image.save(file_path, ImageFormat.Jpeg)
        finally:
            slide_image.dispose()
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPT slides to JPG in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to render the slides in a PowerPoint PPT presentation as separate JPEG images." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source PPT file with `Presentation` and determine the slide count.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Access each slide, call `getImage`, and save the result with `ImageFormat.Jpeg`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPT to Other Supported Formats" subTitle="You can also convert PPT presentations to other supported file formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-fodp/" name="PPT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-odp/" name="PPT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-otp/" name="PPT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-pot/" name="PPT TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-potm/" name="PPT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-potx/" name="PPT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-pps/" name="PPT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
