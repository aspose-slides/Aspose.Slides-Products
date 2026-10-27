---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 360
title: Usuwanie adnotacji z PPTX za pomocą Javy
url: /pl/java/annotation/pptx/ 
description: Usuwaj komentarze i autorów komentarzy z prezentacji PPTX w Javie za pomocą Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Usuwanie komentarzy i autorów komentarzy z PPTX w Javie" h2="Użyj Aspose.Slides for Java, aby usuwać komentarze i autorów komentarzy z plików prezentacji." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Usuwanie komentarzy z PPTX w Javie" variant="code" %}}

Aspose.Slides for Java pozwala usuwać komentarze i autorów komentarzy z prezentacji PPTX. Wczytaj plik za pomocą klasy `Presentation`, przejdź przez obiekty `ICommentAuthor` z `getCommentAuthors`, wyczyść ich komentarze i zapisz zaktualizowaną prezentację.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Usuwanie adnotacji z PPTX – Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak usunąć komentarze z PPTX w Javie" intro="Wykonaj poniższe kroki, aby usunąć komentarze i autorów komentarzy z prezentacji PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj Aspose.Slides for Java. Zobacz [Instalacja](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik PPTX za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Przejdź przez obiekty `ICommentAuthor` z `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wyczyść komentarze każdego autora za pomocą `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wyczyść kolekcję autorów komentarzy i zapisz zaktualizowany plik PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Zbudowano z Aspose.Slides" title="Usuwanie komentarzy z PPTX online" description="Bezpłatna aplikacja Aspose.Slides Annotation została zbudowana z użyciem [Aspose.Slides for Java](https://products.aspose.com/slides/pl/java/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPTX." button="Otwórz Aspose.Slides Annotation" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides usuwa komentarze, zanim napiszesz kod.
- Usuń wszystkie komentarze z pliku PPTX.
- Pobierz oczyszczony plik.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty adnotacji" subTitle="Za pomocą Javy możesz także usuwać adnotacje z innych formatów." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
