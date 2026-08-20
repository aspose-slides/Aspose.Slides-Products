---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTX to PPSM in Python
url: /python-java/conversion/pptx-to-ppsm/
keywords: Python PPTX conversion, PPTX to PPSM, macro-enabled PowerPoint slide show, PowerPoint conversion, Aspose.Slides for Python via Java
description: Convert PPTX presentations to macro-enabled PPSM slide shows in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTX to PPSM in Python" h2="Save a PowerPoint presentation as a macro-enabled slide show with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPTX to PPSM in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a macro-free PowerPoint presentation (PPTX) and save it as a macro-enabled PowerPoint slide show (PPSM). The output opens in slide show mode in compatible applications. Selecting PPSM as the output format does not add macros to a presentation that has none. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPTX to PPSM using Python" %}}
Create a `Presentation` from the PPTX file, then call `save` with `SaveFormat.Ppsm`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPTX to PPSM" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pptx")
try:
    presentation.save("presentation.ppsm", SaveFormat.Ppsm)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPTX to PPSM in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert a PowerPoint presentation to a macro-enabled PPSM slide show." >}}

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
Call `save` with `SaveFormat.Ppsm` to create the PPSM slide show.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPTX to Other Supported Formats" subTitle="You can also convert PPTX presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
