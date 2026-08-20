---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POT to PNG in Python
url: /python-java/conversion/pot-to-png/
keywords: Python POT conversion, POT to PNG, PowerPoint to PNG, presentation to PNG, Aspose.Slides for Python via Java
description: Convert POT presentation slides to PNG images in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert POT Slides to PNG Images in Python" h2="Render every slide in a POT file as a separate PNG image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert POT to PNG in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a POT file, render each slide, and save the rendered content as a PNG image. This produces one image per slide and does not require Microsoft PowerPoint.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert POT to PNG using Python" %}}
Create a `Presentation` from the POT file, access each slide through a variable, call `getImage`, and save the rendered image with `ImageFormat.Png`.

{{% blocks/products/pf/agp/code-block title="Python code for converting POT slides to PNG" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pot")
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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert POT slides to PNG in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to render the slides in a POT file as separate PNG images." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source POT file with `Presentation` and access each slide through a variable.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `getImage` for each slide and save the result with `ImageFormat.Png`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert POT to Other Supported Formats" subTitle="You can also convert POT files to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
