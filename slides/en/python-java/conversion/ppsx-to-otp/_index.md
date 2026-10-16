---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSX to OTP in Python
url: /python-java/conversion/ppsx-to-otp/
keywords: Python PPSX conversion, PPSX to OTP, PowerPoint to OTP, slide show to OTP, Aspose.Slides for Python via Java
description: Convert PPSX files to OTP presentation templates in Python with Aspose.Slides for Python via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPSX Files to OTP in Python" h2="Turn a PowerPoint slide show into a reusable OpenDocument presentation template." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="How to Convert PPSX to OTP in Python" variant="code" %}}

Create a `Presentation` from the source PPSX file and save it with `SaveFormat.Otp`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for converting PPSX to OTP" >}}
```python
presentation = Presentation("presentation.ppsx")
try:
    presentation.save("presentation.otp", SaveFormat.Otp)
finally:
    presentation.dispose()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSX to OTP in Python" %}}

[Aspose.Slides for Python via Java](/slides/python-java/) can convert a PowerPoint Slide Show (`.ppsx`) to an OpenDocument Presentation Template (`.otp`) without Microsoft PowerPoint or LibreOffice. The OTP output can serve as a reusable starting point for presentations in applications that support the OpenDocument format.

Load the source file with `Presentation`, then call `save` with `SaveFormat.Otp`. Aspose.Slides writes the supported slide content, layouts, and formatting to the template file.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps to Convert PPSX to OTP in Python" intro="The conversion loads the PowerPoint slide show and writes its content to an OpenDocument presentation template." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [Aspose.Slides for Python via Java](/slides/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure JPype and make the Aspose.Slides package available to your Python project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` from the source `.ppsx` file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with `SaveFormat.Otp` and an `.otp` output path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX presentations to other supported file formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
