---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSX to PPTM in Python
url: /python-java/conversion/ppsx-to-pptm/
keywords: Python PPSX conversion, PPSX to PPTM, PowerPoint slide show to presentation, macro-enabled PowerPoint presentation, Aspose.Slides for Python via Java
description: Convert PPSX slide shows to PowerPoint PPTM presentations in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSX Slide Shows to PPTM in Python" h2="Save a PowerPoint slide show as a macro-enabled PPTM presentation with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSX to PPTM in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a macro-free PowerPoint Slide Show (`.ppsx`) and save it as a macro-enabled PowerPoint presentation (`.pptm`). Choosing PPTM as the output format does not add VBA macros when the source slide show has none. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPSX to PPTM using Python" %}}
Create a `Presentation` from the PPSX file, then call `save` with `SaveFormat.Pptm`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPSX to PPTM" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppsx")
try:
    presentation.save("presentation.pptm", SaveFormat.Pptm)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPSX to PPTM in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert a PowerPoint slide show to a macro-enabled PPTM presentation." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source PPSX file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Pptm` to create the PPTM presentation.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX slide shows to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
