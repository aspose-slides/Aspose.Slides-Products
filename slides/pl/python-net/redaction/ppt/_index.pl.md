---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Utajnianie tekstu w prezentacjach PPT za pomocą Pythona
url: /pl/python-net/redaction/ppt/
description: Wyszukuj i zamieniaj poufny tekst w prezentacjach PPT za pomocą Pythona.
keywords: utajnianie PPT, wyszukiwanie i zamiana tekstu w PPT, aktualizacja prezentacji PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Utajnianie tekstu w prezentacjach PPT za pomocą Pythona" h2="Twórz aplikacje w Pythonie, które wyszukują i zamieniają poufny tekst w prezentacjach za pomocą Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Utajnianie tekstu w prezentacji PPT za pomocą Pythona" variant="code" %}}

Dzięki [Aspose.Slides for Python via .NET](/slides/pl/python-net/) możesz zamienić poufny tekst w całej prezentacji PPT. Użyj `Presentation.replace_text` z `TextSearchOptions`, aby sterować wyszukiwaniem, a następnie zapisz zmodyfikowaną prezentację.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Utajnianie tekstu w prezentacji PPT – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.ppt") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak utajnić tekst w prezentacji PPT za pomocą Pythona" intro="Wykonaj poniższe kroki, aby zamienić poufny tekst w prezentacji PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otwórz plik PPT za pomocą `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Użyj [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) z `TextSearchOptions`, aby zamienić wybrany tekst.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz zmodyfikowaną prezentację przy użyciu `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Zbudowano z Aspose.Slides" title="Utajnianie plików PPT online" description="Bezpłatna aplikacja Aspose.Slides Redaction została zbudowana z użyciem [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pl/python-net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPT." button="Otwórz Aspose.Slides Redaction" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides wyszukuje i zamienia tekst, zanim napiszesz kod.
- Wyszukuj i zamieniaj tekst w pliku PPT, także za pomocą wyrażeń regularnych.
- Pobierz utajniony plik.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty utajniania" subTitle="Używaj Pythona do utajniania tekstu w innych obsługiwanych formatach prezentacji." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
