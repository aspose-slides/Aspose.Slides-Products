---
lastmod: 2026-07-24
title: Convert PPT to Word in Python
url: /python-net/conversion/ppt-to-word/
keywords: Convert PPT to Word, PPT to Word, PPT to DOC, PowerPoint to Word, Python API, Python Library
description: Convert PPT presentation slides to Word documents in Python. Use Aspose.Slides and Aspose.Words to create a DOCX file from a PowerPoint presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPT to Word in Python" h2="Python APIs for converting PowerPoint presentation slides to Word documents without Microsoft Office" >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Word using Aspose.Slides and Aspose.Words" %}}

[**Aspose.Slides for Python via .NET**](/slides/python-net/) and [**Aspose.Words for Python via .NET**](/words/python-net/) let you process PowerPoint presentations and Word documents programmatically. To convert a PPT file to Word, render each slide by using `Slide.get_image`, insert the resulting image into a document with `DocumentBuilder.insert_image`, and save the document in DOCX format.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Convert PowerPoint to Word in Python" %}}
The following example converts every slide in a PPT presentation to a full-page image in a Word document.

{{% blocks/products/pf/agp/code-block title="Python code for converting PowerPoint to Word" offSpacer="true" %}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    document = words.Document()
    document_builder = words.DocumentBuilder(document)

    slide_size = presentation.slide_size.size
    document_builder.page_setup.page_width = slide_size.width
    document_builder.page_setup.page_height = slide_size.height
    document_builder.page_setup.left_margin = 0
    document_builder.page_setup.right_margin = 0
    document_builder.page_setup.top_margin = 0
    document_builder.page_setup.bottom_margin = 0

    image_scale = 2
    slide_count = len(presentation.slides)

    for slide_index, slide in enumerate(presentation.slides):
        with slide.get_image(image_scale, image_scale) as slide_image:
            with io.BytesIO() as image_stream:
                slide_image.save(image_stream, slides.ImageFormat.PNG)
                image_data = image_stream.getvalue()

        page_width = document_builder.page_setup.page_width
        page_height = document_builder.page_setup.page_height
        document_builder.insert_image(image_data, page_width, page_height)

        if slide_index < slide_count - 1:
            document_builder.insert_break(words.BreakType.PAGE_BREAK)

    document.save("presentation.docx")
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to convert PPT to Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install **Aspose.Slides for Python via .NET** and **Aspose.Words for Python via .NET**.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PPT file into a `Presentation` instance, and create `Document` and `DocumentBuilder` instances.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Match the Word page size and margins to `Presentation.slide_size`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render each `Slide` with `Slide.get_image` and insert the image by using `DocumentBuilder.insert_image`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the resulting DOCX file by using `Document.save`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}





{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert PPT files to other supported formats." >}}


{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/ppt-to-jpg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
