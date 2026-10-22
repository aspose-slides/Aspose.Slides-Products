---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge PPTM Files in C++
weight: 8630
url: /cpp/merger/pptm/
description: Merge PPTM files in C++. Use Aspose.Slides for C++ to clone slides from one macro-enabled presentation into another and save the merged result.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Merge PPTM Files using C++" h2="Use Aspose.Slides for C++ to merge PPTM files with server-side C++ APIs."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge PPTM Files Using C++" %}}

To merge `PPTM` files, use [Aspose.Slides for C++](/slides/cpp/), a C++ API for working with presentation files. Install the latest package from [NuGet](https://www.nuget.org/packages/Aspose.Slides.Cpp/) or use the Package Manager Console command below.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Command" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Merge PPTM Files - C++" >}}
```cpp
auto destinationPresentation = MakeObject<Presentation>(u"first.pptm");
auto sourcePresentation = MakeObject<Presentation>(u"second.pptm");

for (auto&& slide : sourcePresentation->get_Slides())
{
    destinationPresentation->get_Slides()->AddClone(slide);
}

destinationPresentation->Save(u"merged.pptm", SaveFormat::Pptm);
sourcePresentation->Dispose();
destinationPresentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps for Merging PPTM Files in C++" intro="Merge `PPTM` files with [Aspose.Slides for C++](/slides/cpp/) by cloning slides from one presentation into another." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the destination and source `PPTM` files with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through the source slides with `get_Slides`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add each slide to the destination presentation with `AddClone`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the merged file with `SaveFormat::Pptm`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Aspose.Slides for C++ is supported on all major platforms and operating systems. Please make sure that you have the following prerequisites." %}}

-  Microsoft Windows, Linux, macOS, or another compatible OS with the supported C++ runtime.
-  Aspose.Slides for C++ library referenced in your project.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Merge Files Online"
  description="Merge presentations, documents, and images online." >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTM" readMoreLink="https://docs.fileformat.com/presentation/pptm/" %}}

Files with the `.PPTM` extension are macro-enabled presentation files introduced with Microsoft PowerPoint 2007. They are similar to PPTX files, but PPTM files can store VBA macro code, whereas PPTX files cannot. PPTM files can be opened and edited in Microsoft PowerPoint. The related PPSM format opens in Slide Show view by default but can also be opened in PowerPoint for editing. Like PPTX files, PPTM files can contain text, images, videos, charts, and other presentation content.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Merging Formats" subTitle="You can also merge presentations in other formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/odp/" name="ODP" description="OpenDocument presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/otp/" name="OTP" description="OpenDocument presentation template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/pot/" name="POT" description="PowerPoint template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/potm/" name="POTM" description="Macro-enabled PowerPoint template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/potx/" name="POTX" description="PowerPoint Open XML template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/pps/" name="PPS" description="PowerPoint slide show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/ppsm/" name="PPSM" description="Macro-enabled PowerPoint slide show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/ppsx/" name="PPSX" description="PowerPoint Open XML slide show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/ppt/" name="PPT" description="PowerPoint presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/merger/pptx/" name="PPTX" description="PowerPoint Open XML presentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
