---
lastmod: 2026-07-09
title: View PPS in C++
url: /cpp/viewer/pps/
keywords: View PPS, Open PPS, PPS Viewer, PPS, C++ API, C++ Library, CPP
description: View PPS presentations in C++. Use Aspose.Slides for C++ to open PowerPoint slideshow files and save them as responsive HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="View PPS in C++" h2="Use Aspose.Slides for C++ to open PPS files and save them as responsive HTML." related="PPT,PPTX,ODP,OTP,POT,POTM,POTX,PPSM,PPSX,PPTM" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="View PPS in C++" variant="code" %}}

Use Aspose.Slides for C++ to load a PPS file and export it to responsive HTML with `ResponsiveHtmlController`, `HtmlOptions`, `HtmlFormatter`, and `SaveFormat::Html`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ code for viewing PPS" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pps");

auto controller = MakeObject<ResponsiveHtmlController>();
auto htmlOptions = MakeObject<HtmlOptions>();
htmlOptions->set_HtmlFormatter(HtmlFormatter::CreateCustomFormatter(controller));

presentation->Save(u"index.html", SaveFormat::Html, htmlOptions);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="View PPS using Aspose.Slides" %}}

Aspose.Slides for C++ is a presentation processing library for opening, viewing, editing, and converting presentation files. You can load a PPS file with the `Presentation` class and save it as HTML for browser-based viewing.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to view PPS in C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install Aspose.Slides for C++. See [Installation](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the library as a reference in your project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPS file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `ResponsiveHtmlController` object for responsive HTML formatting.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create an `HtmlOptions` object and set the `HtmlFormatter` property.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the PPS presentation as HTML with `SaveFormat::Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the generated HTML file in a browser to view the PPS content.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="View other files" subTitle="You can also open and view presentations in other formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/viewer/ppt/" name="View PPT Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/viewer/pptx/" name="View PPTX Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/viewer/odp/" name="View ODP Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/viewer/otp/" name="View OTP Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/viewer/pot/" name="View POT Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/viewer/potm/" name="View POTM Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/viewer/potx/" name="View POTX Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/viewer/ppsm/" name="View PPSM Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/viewer/ppsx/" name="View PPSX Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/viewer/pptm/" name="View PPTM Presentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
