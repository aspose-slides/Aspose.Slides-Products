---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert ODP to PPTX in Python
url: /python-java/conversion/odp-to-pptx/
keywords: Python presentation conversion, convert presentations to Python, Python for presentations, Aspose.Slides Python, ODP to PPTX conversion, Python presentation library
description: Convert ODP presentations to PPTX files in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert ODP Presentations to PPTX in Python" h2="Transform an ODP presentation into an editable PPTX file with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert ODP to PPTX in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load an ODP presentation and save it as a PPTX file while preserving its slides and content. PPTX is the macro-free presentation format based on Office Open XML. The conversion does not require Microsoft PowerPoint, LibreOffice, or OpenOffice.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert ODP to PPTX using Python" %}}
Create a `Presentation` from the ODP file and call `save` with `SaveFormat.Pptx` to create the PPTX file.

{{% blocks/products/pf/agp/code-block title="Python code for converting ODP to PPTX" offSpacer="true" %}}

```python
presentation = Presentation("presentation.odp")
try:
    presentation.save("presentation.pptx", SaveFormat.Pptx)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert ODP to PPTX in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert an OpenDocument presentation to the PowerPoint PPTX format." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source ODP file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Pptx` to write the PPTX file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert ODP to Other Supported Formats" subTitle="You can also convert ODP presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
