---
lastmod: 2026-07-30
title: View PPS in Python
url: /python-net/viewer/pps/
keywords: View PPS, View PowerPoint Slideshow, Play Slideshow, Open PPS, PPS Viewer, PPS, PowerPoint, Python API, Python Library
description: Open a PPS slide show in Python and export it to responsive HTML for viewing in a browser.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="View PPS in Python" h2="Use a cross-platform Python API to open PPS files and export them for viewing in a browser" >}}

{{% blocks/products/pf/feature-page-section h2="View PPS using Aspose.Slides" %}}

[Aspose.Slides for Python via .NET](/slides/python-net/) is a presentation-processing library for opening, editing, and converting PowerPoint and OpenDocument presentation files.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="View PPS in Python" %}}
With [Aspose.Slides for Python via .NET](/slides/python-net/), you can load a PPS slide show and export it to responsive HTML for viewing in a web browser.

{{% blocks/products/pf/agp/code-block title="Python code for viewing PPS" offSpacer="true" %}}
```python
with slides.Presentation("presentation.pps") as presentation:
    responsive_html_controller = slides.export.ResponsiveHtmlController()
    html_formatter = slides.export.HtmlFormatter.create_custom_formatter(responsive_html_controller)

    html_options = slides.export.HtmlOptions()
    html_options.html_formatter = html_formatter

    presentation.save("presentation.html", slides.export.SaveFormat.HTML, html_options)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to view PPS in Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install Aspose.Slides for Python via .NET. See the [installation guide](https://docs.aspose.com/slides/python-net/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Ensure that the source PPS file is accessible to your application.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PPS file into a `Presentation` instance.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `ResponsiveHtmlController` instance for responsive HTML output.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create an `HtmlOptions` instance and set its `html_formatter` property with `HtmlFormatter.create_custom_formatter()`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save()` with `SaveFormat.HTML` to export the presentation.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the generated HTML file in a web browser to view the presentation.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}





{{< blocks/products/pf/agp/other-supported-section title="View other files" subTitle="You can also open and view presentations in other formats" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/viewer/ppt/" name="View PPT Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/viewer/pptx/" name="View PPTX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/viewer/odp/" name="View ODP Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/viewer/otp/" name="View OTP Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/viewer/pot/" name="View POT Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/viewer/potm/" name="View POTM Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/viewer/potx/" name="View POTX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/viewer/ppsm/" name="View PPSM Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/viewer/ppsx/" name="View PPSX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/viewer/pptm/" name="View PPTM Presentation" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
