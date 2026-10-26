---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Sök efter text i PPTX-presentationer med C++
url: /sv/cpp/search/pptx/
description: Sök efter text i PPTX-presentationer i C++. Använd Aspose.Slides for C++ för att hitta text i presentationsfiler.
keywords: sök efter ord i PPTX, hitta text i PPTX, sök i PPTX-presentationstext
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Sök efter text i PPTX med C++" h2="Använd Aspose.Slides for C++ för att hitta text i presentationsfiler utan Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sök efter text i en PPTX-presentation via C++" variant="code" %}}

Med Aspose.Slides for C++ kan du söka efter text i PPTX-presentationer. Använd `SlideUtil::GetAllTextBoxes` för att samla textramarna på en bild och kontrollera sedan om deras text innehåller den önskade frasen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Sök efter text i en PPTX-presentation med C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så söker du efter text i PPTX via C++" intro="Följ de här stegen för att söka efter text i en PPTX-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in PPTX-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hämta den önskade bilden med `Presentation::get_Slides` och dess textramar med [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kontrollera om texten i varje ram innehåller den önskade frasen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Byggd med Aspose.Slides" title="Sök efter text i PPTX-filer online" description="Den kostnadsfria appen Aspose.Slides Search är byggd med [Aspose.Slides for C++](https://products.aspose.com/slides/sv/cpp/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPTX-filer." button="Öppna Aspose.Slides Search" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides hittar text innan du skriver kod.
- Sök efter vanlig text eller reguljära uttryck i din PPTX-fil.
- Ladda ned träffarna som en textfil.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för sökning" subTitle="Med C++ kan du även söka efter text i följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/cpp/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
