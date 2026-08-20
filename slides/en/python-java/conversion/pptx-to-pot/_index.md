---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTX to POT in Python
url: /python-java/conversion/pptx-to-pot/
keywords: Python PPTX conversion, PPTX to POT, PowerPoint POT format, presentation conversion, Aspose.Slides for Python via Java
description: Convert PPTX presentations to POT files in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTX Presentations to POT in Python" h2="Save a PPTX presentation in the binary POT format with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPTX to POT in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PPTX presentation and save it in the binary PowerPoint 97-2003 POT format. The conversion does not require Microsoft PowerPoint.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPTX to POT using Python" %}}
Create a `Presentation` from the PPTX file and call `save` with `SaveFormat.Pot` to create the POT file.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPTX to POT" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pptx")
try:
    presentation.save("presentation.pot", SaveFormat.Pot)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPTX to POT in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert a PPTX presentation to the binary POT format." >}}

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
Call `save` with `SaveFormat.Pot` to write the POT file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPTX to Other Supported Formats" subTitle="You can also convert PPTX presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
