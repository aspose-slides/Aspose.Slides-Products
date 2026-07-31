---
title: Convert PDF to SVG in Python
url: /python-net/conversion/pdf-to-svg/
keywords: PDF to SVG, Convert PDF to SVG, Python API, Python Library, PDF, SVG
description: Convert PDF pages to SVG images in Python. Use the Aspose.Slides Python API to import PDF pages and render each slide as scalable vector graphics.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PDF to SVG in Python" h2="Import PDF pages and render them as scalable vector graphics with a cross-platform Python library" >}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to SVG in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you convert PDF pages to SVG images programmatically. The API imports each PDF page as a slide with `SlideCollection.add_from_pdf`, then renders each slide by using `Slide.write_as_svg`.

SVG is a vector format, so every PDF page is written to a separate scalable image file. The conversion requires no Microsoft PowerPoint, Adobe Acrobat, or other presentation software.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to SVG using Python" %}}
Create a `Presentation`, remove its default blank slide, import the PDF pages with `SlideCollection.add_from_pdf`, and call `Slide.write_as_svg` for each slide.

{{% blocks/products/pf/agp/code-block title="Python code for converting PDF into SVG" offSpacer="true" %}}

```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")

    for slide in presentation.slides:
        file_path = f"slide_{slide.slide_number}.svg"
        with open(file_path, "wb") as output_stream:
            slide.write_as_svg(output_stream)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Convert PDF to SVG Using Aspose.Slides for Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PDF to SVG in Python." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and remove its default blank slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the source PDF by using `SlideCollection.add_from_pdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Access each slide through a `Slide` variable and call `Slide.write_as_svg` with an output stream.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF and save it in other file formats. See the supported formats below:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
