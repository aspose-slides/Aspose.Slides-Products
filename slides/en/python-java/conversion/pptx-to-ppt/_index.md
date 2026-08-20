---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTX to PPT in Python
url: /python-java/conversion/pptx-to-ppt/
keywords: Python PPTX conversion, PPTX to PPT, PowerPoint 97-2003 presentation, legacy PowerPoint conversion, Aspose.Slides for Python via Java
description: Convert PPTX presentations to legacy PowerPoint PPT files in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTX to PPT in Python" h2="Save an Open XML presentation in the legacy PowerPoint 97-2003 format with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPTX to PPT in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load an Open XML PowerPoint presentation (PPTX) and save it in the legacy PowerPoint 97-2003 presentation format (PPT). The conversion preserves supported content and layout, but features unavailable in the older format may be simplified. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPTX to PPT using Python" %}}
Create a `Presentation` from the PPTX file, then call `save` with `SaveFormat.Ppt`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPTX to PPT" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pptx")
try:
    presentation.save("presentation.ppt", SaveFormat.Ppt)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPTX to PPT in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert an Open XML PowerPoint presentation to the legacy PPT format." >}}

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
Call `save` with `SaveFormat.Ppt` to create the PPT presentation.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPTX to Other Supported Formats" subTitle="You can also convert PPTX presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
