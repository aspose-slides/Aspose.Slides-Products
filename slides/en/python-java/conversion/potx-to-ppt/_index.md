---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POTX to PPT in Python
url: /python-java/conversion/potx-to-ppt/
keywords: Python POTX conversion, POTX to PPT, PowerPoint template to presentation, Open XML to binary presentation, Aspose.Slides for Python via Java
description: Convert POTX presentation templates to legacy PowerPoint PPT presentations in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert POTX Files to PPT in Python" h2="Transform a PowerPoint Open XML template into a legacy binary PPT presentation with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert POTX to PPT in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PowerPoint Open XML template (`POTX`) and save it as an editable presentation in the legacy binary PowerPoint format (`PPT`). The conversion changes the document type while retaining the slide content and design. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert POTX to PPT using Python" %}}
Create a `Presentation` from the POTX file, then call `save` with `SaveFormat.Ppt`.

{{% blocks/products/pf/agp/code-block title="Python code for converting POTX to PPT" offSpacer="true" %}}

```python
presentation = Presentation("presentation.potx")
try:
    presentation.save("presentation.ppt", SaveFormat.Ppt)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert POTX to PPT in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert a POTX file to a legacy PPT presentation." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source POTX file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Ppt` to create the PPT presentation.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert POTX to Other Supported Formats" subTitle="You can also convert POTX presentation templates to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
