---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTX to FODP in Python
url: /python-java/conversion/pptx-to-fodp/
keywords: Python PPTX conversion, PPTX to FODP, PowerPoint to Flat OpenDocument Presentation, presentation conversion, Aspose.Slides for Python via Java
description: Convert PPTX files to Flat OpenDocument Presentation (FODP) format in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTX to FODP in Python" h2="Export PowerPoint presentations to Flat OpenDocument Presentation format with Aspose.Slides for Python via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPTX to FODP in Python" %}}

[**Aspose.Slides for Python via Java**](/slides/python-java/) can load a PowerPoint presentation (`.pptx`) and save it as a Flat OpenDocument Presentation (`.fodp`). FODP stores an OpenDocument presentation as a single uncompressed XML file, which is useful for source control and XML-based processing. Microsoft PowerPoint is not required.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPTX to FODP using Python" %}}
Create a `Presentation` from the PPTX file, then call `save` with `SaveFormat.Fodp`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPTX to FODP" offSpacer="true" %}}

```python
presentation = Presentation("presentation.pptx")
try:
    presentation.save("presentation.fodp", SaveFormat.Fodp)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPTX to FODP in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to export a PPTX file as a Flat OpenDocument Presentation." >}}

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
Call `save` with `SaveFormat.Fodp` to create the FODP file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPTX to Other Supported Formats" subTitle="You can also convert PPTX presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
