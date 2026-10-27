---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge PPT Files using .NET
weight: 7610
url: /net/merger/ppt/
description: C# source code to merge PPT files with Aspose.Slides for .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Merge PPT Files in C#" h2="Combine PPT documents with server-side Aspose.Slides for .NET APIs."
  apiHomeLink="/slides/net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/net/"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge PPT File Using C#" %}}

To merge PPT files, use [Aspose.Slides for .NET](/slides/net/), a C# API for creating, converting, and combining presentation documents. Install the package from [NuGet](https://www.nuget.org/packages/Aspose.Slides.NET/) or run the following command in the Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Command" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Merge PPT Files - C#" >}}
```cs
using var firstPresentation = new Presentation("first.ppt");
using var secondPresentation = new Presentation("second.ppt");
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

mergedPresentation.Save("merged.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps for Merging PPT Files in C#" intro="Merge PPT files with Aspose.Slides for .NET in a few lines of C# code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source PPT files with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a destination `Presentation` object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add slides from each source file with `Slides.AddClone`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the merged presentation with `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the merged PPT file in a compatible program.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Aspose.Slides for .NET is supported on major platforms and operating systems. Before running the code below, make sure that your system meets the following requirements." %}}

- A supported operating system with .NET or Mono installed.
-  Development environment like Microsoft Visual Studio
-  Aspose.Slides for .NET DLL referenced in your project - Install from NuGet using the Download button above

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

A file with the .ppt extension is a PowerPoint presentation that contains a collection of slides for use in a slide show. It uses the binary file format supported by Microsoft PowerPoint 97–2003. A PPT file can contain several types of content, such as text, bulleted lists, images, multimedia, and other embedded OLE objects. Beginning with PowerPoint 2007, Microsoft introduced the newer PPTX format, which is based on Office Open XML rather than this binary format. Other applications, such as OpenOffice Impress and Apple Keynote, can also create PPT files.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Merging Formats" subTitle="You can also merge many other file formats in C#." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/odp/" name="ODP" description="OpenDocument Presentation Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/otp/" name="OTP" description="OpenDocument Presentation Template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/pot/" name="POT" description="PowerPoint 97–2003 Template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/potm/" name="POTM" description="PowerPoint Macro-Enabled Template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/potx/" name="POTX" description="PowerPoint Template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/pptx/" name="PPTX" description="Open XML Presentation Format" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
