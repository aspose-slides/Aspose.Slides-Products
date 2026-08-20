---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POTX to PPSX in Python
url: /python-java/conversion/potx-to-ppsx/
keywords: Python POTX conversion, POTX to PPSX, PowerPoint slide show conversion, Open XML template to slide show, Aspose.Slides for Python via Java
description: Convert POTX presentation templates to PowerPoint PPSX slide shows in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert POTX Files to PPSX in Python" h2="Save a PowerPoint Open XML template as a PowerPoint slide show with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert POTX to PPSX in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PowerPoint Open XML template (`POTX`) and save it as a PowerPoint Show (`PPSX`). A PPSX file uses the Open XML format and opens directly in Slide Show view in compatible applications. Microsoft PowerPoint is not required for the conversion.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert POTX to PPSX using Python" %}}
Create a `Presentation` from the POTX file, then call `save` with `SaveFormat.Ppsx`.

{{% blocks/products/pf/agp/code-block title="Python code for converting POTX to PPSX" offSpacer="true" %}}

```python
presentation = Presentation("presentation.potx")
try:
    presentation.save("presentation.ppsx", SaveFormat.Ppsx)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert POTX to PPSX in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to save a POTX file as a PPSX slide show." >}}

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
Call `save` with `SaveFormat.Ppsx` to create the PPSX slide show.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert POTX to Other Supported Formats" subTitle="You can also convert POTX presentation templates to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
