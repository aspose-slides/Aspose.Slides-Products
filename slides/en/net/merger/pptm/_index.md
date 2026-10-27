---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge PPTM Files using .NET
weight: 5580
url: /net/merger/pptm/
description: C# source code to merge PPTM files with Aspose.Slides for .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Merge PPTM Files in C#" h2="Combine PPTM documents with server-side Aspose.Slides for .NET APIs."
  apiHomeLink="/slides/net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/net/"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge PPTM File Using C#" %}}

To merge PPTM files, use [Aspose.Slides for .NET](/slides/net/), a C# API for creating, converting, and combining presentation documents. Install the package from [NuGet](https://www.nuget.org/packages/Aspose.Slides.NET/) or run the following command in the Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Command" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Merge PPTM Files - C#" >}}
```cs
using var firstPresentation = new Presentation("first.pptm");
using var secondPresentation = new Presentation("second.pptm");
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

mergedPresentation.Save("merged.pptm", SaveFormat.Pptm);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps for Merging PPTM Files in C#" intro="Merge PPTM files with Aspose.Slides for .NET in a few lines of C# code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source PPTM files with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a destination `Presentation` object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add slides from each source file with `Slides.AddClone`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the merged presentation with `SaveFormat.Pptm`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the merged PPTM file in a compatible program.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Aspose.Slides for .NET is supported on major platforms and operating systems. Before running the code below, make sure that your system meets the following requirements." %}}

- A supported operating system with .NET or Mono installed.
-  Development environment like Microsoft Visual Studio
-  Aspose.Slides for .NET DLL referenced in your project - Install from NuGet using the Download button above

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTM" readMoreLink="https://docs.fileformat.com/presentation/pptm/" %}}

Files with the `.PPTM` extension are macro-enabled presentation files introduced with Microsoft PowerPoint 2007. They are similar to PPTX files, but PPTM files can store VBA macro code, whereas PPTX files cannot. PPTM files can be opened and edited in Microsoft PowerPoint. The related PPSM format opens in Slide Show view by default but can also be opened in PowerPoint for editing. Like PPTX files, PPTM files can contain text, images, videos, charts, and other presentation content.

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
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/ppt/" name="PPT" description="PowerPoint 97-2003 Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/merger/pptx/" name="PPTX" description="Open XML Presentation Format" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
