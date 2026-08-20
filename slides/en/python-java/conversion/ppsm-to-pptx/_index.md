---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSM to PPTX in Python
url: /python-java/conversion/ppsm-to-pptx/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, PPSM to PPTX conversion, Python presentation library
description: Convert PPSM slide shows to editable PowerPoint PPTX files in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSM Slide Shows to PPTX in Python" h2="Transform a macro-enabled PowerPoint slide show into an editable PPTX presentation with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSM to PPTX in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a macro-enabled PowerPoint PPSM slide show and save it as an editable PPTX presentation. Because PPTX is not a macro-enabled format, VBA projects in the source file are not retained in the output. The conversion does not require Microsoft PowerPoint.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPSM to PPTX using Python" %}}
Create a `Presentation` from the PPSM file and call `save` with `SaveFormat.Pptx` to create the PPTX file.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPSM to PPTX" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppsm")
try:
    presentation.save("presentation.pptx", SaveFormat.Pptx)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPSM to PPTX in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert a macro-enabled PowerPoint slide show to an editable PPTX presentation." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source PPSM file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Pptx` to write the PPTX file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSM to Other Supported Formats" subTitle="You can also convert PPSM presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
