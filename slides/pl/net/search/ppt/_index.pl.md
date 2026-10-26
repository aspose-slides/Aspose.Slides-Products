---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Wyszukiwanie tekstu w plikach prezentacji PPT za pomocą .NET
url: /pl/net/search/ppt/
description: Kod źródłowy C# do wyszukiwania tekstu w prezentacjach PPT.
keywords: Wyszukiwanie tekstu w PPT, znajdowanie tekstu w PPT, przeszukiwanie tekstu prezentacji PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Wyszukiwanie tekstu w plikach PPT za pomocą C#" h2="Twórz aplikacje .NET, które znajdują tekst w prezentacjach za pomocą interfejsów API po stronie serwera." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Wyszukiwanie tekstu w prezentacji PPT za pomocą C#" variant="code" %}}

Dzięki [Aspose.Slides for .NET](/slides/pl/net/) możesz wyszukiwać tekst w prezentacji PPT. Pobierz ramki tekstowe slajdu za pomocą `SlideUtil.GetAllTextBoxes`, a następnie sprawdź ich wartości `Text` pod kątem szukanej frazy.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Wyszukiwanie tekstu w prezentacji PPT za pomocą C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak wyszukać tekst w prezentacji PPT za pomocą C#" intro="Wykonaj poniższe kroki, aby wyszukać tekst w prezentacji PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik PPT za pomocą `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pobierz wybrany slajd z `Presentation.Slides` i przypisz go do zmiennej.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pobierz jego ramki tekstowe za pomocą [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sprawdź, czy wartość `Text` każdej ramki zawiera szukaną frazę.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Zbudowano z Aspose.Slides" title="Wyszukiwanie tekstu w plikach PPT online" description="Bezpłatna aplikacja Aspose.Slides Search została zbudowana z użyciem [Aspose.Slides for .NET](https://products.aspose.com/slides/pl/net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPT." button="Otwórz Aspose.Slides Search" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides znajduje tekst, zanim napiszesz kod.
- Przeszukaj plik PPT pod kątem zwykłego tekstu lub wyrażeń regularnych.
- Pobierz wyniki jako plik tekstowy.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty wyszukiwania" subTitle="Za pomocą C# możesz także wyszukiwać tekst w następujących formatach." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
