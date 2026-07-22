---
title: Convert PPSX to PNG in Python
url: /python-java/conversion/ppsx-to-png/
keywords: Python PPSX conversion, PPSX to PNG, PowerPoint to PNG, slide show to PNG, Aspose.Slides for Python via Java
description: Convert PPSX presentation slides to PNG images in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSX Slides to PNG Images in Python" h2="Render every slide in a PowerPoint slide show as a PNG image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSX to PNG in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can render the slides in a PowerPoint Slide Show (`.ppsx`) as PNG images without Microsoft PowerPoint. Because a PNG file stores one image, the conversion creates a separate output file for each slide. Animations, transitions, and other interactive behavior are not included in the images.

Use `Presentation.getSlides` to iterate through the source slides. For each `Slide`, call `getImage` and save the returned image with `ImageFormat.Png`. The scaling values passed to `getImage` control the output dimensions relative to the original slide size.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="How to Convert PPSX to PNG in Python" %}}
Load the PPSX file into a `Presentation`, render each slide with `getImage`, and save each result in PNG format.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPSX slides to PNG" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppsx")
try:
    slide_count = presentation.getSlides().size()

    for slide_index in range(slide_count):
        slide = presentation.getSlides().get_Item(slide_index)
        slide_image = slide.getImage(2.0, 2.0)
        try:
            slide_number = slide_index + 1
            file_path = f"slide-{slide_number}.png"
            slide_image.save(file_path, ImageFormat.Png)
        finally:
            slide_image.dispose()
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Steps to Convert PPSX to PNG in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="The conversion renders each slide in the PPSX presentation to a separate PNG image." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [Aspose.Slides for Python via Java](/slides/python-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure JPype and make the Aspose.Slides package available to your Python project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` from the source `.ppsx` file and determine the slide count.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Access each `Slide`, call `getImage`, and save the result with `ImageFormat.Png`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX presentations to other supported file formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-jpg/" name="PPSX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
