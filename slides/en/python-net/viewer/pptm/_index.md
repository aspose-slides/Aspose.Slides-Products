---
lastmod: 2026-07-30
title: View PPTM in Python
url: /python-net/viewer/pptm/
keywords: View PPTM, View Macro-enabled PowerPoint Presentation, Open PPTM, PPTM Viewer, PPTM, PowerPoint, Python API, Python Library
description: Open a macro-enabled PPTM presentation in Python and export it to responsive HTML for viewing in a browser.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="View PPTM in Python" h2="Use a cross-platform Python API to open PPTM files and export them for viewing in a browser" related="PPT,PPTX,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="View PPTM in Python" variant="code" %}}

With [Aspose.Slides for Python via .NET](/slides/python-net/), you can load a macro-enabled PPTM presentation and export it to responsive HTML for viewing in a web browser.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for viewing PPTM" >}}
```python
with slides.Presentation("presentation.pptm") as presentation:
    responsive_html_controller = slides.export.ResponsiveHtmlController()
    html_formatter = slides.export.HtmlFormatter.create_custom_formatter(responsive_html_controller)

    html_options = slides.export.HtmlOptions()
    html_options.html_formatter = html_formatter

    presentation.save("presentation.html", slides.export.SaveFormat.HTML, html_options)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="View PPTM using Aspose.Slides" %}}

[Aspose.Slides for Python via .NET](/slides/python-net/) is a presentation-processing library for opening, editing, and converting PowerPoint and OpenDocument presentation files.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to view PPTM in Python" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install Aspose.Slides for Python via .NET. See the [installation guide](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ensure that the source PPTM file is accessible to your application.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPTM file into a `Presentation` instance.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `ResponsiveHtmlController` instance for responsive HTML output.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create an `HtmlOptions` instance and set its `html_formatter` property with `HtmlFormatter.create_custom_formatter()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Presentation.save()` with `SaveFormat.HTML` to export the presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the generated HTML file in a web browser to view the presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="View other files" subTitle="You can also open and view presentations in other formats" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/viewer/ppt/" name="View PPT Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/viewer/pptx/" name="View PPTX Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/viewer/odp/" name="View ODP Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/viewer/otp/" name="View OTP Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/viewer/pot/" name="View POT Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/viewer/potm/" name="View POTM Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/viewer/potx/" name="View POTX Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/viewer/pps/" name="View PPS Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/viewer/ppsm/" name="View PPSM Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/viewer/ppsx/" name="View PPSX Presentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
