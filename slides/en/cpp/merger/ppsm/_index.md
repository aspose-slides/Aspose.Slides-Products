---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge PPSM Files in C++
weight: 290
url: /cpp/merger/ppsm/
description: Merge PPSM files in C++. Use Aspose.Slides for C++ to clone slides from one macro-enabled slide show into another and save the merged result.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Merge PPSM Files using C++" h2="Use Aspose.Slides for C++ to merge PPSM files with server-side C++ APIs."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge PPSM Files Using C++" %}}

To merge `PPSM` files, use [Aspose.Slides for C++](/slides/cpp/), a C++ API for working with presentation files. Install the latest package from [NuGet](https://www.nuget.org/packages/Aspose.Slides.Cpp/) or use the Package Manager Console command below.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Command" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Merge PPSM Files - C++" >}}
```cpp
auto destinationPresentation = MakeObject<Presentation>(u"first.ppsm");
auto sourcePresentation = MakeObject<Presentation>(u"second.ppsm");

for (auto&& slide : sourcePresentation->get_Slides())
{
    destinationPresentation->get_Slides()->AddClone(slide);
}

destinationPresentation->Save(u"merged.ppsm", SaveFormat::Ppsm);
sourcePresentation->Dispose();
destinationPresentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps for Merging PPSM Files in C++" intro="Merge `PPSM` files with [Aspose.Slides for C++](/slides/cpp/) by cloning slides from one presentation into another." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the destination and source `PPSM` files with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through the source slides with `get_Slides`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add each slide to the destination presentation with `AddClone`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the merged file with `SaveFormat::Ppsm`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Aspose.Slides for C++ is supported on all major platforms and operating systems. Please make sure that you have the following prerequisites." %}}

-  Microsoft Windows, Linux, macOS, or another compatible OS with the supported C++ runtime.
-  Aspose.Slides for C++ library referenced in your project.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Merge Files Online"
  description="Merge presentations, documents, and images online." >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSM" readMoreLink="https://docs.fileformat.com/presentation/ppsm/" %}}

Files with the PPSM extension are macro-enabled slide show files introduced with Microsoft PowerPoint 2007. Unlike PPTM, PPSM opens in Slide Show view by default. This default opening mode is not file protection; a PPSM file can also be opened in Microsoft PowerPoint for editing.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Merging Formats" subTitle="You can also merge presentations in other formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/odp/" name="ODP" description="OpenDocument presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/otp/" name="OTP" description="OpenDocument presentation template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/pot/" name="POT" description="PowerPoint template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/potm/" name="POTM" description="Macro-enabled PowerPoint template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/potx/" name="POTX" description="PowerPoint Open XML template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/pps/" name="PPS" description="PowerPoint slide show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/ppsx/" name="PPSX" description="PowerPoint Open XML slide show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/ppt/" name="PPT" description="PowerPoint presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/pptm/" name="PPTM" description="Macro-enabled PowerPoint presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/pptx/" name="PPTX" description="PowerPoint Open XML presentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
