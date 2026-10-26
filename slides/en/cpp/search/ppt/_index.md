---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Search Text in PPT Presentations using C++
url: /cpp/search/ppt/
keywords: search words in PPT, find text in PPT, search text PPT Presentation
description: Search text in PPT presentations in C++. Use Aspose.Slides for C++ to find text in presentation files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Search Text in PPT using C++" h2="Use Aspose.Slides for C++ to find text in presentation files without Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Search Text in a PPT Presentation via C++" variant="code" %}}

Aspose.Slides for C++ lets you search text in PPT presentations. Use `SlideUtil::GetAllTextBoxes` to collect the text frames of a slide, then check their text for the required phrase.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Search Text in a PPT Presentation using C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Search Text in PPT via C++" intro="Follow these steps to search text in a PPT presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPT file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Get the required slide from `Presentation::get_Slides` and retrieve its text frames with [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Check the text of each frame for the required phrase.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Search Formats" subTitle="Using C++, you can also search text in the following formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
