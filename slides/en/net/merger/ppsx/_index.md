---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge PPSX Files using .NET
weight: 6100
url: /net/merger/ppsx/
description: C# source code to merge PPSX files with Aspose.Slides for .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Merge PPSX Files in C#" h2="Combine PPSX documents with server-side Aspose.Slides for .NET APIs."
  apiHomeLink="/slides/net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/net/"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge PPSX File Using C#" %}}

To merge PPSX files, use [Aspose.Slides for .NET](/slides/net/), a C# API for creating, converting, and combining presentation documents. Install the package from [NuGet](https://www.nuget.org/packages/Aspose.Slides.NET/) or run the following command in the Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Command" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Merge PPSX Files - C#" >}}
```cs
using var firstPresentation = new Presentation("first.ppsx");
using var secondPresentation = new Presentation("second.ppsx");
using var mergedPresentation = new Presentation();

mergedPresentation.Slides.RemoveAt(0);

foreach (var slide in firstPresentation.Slides)
{
    mergedPresentation.Slides.AddClone(slide);
}

foreach (var slide in secondPresentation.Slides)
{
    mergedPresentation.Slides.AddClone(slide);
}

mergedPresentation.Save("merged.ppsx", SaveFormat.Ppsx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps for Merging PPSX Files in C#" intro="Merge PPSX files with Aspose.Slides for .NET in a few lines of C# code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source PPSX files with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a destination `Presentation` object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add slides from each source file with `Slides.AddClone`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the merged presentation with `SaveFormat.Ppsx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the merged PPSX file in a compatible program.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Aspose.Slides for .NET is supported on major platforms and operating systems. Before running the code below, make sure that your system meets the following requirements." %}}

- A supported operating system with .NET or Mono installed.
-  Development environment like Microsoft Visual Studio
-  Aspose.Slides for .NET DLL referenced in your project - Install from NuGet using the Download button above

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension="ppsx"
  title="Merge PPSX Files Online"
  description="Combine files online with Aspose.Slides Merger." >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSX" readMoreLink="https://docs.fileformat.com/presentation/ppsx/" %}}

A PPSX file is a PowerPoint Open XML Slide Show created by Microsoft PowerPoint 2007 or later. It is the Open XML successor to the PPS format used by PowerPoint 97–2003. Unlike a PPTX file, which opens in editing mode by default, a PPSX file opens directly as a slide show. It preserves the presentation's slide order and can contain images, audio, and other embedded media.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Merging Formats" subTitle="You can also merge many other file formats in C#." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/odp/" name="ODP" description="OpenDocument Presentation Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/otp/" name="OTP" description="OpenDocument Presentation Template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/pot/" name="POT" description="PowerPoint 97–2003 Template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/potm/" name="POTM" description="PowerPoint Macro-Enabled Template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/potx/" name="POTX" description="PowerPoint Template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/ppt/" name="PPT" description="PowerPoint 97-2003 Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/pptx/" name="PPTX" description="Open XML Presentation Format" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
