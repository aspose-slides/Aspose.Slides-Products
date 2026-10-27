---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Usuwanie adnotacji z PPT za pomocą C++
url: /pl/cpp/annotation/ppt/ 
description: Kod źródłowy C++ do usuwania adnotacji z prezentacji PPT.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Usuwanie komentarzy i autorów komentarzy z PPT w C++" h2="Twórz aplikacje C++, które zarządzają komentarzami i autorami w plikach prezentacji za pomocą interfejsów API po stronie serwera." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Usuwanie komentarzy z PPT w C++" variant="code" %}}

Użyj [Aspose.Slides for C++](/slides/pl/cpp/), aby usunąć komentarze i autorów komentarzy z prezentacji PPT. Poniższy przykład czyści komentarze każdego autora z `get_CommentAuthors`, a następnie czyści kolekcję autorów komentarzy.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Usuwanie adnotacji z PPT – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.ppt");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak usunąć komentarze z PPT w C++" intro="Wykonaj poniższe kroki, aby usunąć komentarze i autorów komentarzy z prezentacji PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj Aspose.Slides for C++. Zobacz [Instalacja](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik PPT za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Przejdź przez autorów komentarzy z `get_CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wyczyść komentarze każdego autora za pomocą `get_Comments()->Clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wyczyść kolekcję autorów komentarzy.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz zaktualizowaną prezentację przy użyciu `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Zbudowano z Aspose.Slides" title="Usuwanie komentarzy z PPT online" description="Bezpłatna aplikacja Aspose.Slides Annotation została zbudowana z użyciem [Aspose.Slides for C++](https://products.aspose.com/slides/pl/cpp/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPT." button="Otwórz Aspose.Slides Annotation" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides usuwa komentarze, zanim napiszesz kod.
- Usuń wszystkie komentarze z pliku PPT.
- Pobierz oczyszczony plik.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty adnotacji" subTitle="Za pomocą C++ możesz także usuwać adnotacje z innych formatów." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/cpp/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
