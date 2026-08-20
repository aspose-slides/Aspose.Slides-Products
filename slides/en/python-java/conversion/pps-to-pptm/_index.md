---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPS to PPTM in Python
url: /python-java/conversion/pps-to-pptm/
keywords: Python PPS conversion, PPS to PPTM, macro-enabled PowerPoint presentation, PowerPoint conversion, Aspose.Slides for Python via Java
description: Convert PPS slide shows to PowerPoint PPTM presentations in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPS Slide Shows to PPTM in Python" h2="Save a legacy PowerPoint slide show as a macro-enabled PPTM presentation with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPS to PPTM in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a legacy binary PowerPoint slide show (PPS) and save it as a macro-enabled Open XML presentation (PPTM). PPTM can store VBA projects, but selecting this output format does not add macros to a source file that has none. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPS to PPTM using Python" %}}
Create a `Presentation` from the PPS file, then call `save` with `SaveFormat.Pptm`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPS to PPTM" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pps")
try:
    presentation.save("presentation.pptm", SaveFormat.Pptm)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPS to PPTM in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert a legacy PowerPoint slide show to a macro-enabled PPTM presentation." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Python via Java**](https://docs.aspose.com/slides/python-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure the package and start the Java Virtual Machine in your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source PPS file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Pptm` to create the PPTM presentation.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPS to Other Supported Formats" subTitle="You can also convert PPS slide shows to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
