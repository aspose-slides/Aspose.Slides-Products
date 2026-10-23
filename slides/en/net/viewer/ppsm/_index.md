---
lastmod: 2026-07-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: View PPSM in C#
url: /net/viewer/ppsm/
keywords: View PPSM, Open PPSM, PPSM Viewer, PPSM, PowerPoint, C# API, .NET Library
description: View PPSM files in C#. Use Aspose.Slides for .NET to open macro-enabled PowerPoint slideshow files and save them as HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="View PPSM in C#" h2="C# API for opening PPSM files and saving them as responsive HTML." related="PPT,PPTX,ODP,OTP,POT,POTM,POTX,PPS,PPSX,PPTM" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="View PPSM in C#" variant="code" %}}

Using [**Aspose.Slides for .NET**](/slides/net/), you can load a PPSM slideshow and save it as responsive HTML with a few lines of code.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# code for viewing PPSM" >}}
```cs
using var presentation = new Presentation("presentation.ppsm");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="View PPSM using Aspose.Slides" %}}

[**Aspose.Slides for .NET**](/slides/net/) is a .NET library for opening, viewing, editing, and converting presentation files. You can load PPSM files and save them as HTML for viewing in a browser.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to view PPSM in C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for .NET**. See [**Installation**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the library as a reference in your project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the `PPSM` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `ResponsiveHtmlController` object for responsive HTML output.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create an `HtmlOptions` object and set the `HtmlFormatter` property.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the PPSM file as HTML with `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="View other files" subTitle="You can also open and view presentations in other formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/viewer/ppt/" name="View PPT Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/viewer/pptx/" name="View PPTX Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/viewer/odp/" name="View ODP Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/viewer/otp/" name="View OTP Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/viewer/pot/" name="View POT Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/viewer/potm/" name="View POTM Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/viewer/potx/" name="View POTX Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/viewer/pps/" name="View PPS Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/viewer/ppsx/" name="View PPSX Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/viewer/pptm/" name="View PPTM Presentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
