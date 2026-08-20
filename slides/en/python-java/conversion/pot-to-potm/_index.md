---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POT to POTM in Python
url: /python-java/conversion/pot-to-potm/
keywords: Python POT conversion, POT to POTM, PowerPoint to POTM, macro-enabled presentation template, Aspose.Slides for Python via Java
description: Convert POT files to POTM presentation templates in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert POT Files to POTM in Python" h2="Export a binary PowerPoint template as a macro-enabled Open XML template with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert POT to POTM in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a binary PowerPoint template (POT) and export it as a macro-enabled Open XML template (POTM). The POTM format can store VBA macros, but converting a macro-free POT file does not add macros. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert POT to POTM using Python" %}}
Create a `Presentation` from the POT file, then call `save` with `SaveFormat.Potm`.

{{% blocks/products/pf/agp/code-block title="Python code for converting POT to POTM" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pot")
try:
    presentation.save("presentation.potm", SaveFormat.Potm)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert POT to POTM in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to export a POT file as a macro-enabled PowerPoint template." >}}

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
Call `save` with `SaveFormat.Potm` to create the POTM file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert POT to Other Supported Formats" subTitle="You can also convert POT files to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
