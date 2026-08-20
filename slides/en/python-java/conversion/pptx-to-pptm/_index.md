---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTX to PPTM in Python
url: /python-java/conversion/pptx-to-pptm/
keywords: Python PPTX conversion, PPTX to PPTM, macro-enabled PowerPoint presentation, PowerPoint conversion, Aspose.Slides for Python via Java
description: Convert PPTX presentations to macro-enabled PowerPoint PPTM files in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTX to PPTM in Python" h2="Save a PowerPoint presentation in the macro-enabled PPTM format with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPTX to PPTM in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a macro-free PowerPoint presentation (PPTX) and save it as a macro-enabled Open XML presentation (PPTM). PPTM supports VBA projects, but selecting this output format does not add macros to a presentation that has none. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPTX to PPTM using Python" %}}
Create a `Presentation` from the PPTX file, then call `save` with `SaveFormat.Pptm`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPTX to PPTM" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pptx")
try:
    presentation.save("presentation.pptm", SaveFormat.Pptm)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPTX to PPTM in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to convert a PowerPoint presentation to the macro-enabled PPTM format." >}}

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
Call `save` with `SaveFormat.Pptm` to create the PPTM presentation.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPTX to Other Supported Formats" subTitle="You can also convert PPTX presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
