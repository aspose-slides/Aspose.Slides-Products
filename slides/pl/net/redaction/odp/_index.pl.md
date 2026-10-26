---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Utajnianie plików prezentacji ODP za pomocą .NET
url: /pl/net/redaction/odp/
description: Kod źródłowy C# do wyszukiwania i zamiany tekstu w prezentacjach ODP.
keywords: Utajnianie ODP, wyszukiwanie i zamiana tekstu w ODP, aktualizacja prezentacji ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Utajnianie plików ODP za pomocą C#" h2="Twórz aplikacje .NET, które wyszukują i zamieniają tekst w prezentacjach za pomocą interfejsów API po stronie serwera." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Utajnianie prezentacji ODP za pomocą C#" variant="code" %}}

Dzięki [Aspose.Slides for .NET](/slides/pl/net/) możesz wyszukiwać i zamieniać tekst w prezentacji ODP. Użyj `Presentation.ReplaceText` z `TextSearchOptions`, aby sterować wyszukiwaniem, a następnie zapisz zmodyfikowaną prezentację.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Utajnianie prezentacji ODP za pomocą C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak utajnić prezentację ODP za pomocą C#" intro="Wykonaj poniższe kroki, aby zamienić tekst w prezentacji ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik ODP za pomocą `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Użyj [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) z `TextSearchOptions`, aby zamienić wybrany tekst.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz zmodyfikowaną prezentację przy użyciu `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Zbudowano z Aspose.Slides" title="Utajnianie plików ODP online" description="Bezpłatna aplikacja Aspose.Slides Redaction została zbudowana z użyciem [Aspose.Slides for .NET](https://products.aspose.com/slides/pl/net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami ODP." button="Otwórz Aspose.Slides Redaction" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides wyszukuje i zamienia tekst, zanim napiszesz kod.
- Wyszukuj i zamieniaj tekst w pliku ODP, także za pomocą wyrażeń regularnych.
- Pobierz utajniony plik.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty utajniania" subTitle="Za pomocą C# możesz także utajniać następujące formaty." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
