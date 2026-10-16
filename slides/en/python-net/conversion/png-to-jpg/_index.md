---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PNG to JPG in Python
url: /python-net/conversion/png-to-jpg/
keywords: PNG to JPG, Convert PNG to JPG, Python API, Python Library, PNG, JPG
description: Convert PNG to JPG in Python. Use the Aspose.Slides Python API to load a PNG image and save it in JPEG format.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PNG to JPG in Python" h2="Load a PNG image and save it as JPG with a cross-platform Python API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to JPG using Python" variant="code" %}}

Load the source PNG as an `IImage` and save it in JPEG format.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PNG into JPG" >}}
```python
with slides.Images.from_file("image.png") as source_image:
    source_image.save("image.jpg", slides.ImageFormat.JPEG)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to JPG in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you convert PNG images to JPG programmatically. Load the source file with `Images.from_file`, then call `IImage.save` with `ImageFormat.JPEG`.

The conversion produces a standard JPEG image without requiring Microsoft PowerPoint or another presentation application. The API also provides an overload of `IImage.save` for setting JPEG quality when you need to control compression.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PNG to JPG Using the Aspose.Slides Python API" intro="These are the steps to convert PNG to JPG in Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source PNG with `Images.from_file`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `IImage.save` with the output file path and `ImageFormat.JPEG`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use the `IImage.save` overload that accepts a quality value if you need to adjust JPEG compression.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PNG to Other Supported Formats" subTitle="You can also convert PNG images to other supported formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
