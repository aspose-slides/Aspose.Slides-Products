---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PNG to PDF in Python
url: /python-net/conversion/png-to-pdf/
keywords: PNG to PDF, Convert PNG to PDF, Python API, Python Library, PNG, PDF
description: Convert PNG to PDF in Python. Use the Aspose.Slides Python API to place a PNG image on a slide and export it as a PDF document.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PNG to PDF in Python" h2="Place a PNG image on a slide and export it as PDF with a cross-platform Python API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to PDF using Python" variant="code" %}}

Create a `Presentation`, add the source PNG image to its first `Slide`, and save the presentation as a PDF document.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PNG into PDF" >}}
```python
with slides.Presentation() as presentation:
    slide = presentation.slides[0]

    with slides.Images.from_file("image.png") as source_image:
        presentation_image = presentation.images.add_image(source_image)

    presentation.slide_size.set_size(
        presentation_image.width,
        presentation_image.height,
        slides.SlideSizeScaleType.DO_NOT_SCALE,
    )

    slide.shapes.add_picture_frame(
        slides.ShapeType.RECTANGLE,
        0,
        0,
        presentation_image.width,
        presentation_image.height,
        presentation_image,
    )
    presentation.save("image.pdf", slides.export.SaveFormat.PDF)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to PDF in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you place a PNG image on a slide and export the presentation as a PDF document. Add the image to `Presentation.images`, create a picture frame with `ShapeCollection.add_picture_frame`, and call `Presentation.save` with `SaveFormat.PDF`.

The example below creates a one-page PDF whose page size matches the source image. This workflow preserves the image's aspect ratio and does not require Microsoft PowerPoint or a PDF printer.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PNG to PDF Using the Aspose.Slides Python API" intro="These are the steps to convert PNG to PDF in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and access its first `Slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PNG image with `Images.from_file`, add it to `Presentation.images`, and use its dimensions for the slide and picture frame.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Presentation.save` with the output file path and `SaveFormat.PDF`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PNG to Other Supported Formats" subTitle="You can also convert PNG images to other supported formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
