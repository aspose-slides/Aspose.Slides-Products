---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPS to BMP in Python
url: /python-java/conversion/pps-to-bmp/
keywords: Python PPS conversion, PPS to BMP, PowerPoint to BMP, slide show to BMP, Aspose.Slides for Python via Java
description: Convert PPS presentation slides to BMP images in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPS Slides to BMP Images in Python" h2="Render every slide in a PowerPoint PPS slide show as a separate BMP image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPS to BMP using Python" variant="code" %}}

Create a `Presentation` from the PPS file, access each slide through a variable, call `getImage`, and save the rendered image with `ImageFormat.Bmp`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPS slides to BMP" >}}
```python
presentation = Presentation("presentation.pps")
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPS to BMP in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PowerPoint 97–2003 slide show (`PPS`), render its slides, and save each rendered slide as a `BMP` image. The conversion does not require Microsoft PowerPoint.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPS slides to BMP in Python" intro="Follow these steps to render the slides in a PowerPoint 97–2003 slide show as separate BMP images." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPS file with `Presentation` and access each slide through a variable.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `getImage` for each slide and save the result with `ImageFormat.Bmp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPS to Other Supported Formats" subTitle="You can also convert PPS slide shows to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
