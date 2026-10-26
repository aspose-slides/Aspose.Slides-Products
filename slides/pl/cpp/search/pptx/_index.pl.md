---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Wyszukiwanie tekstu w prezentacjach PPTX za pomocą C++
url: /pl/cpp/search/pptx/
description: Wyszukuj tekst w prezentacjach PPTX w C++. Użyj Aspose.Slides for C++, aby znajdować tekst w plikach prezentacji.
keywords: wyszukiwanie słów w PPTX, znajdowanie tekstu w PPTX, przeszukiwanie tekstu prezentacji PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Wyszukiwanie tekstu w PPTX za pomocą C++" h2="Użyj Aspose.Slides for C++, aby znajdować tekst w plikach prezentacji bez Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Wyszukiwanie tekstu w prezentacji PPTX w C++" variant="code" %}}

Aspose.Slides for C++ pozwala wyszukiwać tekst w prezentacjach PPTX. Użyj `SlideUtil::GetAllTextBoxes`, aby zebrać ramki tekstowe slajdu, a następnie sprawdź, czy ich tekst zawiera szukaną frazę.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Wyszukiwanie tekstu w prezentacji PPTX za pomocą C++" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak wyszukać tekst w PPTX w C++" intro="Wykonaj poniższe kroki, aby wyszukać tekst w prezentacji PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik PPTX za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pobierz wybrany slajd za pomocą `Presentation::get_Slides` i odczytaj jego ramki tekstowe za pomocą [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sprawdź, czy tekst każdej ramki zawiera szukaną frazę.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Zbudowano z Aspose.Slides" title="Wyszukiwanie tekstu w plikach PPTX online" description="Bezpłatna aplikacja Aspose.Slides Search została zbudowana z użyciem [Aspose.Slides for C++](https://products.aspose.com/slides/pl/cpp/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPTX." button="Otwórz Aspose.Slides Search" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides znajduje tekst, zanim napiszesz kod.
- Przeszukaj plik PPTX pod kątem zwykłego tekstu lub wyrażeń regularnych.
- Pobierz wyniki jako plik tekstowy.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty wyszukiwania" subTitle="Za pomocą C++ możesz także wyszukiwać tekst w następujących formatach." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/cpp/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
