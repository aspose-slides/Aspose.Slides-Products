---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to SVG in C#
weight: 100
url: /net/conversion/pdf-to-svg/
keywords: PDF to SVG, Convert PDF to SVG, C# API, .NET Library, PDF, SVG
description: Convert PDF to SVG in C# using Aspose.Slides for .NET. Use the sample code to import PDF pages and export them as SVG files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to SVG in C#" h2="Convert PDF documents to SVG files in C# using server-side Aspose.Slides APIs."
  apiHomeLink="/slides/net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/net/"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to SVG in C#" %}}

Use [Aspose.Slides for .NET](/slides/net/) to import PDF pages into a presentation and export each slide as an SVG file. Install the package from [NuGet](https://www.nuget.org/packages/Aspose.Slides.NET/) or use the following Package Manager Console command.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Package Manager Console Command" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# code to convert PDF to SVG" >}}
```cs
using var presentation = new Presentation();
presentation.Slides.AddFromPdf("document.pdf");
presentation.Slides.RemoveAt(0);

foreach (var slide in presentation.Slides)
{
    using var svgStream = File.Create($"Slide_{slide.SlideNumber}.svg");
    slide.WriteAsSvg(svgStream);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PDF to SVG in C#" intro=".NET developers can convert PDF files to SVG in a few lines of code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Slides.AddFromPdf` to import pages from the PDF file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Remove the default empty slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through each slide in the `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create an output stream and call `WriteAsSvg` for each slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before you run the PDF to SVG conversion C# code, your machine must have these prerequisites:" %}}

- A supported operating system with .NET or Mono installed.
-  Development environment like Microsoft Visual Studio.
-  Aspose.Slides for .NET referenced in your project.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free Online Converter"
  description="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="Aspose.Slides supports conversion operations for many file formats" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
