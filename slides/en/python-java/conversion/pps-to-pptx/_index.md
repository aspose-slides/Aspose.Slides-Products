---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPS to PPTX in Python
url: /python-java/conversion/pps-to-pptx/
keywords: Python PPS conversion, PPS to PPTX, PowerPoint slide show to presentation, Open XML presentation, Aspose.Slides for Python via Java
description: Convert PPS slide shows to editable PowerPoint PPTX presentations in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPS Slide Shows to PPTX in Python" h2="Save a legacy PowerPoint slide show as an editable Open XML presentation with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPS to PPTX in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a legacy binary PowerPoint slide show (PPS) and save it as an editable, macro-free Open XML presentation (PPTX). The conversion changes the default document behavior from slide show playback to presentation editing. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPS to PPTX using Python" %}}
Create a `Presentation` from the PPS file, then call `save` with `SaveFormat.Pptx`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPS to PPTX" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pps")
try:
    presentation.save("presentation.pptx", SaveFormat.Pptx)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPS to PPTX in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert a PowerPoint slide show to an editable PPTX presentation." >}}

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
Call `save` with `SaveFormat.Pptx` to create the PPTX presentation.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPS to Other Supported Formats" subTitle="You can also convert PPS slide shows to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
