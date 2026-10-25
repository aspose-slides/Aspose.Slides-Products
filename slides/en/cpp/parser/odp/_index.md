---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Extract Text from ODP Presentations using C++
weight: 460
url: /cpp/parser/odp/
description: Extract text from ODP presentations in C++. Use Aspose.Slides for C++ to parse slides, text frames, paragraphs, and portions.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Parse ODP Presentations in C++" h2="Use Aspose.Slides for C++ to extract text from presentation slides without Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Parse ODP File Using C++" %}}

Use Aspose.Slides for C++ to parse ODP presentation files and extract text from slides. The API exposes slide text through `SlideUtil::GetAllTextBoxes`, `ITextFrame`, `IParagraph`, and `IPortion`, so you can read text content without automating Microsoft PowerPoint. Install the [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) package from NuGet or use the Package Manager Console command below.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Command" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Parse ODP Files - C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Parse ODP Files in C++" intro="Extract text from ODP files with Aspose.Slides for C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the ODP file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Get the `ITextFrame` objects from the first slide with `SlideUtil::GetAllTextBoxes`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Loop through the `ITextFrame` objects.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Loop through the `IParagraph` objects in each `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Loop through the `IPortion` objects in each `IParagraph`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Read the text with `get_Text`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Aspose.Slides for C++ supports major desktop and server platforms. Make sure that your project has the following prerequisites." %}}

-  Microsoft Windows, Linux, macOS, or another compatible OS with the supported C++ runtime.
-  Aspose.Slides for C++ library referenced in your project.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

An ODP file is an OpenDocument presentation file used by applications such as OpenOffice Impress and LibreOffice Impress. It stores slides, text, images, formatting, animations, and other presentation content in an open XML-based package.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Parsing Formats" subTitle="You can also parse other presentation formats with C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/parser/ppt/" name="PPT" description="PowerPoint 97-2003 Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/parser/pptx/" name="PPTX" description="PowerPoint Open XML Presentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
