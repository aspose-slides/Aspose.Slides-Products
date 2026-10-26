---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Utajnianie plików prezentacji PPTX za pomocą Javy
url: /pl/java/redaction/pptx/
description: Wyszukuj i zamieniaj tekst w prezentacjach PPTX w Javie za pomocą Aspose.Slides for Java.
keywords: utajnianie PPTX, wyszukiwanie i zamiana tekstu w PPTX, aktualizacja prezentacji PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Utajnianie PPTX za pomocą Javy" h2="Twórz aplikacje Java, które wyszukują i zamieniają tekst w plikach prezentacji za pomocą interfejsów API po stronie serwera." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Utajnianie prezentacji PPTX w Javie" variant="code" %}}

Dzięki [Aspose.Slides for Java](/slides/pl/java/) możesz wyszukiwać i zamieniać tekst w prezentacjach PPTX. Użyj metody `SlideUtil.findAndReplaceText`, aby przeszukać prezentację i zamienić pasujący tekst na nową wartość.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Utajnianie prezentacji PPTX za pomocą Javy" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak utajnić PPTX w Javie" intro="Wykonaj poniższe kroki, aby utajnić prezentację PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik PPTX za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj metodę `SlideUtil.findAndReplaceText`, aby wyszukać i zamienić tekst.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz zaktualizowaną prezentację przy użyciu `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Zbudowano z Aspose.Slides" title="Utajnianie plików PPTX online" description="Bezpłatna aplikacja Aspose.Slides Redaction została zbudowana z użyciem [Aspose.Slides for Java](https://products.aspose.com/slides/pl/java/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPTX." button="Otwórz Aspose.Slides Redaction" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides wyszukuje i zamienia tekst, zanim napiszesz kod.
- Wyszukuj i zamieniaj tekst w pliku PPTX, także za pomocą wyrażeń regularnych.
- Pobierz utajniony plik.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty utajniania" subTitle="Za pomocą Javy możesz także utajniać następujące formaty." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
