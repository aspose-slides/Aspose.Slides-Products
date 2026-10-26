---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Wyszukiwanie tekstu w plikach prezentacji PPT za pomocą Javy
url: /pl/java/search/ppt/
description: Wyszukuj tekst w prezentacjach PPT w Javie za pomocą Aspose.Slides for Java.
keywords: wyszukiwanie słów w PPT, wyszukiwanie tekstu w PPT, przeszukiwanie tekstu prezentacji PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Wyszukiwanie tekstu w PPT za pomocą Javy" h2="Twórz aplikacje Java, które wyszukują tekst w plikach prezentacji za pomocą interfejsów API po stronie serwera." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Wyszukiwanie tekstu w prezentacji PPT w Javie" variant="code" %}}

Dzięki [Aspose.Slides for Java](/slides/pl/java/) możesz wyszukiwać tekst w prezentacjach PPT. Użyj metody `SlideUtil.getAllTextBoxes`, aby zebrać ramki tekstowe, a następnie przeanalizuj obiekty `ITextFrame`, `IParagraph` i `IPortion`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Wyszukiwanie tekstu w prezentacji PPT za pomocą Javy" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak wyszukać tekst w PPT w Javie" intro="Wykonaj poniższe kroki, aby wyszukać tekst w prezentacji PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik PPT za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj metodę `SlideUtil.getAllTextBoxes`, aby zebrać ramki tekstowe z każdego slajdu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Przeanalizuj obiekty `ITextFrame`, `IParagraph` i `IPortion`, aby znaleźć pasujący tekst.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Zbudowano z Aspose.Slides" title="Wyszukiwanie tekstu w plikach PPT online" description="Bezpłatna aplikacja Aspose.Slides Search została zbudowana z użyciem [Aspose.Slides for Java](https://products.aspose.com/slides/pl/java/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPT." button="Otwórz Aspose.Slides Search" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides znajduje tekst, zanim napiszesz kod.
- Przeszukaj plik PPT pod kątem zwykłego tekstu lub wyrażeń regularnych.
- Pobierz wyniki jako plik tekstowy.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty wyszukiwania" subTitle="Za pomocą Javy możesz także wyszukiwać tekst w następujących formatach." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
