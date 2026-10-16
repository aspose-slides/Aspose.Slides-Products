---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POTX to JPG in Python
url: /python-java/conversion/potx-to-jpg/
keywords: Python POTX conversion, POTX to JPG, PowerPoint to JPG, presentation template to JPG, Aspose.Slides for Python via Java
description: Convert POTX presentation template slides to JPG images in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert POTX Slides to JPG Images in Python" h2="Render every slide in a POTX presentation template as a separate JPG image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTX to JPG using Python" variant="code" %}}

Create a `Presentation` from the POTX file, access each slide through a variable, call `getImage`, and save the rendered image with `ImageFormat.Jpeg`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting POTX slides to JPG" >}}
```python
presentation = Presentation("presentation.potx")
try:
    slide_count = presentation.getSlides().size()

    for slide_index in range(slide_count):
        slide = presentation.getSlides().get_Item(slide_index)
        slide_image = slide.getImage(2, 2)
        try:
            file_path = f"slide-{slide_index + 1}.jpg"
            slide_image.save(file_path, ImageFormat.Jpeg)
        finally:
            slide_image.dispose()
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTX to JPG in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PowerPoint Open XML template (`POTX`), render each slide, and save the rendered content as a `JPG` image. This produces one image per slide and does not require Microsoft PowerPoint.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert POTX slides to JPG in Python" intro="Follow these steps to render the slides in a PowerPoint Open XML template as separate JPG images." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source POTX file with `Presentation` and access each slide through a variable.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `getImage` for each slide and save the result with `ImageFormat.Jpeg`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert POTX to Other Supported Formats" subTitle="You can also convert POTX presentation templates to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
