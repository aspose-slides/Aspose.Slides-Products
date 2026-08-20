---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert FODP to SVG in Python
url: /python-java/conversion/fodp-to-svg/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, FODP to SVG conversion, Python presentation library
description: Convert FODP presentation slides to SVG images in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert FODP Slides to SVG Images in Python" h2="Export every slide in an FODP presentation as a separate SVG image with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert FODP to SVG in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load an FODP presentation and export each slide as a scalable SVG image. The conversion does not require Microsoft PowerPoint, LibreOffice, or OpenOffice.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert FODP to SVG using Python" %}}
Create a `Presentation` from the FODP file, access each slide through a variable, and call `writeAsSvgToBytes` to create the SVG data.

{{% blocks/products/pf/agp/code-block title="Python code for converting FODP slides to SVG" offSpacer="true" %}}

```python
presentation = Presentation("presentation.fodp")
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

{{< blocks/products/pf/feature-page-section  h2="How to convert FODP slides to SVG in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to export the slides in an FODP presentation as separate SVG images." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source FODP file with `Presentation` and access each slide through a variable.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `writeAsSvgToBytes` for each slide and write the returned data to an SVG file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert FODP to Other Supported Formats" subTitle="You can also convert FODP presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
