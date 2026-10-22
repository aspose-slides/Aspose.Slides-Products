---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge PPS Files in C++
weight: 8570
url: /cpp/merger/pps/
description: Merge PPS files in C++. Use Aspose.Slides for C++ to clone slides from one PowerPoint slide show into another and save the merged result.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Merge PPS Files using C++" h2="Use Aspose.Slides for C++ to merge PPS files with server-side C++ APIs."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,OTP,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge PPS Files Using C++" %}}

To merge `PPS` files, use [Aspose.Slides for C++](/slides/cpp/), a C++ API for working with presentation files. Install the latest package from [NuGet](https://www.nuget.org/packages/Aspose.Slides.Cpp/) or use the Package Manager Console command below.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Command" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Merge PPS Files - C++" >}}
```cpp
auto destinationPresentation = MakeObject<Presentation>(u"first.pps");
auto sourcePresentation = MakeObject<Presentation>(u"second.pps");

for (auto&& slide : sourcePresentation->get_Slides())
{
    destinationPresentation->get_Slides()->AddClone(slide);
}

destinationPresentation->Save(u"merged.pps", SaveFormat::Pps);
sourcePresentation->Dispose();
destinationPresentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps for Merging PPS Files in C++" intro="Merge `PPS` files with [Aspose.Slides for C++](/slides/cpp/) by cloning slides from one presentation into another." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the destination and source `PPS` files with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through the source slides with `get_Slides`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add each slide to the destination presentation with `AddClone`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the merged file with `SaveFormat::Pps`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Aspose.Slides for C++ is supported on all major platforms and operating systems. Please make sure that you have the following prerequisites." %}}

-  Microsoft Windows, Linux, macOS, or another compatible OS with the supported C++ runtime.
-  Aspose.Slides for C++ library referenced in your project.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Merge Files Online"
  description="Merge presentations, documents, and images online." >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPS" readMoreLink="https://docs.fileformat.com/presentation/pps/" %}}

PPS (PowerPoint Slide Show) is the binary slide show format used by PowerPoint 97–2003. PPSX is the newer slide show format based on the Office Open XML standard. Current versions of PowerPoint can open PPS files and can still save presentations in PPS format. When opened normally, a PPS file starts in slide show mode, whereas a PPT file opens in editing mode.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Merging Formats" subTitle="You can also merge presentations in other formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/odp/" name="ODP" description="OpenDocument presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/otp/" name="OTP" description="OpenDocument presentation template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/pot/" name="POT" description="PowerPoint template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/potm/" name="POTM" description="Macro-enabled PowerPoint template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/potx/" name="POTX" description="PowerPoint Open XML template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/ppsm/" name="PPSM" description="Macro-enabled PowerPoint slide show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/ppsx/" name="PPSX" description="PowerPoint Open XML slide show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/ppt/" name="PPT" description="PowerPoint presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/pptm/" name="PPTM" description="Macro-enabled PowerPoint presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/pptx/" name="PPTX" description="PowerPoint Open XML presentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
