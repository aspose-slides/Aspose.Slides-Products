---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSX to POT in Python
url: /python-java/conversion/ppsx-to-pot/
keywords: Python PPSX conversion, PPSX to POT, PowerPoint to POT, slide show to POT, Aspose.Slides for Python via Java
description: Convert PPSX files to POT presentation templates in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSX Files to POT in Python" h2="Turn a PowerPoint slide show into a reusable PowerPoint 97-2003 presentation template." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSX to POT in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can convert a PowerPoint Slide Show (`.ppsx`) to a PowerPoint 97-2003 Presentation Template (`.pot`) without Microsoft PowerPoint. The POT output can be used as a reusable starting point in applications that support the legacy binary PowerPoint format.

Load the source file with `Presentation`, then call `save` with `SaveFormat.Pot`. Because POT is an older format, features that it does not support cannot be represented in the output.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="How to Convert PPSX to POT in Python" %}}
Create a `Presentation` from the source PPSX file and save it with `SaveFormat.Pot`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPSX to POT" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppsx")
try:
    presentation.save("presentation.pot", SaveFormat.Pot)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Steps to Convert PPSX to POT in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="The conversion loads the PowerPoint slide show and writes its content to a legacy PowerPoint presentation template." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [Aspose.Slides for Python via Java](/slides/python-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure JPype and make the Aspose.Slides package available to your Python project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` from the source `.ppsx` file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Pot` and a `.pot` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
