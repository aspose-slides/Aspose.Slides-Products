---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert OTP to PNG in Python
url: /python-java/conversion/otp-to-png/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, OTP to PNG conversion, Python presentation library
description: Convert OTP presentation template slides to PNG images in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert OTP Slides to PNG Images in Python" h2="Render every slide in an OTP presentation template as a separate PNG image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert OTP to PNG using Python" variant="code" %}}

Create a `Presentation` from the OTP file, access each slide through a variable, call `getImage`, and save the rendered image with `ImageFormat.Png`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting OTP slides to PNG" >}}
```python
presentation = Presentation("presentation.otp")
try:
    slide_count = presentation.getSlides().size()

    for slide_index in range(slide_count):
        slide = presentation.getSlides().get_Item(slide_index)
        slide_image = slide.getImage(2, 2)
        try:
            file_path = f"slide-{slide_index + 1}.png"
            slide_image.save(file_path, ImageFormat.Png)
        finally:
            slide_image.dispose()
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert OTP to PNG in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load an OTP presentation template, render each slide, and save the rendered content as a PNG image. This produces one image per slide and does not require Microsoft PowerPoint, LibreOffice, or OpenOffice.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert OTP slides to PNG in Python" intro="Follow these steps to render the slides in an OTP presentation template as separate PNG images." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure the package and start the Java Virtual Machine in your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source OTP file with `Presentation` and access each slide through a variable.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `getImage` for each slide and save the result with `ImageFormat.Png`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert OTP to Other Supported Formats" subTitle="You can also convert OTP presentation templates to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
