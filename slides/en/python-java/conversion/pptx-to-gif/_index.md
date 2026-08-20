---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTX to GIF in Python
url: /python-java/conversion/pptx-to-gif/
keywords: Python PPTX conversion, PPTX to GIF, PowerPoint to animated GIF, presentation animation, Aspose.Slides for Python via Java
description: Convert PPTX files to animated GIF images in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTX to Animated GIF in Python" h2="Export a PowerPoint presentation as a single animated GIF with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPTX to GIF in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PowerPoint presentation (`.pptx`) and export it as an animated GIF. The output file presents the slides as animation frames and can reproduce supported slide transitions and animations. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPTX to GIF using Python" %}}
Create a `Presentation` from the source PPTX file, then call `save` with `SaveFormat.Gif` to generate an animated GIF.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPTX to animated GIF" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pptx")
try:
    presentation.save("presentation.gif", SaveFormat.Gif)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPTX to animated GIF in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to export a PowerPoint PPTX presentation as a single animated GIF." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source PPTX file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Gif` and a `.gif` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPTX to Other Supported Formats" subTitle="You can also convert PPTX presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
