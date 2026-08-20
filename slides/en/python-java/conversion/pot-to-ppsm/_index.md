---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POT to PPSM in Python
url: /python-java/conversion/pot-to-ppsm/
keywords: Python POT conversion, POT to PPSM, PowerPoint to PPSM, macro-enabled PowerPoint show, Aspose.Slides for Python via Java
description: Convert POT templates to macro-enabled PowerPoint PPSM slide shows in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert POT Templates to PPSM in Python" h2="Create a macro-enabled PowerPoint slide show from a POT file with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert POT to PPSM in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a binary PowerPoint 97–2003 template (POT) and save it as a macro-enabled PowerPoint slide show (PPSM). PPSM is an Open XML format that can store VBA macros and is intended to open directly in slide show mode in compatible applications. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert POT to PPSM using Python" %}}
Create a `Presentation` from the POT file, then call `save` with `SaveFormat.Ppsm`.

{{% blocks/products/pf/agp/code-block title="Python code for converting POT to PPSM" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pot")
try:
    presentation.save("presentation.ppsm", SaveFormat.Ppsm)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert POT to PPSM in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert a POT template to a macro-enabled PowerPoint slide show." >}}

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
Call `save` with `SaveFormat.Ppsm` to create the PPSM slide show.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert POT to Other Supported Formats" subTitle="You can also convert POT files to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
