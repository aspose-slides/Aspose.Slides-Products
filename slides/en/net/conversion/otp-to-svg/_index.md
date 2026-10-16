---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert OTP to SVG in C#
weight: 1700
url: /net/conversion/otp-to-svg/
description: Convert OTP to SVG in C# using Aspose.Slides for .NET. Use the sample code in C# applications, including ASP.NET projects.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert OTP to SVG in C#" h2="Convert OTP files to SVG files in C# using server-side Aspose.Slides APIs."
  apiHomeLink="/slides/net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/net/"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert OTP to SVG Using C#" %}}

Use [Aspose.Slides for .NET](/slides/net/) to load an OTP presentation and export each slide as an SVG file. Install the package from [NuGet](https://www.nuget.org/packages/Aspose.Slides.NET/) or use the following Package Manager Console command.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Package Manager Console Command" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="This sample code shows OTP to SVG C# Conversion" >}}
```cs
using var presentation = new Presentation("template.otp");

foreach (var slide in presentation.Slides)
{
    using var svgStream = File.Create($"Slide_{slide.SlideNumber}.svg");
    slide.WriteAsSvg(svgStream);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert OTP to SVG via C#" intro=".NET developers can load and convert OTP files to SVG in a few lines of code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the OTP file with a `Presentation` object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through each slide in the `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create an output stream for each SVG file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `WriteAsSvg` method for each slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the .NET conversion sample source code, make sure that you have the following prerequisites." %}}

- A supported operating system with .NET or Mono installed.
-  Development environment like Microsoft Visual Studio.
-  Aspose.Slides for .NET referenced in your project.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert OTP to SVG"
  description="[Try our free Text To Gif app](https://products.aspose.app/slides/text-to-gif/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert OTP into many other file formats including a few listed below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
