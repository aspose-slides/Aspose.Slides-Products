---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPS to JPG in Python
url: /python-java/conversion/pps-to-jpg/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, PPS to JPG conversion, Python presentation library
description: Convert PPS slides to JPG images in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPS to JPG in Python" h2="Render every slide in a PowerPoint Show as a high-quality JPEG image." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPS to JPG in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can render slides from a PowerPoint Show (`.pps`) file as JPG images without Microsoft PowerPoint. Because a JPG file stores a single image, the conversion creates a separate output file for each slide.

Use `Presentation.getSlides` to iterate through the source slides. For each `Slide`, call `getImage` and save the returned image with `ImageFormat.Jpeg`. The scaling values passed to `getImage` control the output dimensions relative to the original slide size.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="How to Convert PPS to JPG in Python" %}}
Load the PPS file into a `Presentation`, render each slide with `getImage`, and save each result in JPEG format.

{{% blocks/products/pf/agp/code-block title="Python tutorial for converting PPS into JPG" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pps")
try:
    slide_count = presentation.getSlides().size()

    for slide_index in range(slide_count):
        slide = presentation.getSlides().get_Item(slide_index)
        slide_image = slide.getImage(2.0, 2.0)
        try:
            slide_number = slide_index + 1
            file_path = f"slide-{slide_number}.jpg"
            slide_image.save(file_path, ImageFormat.Jpeg)
        finally:
            slide_image.dispose()
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Steps to Convert PPS to JPG in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="The conversion renders each slide in the PPS presentation to a separate JPEG image." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [Aspose.Slides for Python via Java](/slides/python-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure JPype and make the Aspose.Slides package available to your Python project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` from the source `.pps` file and determine the slide count.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Access each `Slide`, call `getImage`, and save the result with `ImageFormat.Jpeg`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPS to Other Supported Formats" subTitle="You can also convert PPS files to the formats listed below." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
