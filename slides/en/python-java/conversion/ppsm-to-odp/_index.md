---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSM to ODP in Python
url: /python-java/conversion/ppsm-to-odp/
keywords: Python PPSM conversion, PPSM to ODP, PowerPoint to ODP, macro-enabled slide show to ODP, Aspose.Slides for Python via Java
description: Convert PPSM files to editable ODP presentations in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSM Files to ODP in Python" h2="Transform a macro-enabled PowerPoint slide show into an editable OpenDocument presentation." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSM to ODP in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can convert a macro-enabled PowerPoint slide show (`.ppsm`) to an OpenDocument Presentation (`.odp`) without Microsoft PowerPoint or LibreOffice. The resulting ODP file remains editable in applications that support the OpenDocument format. Because ODP does not support VBA projects, macros are not retained.

Load the source file with `Presentation`, then call `save` with `SaveFormat.Odp`. Aspose.Slides converts supported slide content, layout, and formatting to the destination format.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="How to Convert PPSM to ODP in Python" %}}
Create a `Presentation` from the source PPSM file and save it with `SaveFormat.Odp`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPSM to ODP" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppsm")
try:
    presentation.save("presentation.odp", SaveFormat.Odp)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Steps to Convert PPSM to ODP in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="The conversion loads the macro-enabled PowerPoint slide show and writes its slides to an OpenDocument presentation." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [Aspose.Slides for Python via Java](/slides/python-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure JPype and make the Aspose.Slides package available to your Python project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` from the source `.ppsm` file.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with `SaveFormat.Odp` and an `.odp` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSM to Other Supported Formats" subTitle="You can also convert PPSM presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
