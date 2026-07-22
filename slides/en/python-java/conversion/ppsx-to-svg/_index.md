---
title: Convert PPSX to SVG in Python
url: /python-java/conversion/ppsx-to-svg/
keywords: Python PPSX conversion, PPSX to SVG, PowerPoint slide to SVG, scalable vector graphics, Aspose.Slides for Python via Java
description: Convert PPSX presentation slides to SVG images in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSX Slides to SVG Images in Python" h2="Export every slide in a PowerPoint slide show as a separate SVG image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSX to SVG in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PowerPoint Slide Show (`.ppsx`) and export each slide as a separate scalable vector graphics (SVG) image. SVG output scales without losing the quality of vector content and can be displayed in modern web browsers. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPSX to SVG using Python" %}}
Create a `Presentation` from the PPSX file, access each slide through a variable, and call `writeAsSvgToBytes` to create the SVG data.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPSX slides to SVG" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppsx")
try:
    slide_count = presentation.getSlides().size()

    for slide_index in range(slide_count):
        slide = presentation.getSlides().get_Item(slide_index)
        file_path = f"slide-{slide_index + 1}.svg"
        svg_data = bytes(slide.writeAsSvgToBytes())

        with open(file_path, "wb") as output_file:
            output_file.write(svg_data)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPSX slides to SVG in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to export the slides in a PowerPoint PPSX file as separate SVG images." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source PPSX file with `Presentation` and access each slide through a variable.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `writeAsSvgToBytes` for each slide and write the returned data to an SVG file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX slide shows to other supported file formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-png/" name="PPSX TO PNG" >}}
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
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
