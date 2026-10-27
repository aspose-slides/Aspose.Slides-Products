---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to PPTX in C#
url: /net/conversion/pdf-to-pptx/
keywords: Convert PDF to PPTX, PDF to PPTX, PowerPoint, PDF, PPTX, C# API, .NET Library
description: Convert PDF to PPTX in C# using Aspose.Slides for .NET. Use the sample code in C# applications, including ASP.NET projects.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to PPTX in C#" h2="Convert PDF files to PPTX in C# using server-side Aspose.Slides APIs." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to PPTX in C#" variant="code" %}}

Use [Aspose.Slides for .NET](/slides/net/) to convert PDF pages to a PPTX presentation in a few lines of C# code:

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# code for converting PDF to PPTX" >}}
```cs
using var presentation = new Presentation();
presentation.Slides.AddFromPdf("document.pdf");
presentation.Slides.RemoveAt(0);
presentation.Save("presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to PPTX using Aspose.Slides" %}}

[Aspose.Slides for .NET](/slides/net/) lets you import PDF pages into a presentation and save the result as a PPTX file.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PDF to PPTX in C#" intro=".NET developers can convert PDF files to PPTX in a few lines of code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[Aspose.Slides for .NET](/slides/net/) referenced in your project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Slides.AddFromPdf` to import pages from the PDF file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Remove the default empty slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `Save` method with the output file path and `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported PowerPoint Conversions" subTitle="You can also convert files in other formats to PowerPoint" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
