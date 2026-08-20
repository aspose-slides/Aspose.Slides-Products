---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POT to POTX in Python
url: /python-java/conversion/pot-to-potx/
keywords: Python POT conversion, POT to POTX, PowerPoint to POTX, PowerPoint presentation template, Aspose.Slides for Python via Java
description: Convert POT files to POTX presentation templates in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert POT Files to POTX in Python" h2="Save a binary PowerPoint template as an Open XML template with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert POT to POTX in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a binary PowerPoint 97–2003 template (POT) and save it as an Open XML PowerPoint template (POTX). POTX is a macro-free format, so use POTM instead when the output must support VBA macros. Microsoft PowerPoint is not required for the conversion.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert POT to POTX using Python" %}}
Create a `Presentation` from the POT file, then call `save` with `SaveFormat.Potx`.

{{% blocks/products/pf/agp/code-block title="Python code for converting POT to POTX" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pot")
try:
    presentation.save("presentation.potx", SaveFormat.Potx)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert POT to POTX in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert a binary PowerPoint template to the POTX format." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source POT file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Potx` to create the POTX file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert POT to Other Supported Formats" subTitle="You can also convert POT files to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
