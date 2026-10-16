---
lastmod: 2026-07-24
title: Convert PPT to Word in Python
url: /python-net/conversion/ppt-to-word/
keywords: Convert PPT to Word, PPT to Word, PPT to DOC, PowerPoint to Word, Python API, Python Library
description: Convert PPT presentation slides to Word documents in Python. Use Aspose.Slides and Aspose.Words to create a DOCX file from a PowerPoint presentation.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPT to Word in Python" h2="Python APIs for converting PowerPoint presentation slides to Word documents without Microsoft Office" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PowerPoint to Word in Python" variant="code" %}}

The following example converts every slide in a PPT presentation to a full-page image in a Word document.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PowerPoint to Word" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PowerPoint to Word using Aspose.Slides and Aspose.Words" %}}

[**Aspose.Slides for Python via .NET**](/slides/python-net/) and [**Aspose.Words for Python via .NET**](/words/python-net/) let you process PowerPoint presentations and Word documents programmatically. To convert a PPT file to Word, render each slide by using `Slide.get_image`, insert the resulting image into a document with `DocumentBuilder.insert_image`, and save the document in DOCX format.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPT to Word" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for Python via .NET** and **Aspose.Words for Python via .NET**.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPT file into a `Presentation` instance, and create `Document` and `DocumentBuilder` instances.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Match the Word page size and margins to `Presentation.slide_size`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render each `Slide` with `Slide.get_image` and insert the image by using `DocumentBuilder.insert_image`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the resulting DOCX file by using `Document.save`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert PPT files to other supported formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
