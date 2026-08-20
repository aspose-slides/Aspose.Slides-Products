---
lastmod: 2026-07-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POT to PPSX in Python
url: /python-java/conversion/pot-to-ppsx/
keywords: Python POT conversion, POT to PPSX, PowerPoint to PPSX, PowerPoint slide show, Aspose.Slides for Python via Java
description: Convert POT templates to PowerPoint PPSX slide shows in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert POT Templates to PPSX in Python" h2="Create an Open XML PowerPoint slide show from a POT file with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert POT to PPSX in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a binary PowerPoint 97–2003 template (POT) and save it as an Open XML PowerPoint slide show (PPSX). PPSX is a macro-free format designed to open directly in slide show mode in compatible applications. The conversion does not require Microsoft PowerPoint.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert POT to PPSX using Python" %}}
Create a `Presentation` from the POT file, then call `save` with `SaveFormat.Ppsx`.

{{% blocks/products/pf/agp/code-block title="Python code for converting POT to PPSX" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pot")
try:
    presentation.save("presentation.ppsx", SaveFormat.Ppsx)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert POT to PPSX in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert a POT template to an Open XML PowerPoint slide show." >}}

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
Call `save` with `SaveFormat.Ppsx` to create the PPSX slide show.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert POT to Other Supported Formats" subTitle="You can also convert POT files to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
