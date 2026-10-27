---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Usuwanie adnotacji z PPT za pomocą .NET
url: /pl/net/annotation/ppt/ 
description: Usuwaj komentarze i autorów komentarzy z prezentacji PPT w C#.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Usuwanie komentarzy i autorów komentarzy z PPT w C#" h2="Twórz aplikacje .NET, które zarządzają komentarzami i autorami w plikach prezentacji za pomocą interfejsów API po stronie serwera." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Usuwanie komentarzy z PPT w C#" variant="code" %}}

Użyj [Aspose.Slides for .NET](/slides/pl/net/), aby usunąć komentarze i autorów komentarzy z plików prezentacji PPT. Poniższy przykład czyści kolekcję `Comments` każdego autora, a następnie kolekcję `CommentAuthors` prezentacji.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Usuwanie adnotacji z PPT – C#" >}}
```cs
using var presentation = new Presentation("example.ppt");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak usunąć komentarze z PPT w C#" intro="Wykonaj poniższe kroki, aby usunąć komentarze i autorów komentarzy z prezentacji PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj Aspose.Slides for .NET. Zobacz [Instalacja](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik PPT za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Przejdź przez kolekcję `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wyczyść kolekcję `Comments` każdego autora komentarzy.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wyczyść kolekcję `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz zaktualizowaną prezentację przy użyciu `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Zbudowano z Aspose.Slides" title="Usuwanie komentarzy z PPT online" description="Bezpłatna aplikacja Aspose.Slides Annotation została zbudowana z użyciem [Aspose.Slides for .NET](https://products.aspose.com/slides/pl/net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPT." button="Otwórz Aspose.Slides Annotation" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides usuwa komentarze, zanim napiszesz kod.
- Usuń wszystkie komentarze z pliku PPT.
- Pobierz oczyszczony plik.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty adnotacji" subTitle="Za pomocą C# możesz także usuwać adnotacje z innych formatów." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
