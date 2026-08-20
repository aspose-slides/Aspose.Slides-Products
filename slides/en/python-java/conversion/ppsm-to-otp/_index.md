---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSM to OTP in Python
url: /python-java/conversion/ppsm-to-otp/
keywords: Python PPSM conversion, PPSM to OTP, PowerPoint to OTP, macro-enabled slide show to OTP, Aspose.Slides for Python via Java
description: Convert PPSM files to OTP presentation templates in Python with Aspose.Slides for Python via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSM Files to OTP in Python" h2="Turn a macro-enabled PowerPoint slide show into an OpenDocument presentation template." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSM to OTP in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can convert a macro-enabled PowerPoint slide show (`.ppsm`) to an OpenDocument Presentation Template (`.otp`). The OTP output can be used as the starting point for new OpenDocument presentations. Because OTP does not support VBA projects, macros are not retained.

Open the source file with `Presentation` and call `save` with `SaveFormat.Otp`. The conversion does not require Microsoft PowerPoint or LibreOffice.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="How to Convert PPSM to OTP in Python" %}}
Create a `Presentation` from the source PPSM file and save it with `SaveFormat.Otp`.

{{% blocks/products/pf/agp/code-block title="Python code for converting PPSM to OTP" offSpacer="true" %}}

```python
presentation = Presentation("presentation.ppsm")
try:
    presentation.save("presentation.otp", SaveFormat.Otp)
finally:
    presentation.dispose()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Steps to Convert PPSM to OTP in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="The conversion loads the macro-enabled PowerPoint slide show and saves its design and content in the OTP format." >}}

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
Call `save` with `SaveFormat.Otp` and an `.otp` output path.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSM to Other Supported Formats" subTitle="You can also convert PPSM presentations to other supported file formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
