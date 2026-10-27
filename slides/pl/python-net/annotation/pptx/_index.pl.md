---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Usuwanie komentarzy z PPTX w Pythonie
url: /pl/python-net/annotation/pptx/ 
description: Usuwaj komentarze i autorów komentarzy z prezentacji PPTX w Pythonie za pomocą Aspose.Slides for Python via .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Usuwanie komentarzy i autorów komentarzy z PPTX w Pythonie" h2="Użyj Aspose.Slides for Python via .NET, aby usuwać komentarze z prezentacji wraz z ich autorami." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Usuwanie komentarzy z PPTX za pomocą Pythona" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/pl/python-net/) zapewnia dostęp do komentarzy i autorów komentarzy zapisanych w prezentacji PPTX. Wczytaj plik za pomocą `Presentation`, wyczyść kolekcję `comments` każdego autora, wyczyść `comment_authors` i zapisz wynik w formacie PPTX.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Usuwanie komentarzy z PPTX w Pythonie" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak usunąć komentarze z PPTX za pomocą Pythona" intro="Wykonaj poniższe kroki, aby usunąć wszystkie komentarze i autorów komentarzy z prezentacji PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj [Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otwórz plik PPTX za pomocą `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Przejdź przez `comment_authors` i wyczyść kolekcję `comments` każdego autora.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wyczyść kolekcję `comment_authors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj `save` z `SaveFormat.PPTX`, aby zapisać zaktualizowaną prezentację PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Zbudowano z Aspose.Slides" title="Usuwanie komentarzy z PPTX online" description="Bezpłatna aplikacja Aspose.Slides Annotation została zbudowana z użyciem [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pl/python-net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPTX." button="Otwórz Aspose.Slides Annotation" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides usuwa komentarze, zanim napiszesz kod.
- Usuń wszystkie komentarze z pliku PPTX.
- Pobierz oczyszczony plik.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty adnotacji" subTitle="Za pomocą Pythona możesz także usuwać adnotacje z innych formatów." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
