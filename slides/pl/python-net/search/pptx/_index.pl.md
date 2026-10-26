---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Wyszukiwanie tekstu w prezentacjach PPTX za pomocą Pythona
url: /pl/python-net/search/pptx/
description: Wyszukuj tekst w prezentacjach PPTX za pomocą Pythona i Aspose.Slides.
keywords: wyszukiwanie tekstu w PPTX, znajdowanie słów w PPTX, przeszukiwanie prezentacji PPTX w Pythonie
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Wyszukiwanie tekstu w prezentacjach PPTX za pomocą Pythona" h2="Twórz aplikacje w Pythonie, które znajdują tekst w prezentacjach PowerPoint za pomocą Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Wyszukiwanie tekstu w prezentacji PPTX za pomocą Pythona" variant="code" %}}

Dzięki [Aspose.Slides for Python via .NET](/slides/pl/python-net/) możesz użyć [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/), aby znaleźć na każdym slajdzie ramki tekstowe zawierające podany ciąg znaków.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Wyszukiwanie tekstu w prezentacji PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak wyszukać tekst w PPTX za pomocą Pythona" intro="Wykonaj poniższe kroki, aby wyszukać tekst w prezentacji PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otwórz plik PPTX za pomocą `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Przejdź przez slajdy i wywołaj [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) dla każdego z nich.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Odczytaj właściwość `text` każdej znalezionej ramki tekstowej.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Zbudowano z Aspose.Slides" title="Wyszukiwanie tekstu w plikach PPTX online" description="Bezpłatna aplikacja Aspose.Slides Search została zbudowana z użyciem [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pl/python-net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPTX." button="Otwórz Aspose.Slides Search" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides znajduje tekst, zanim napiszesz kod.
- Przeszukaj plik PPTX pod kątem zwykłego tekstu lub wyrażeń regularnych.
- Pobierz wyniki jako plik tekstowy.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty wyszukiwania" subTitle="Używaj Pythona do wyszukiwania tekstu w innych obsługiwanych formatach prezentacji." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
