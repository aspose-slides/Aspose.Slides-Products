---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Wyodrębnianie tekstu z plików ODP w Pythonie
url: /pl/python-net/parser/odp/
description: Wyodrębniaj tekst i szczegóły formatowania tekstu z prezentacji ODP w Pythonie.
keywords: analiza ODP w Pythonie, parser ODP Python, wyodrębnianie danych z ODP w Pythonie, wyodrębnianie tekstu z ODP w Pythonie
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Wyodrębnianie tekstu z prezentacji ODP w Pythonie" h2="Twórz aplikacje w Pythonie, które za pomocą Aspose.Slides wyodrębniają tekst i szczegóły formatowania z prezentacji OpenDocument." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Wyodrębnianie tekstu z prezentacji ODP w Pythonie – przykład" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/pl/python-net/) udostępnia statyczną metodę [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) klasy `SlideUtil`. Zwraca ona obiekty `TextFrame` z całej prezentacji i może uwzględniać tekst ze slajdów wzorca. Poniższy przykład wyodrębnia tekst i powiązane szczegóły czcionki z prezentacji ODP.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Wyodrębnianie tekstu z prezentacji ODP – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.odp") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak wyodrębnić tekst z ODP w Pythonie" intro="Wykonaj poniższe kroki, aby wyodrębnić tekst z pliku ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otwórz plik ODP za pomocą `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj `SlideUtil.get_all_text_frames` i określ, czy uwzględnić slajdy wzorca.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Przejdź przez zwrócone obiekty `TextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Przejdź przez kolekcję `paragraphs` każdej ramki tekstowej.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Przejdź przez kolekcję `portions` każdego akapitu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Odczytaj `text` i właściwości formatowania bieżącego fragmentu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Zbudowano z Aspose.Slides" title="Wyodrębniaj tekst i obrazy online" description="Bezpłatna aplikacja Aspose.Slides Parser została zbudowana z użyciem [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pl/python-net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami ODP." button="Otwórz Aspose.Slides Parser" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides odczytuje Twoje pliki, zanim napiszesz kod.
- Prześlij plik ODP i otrzymaj jego tekst oraz obrazy.
- Pobierz wszystko jako jedno archiwum ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty do analizy" subTitle="W Pythonie możesz też wyodrębniać tekst z innych obsługiwanych formatów prezentacji." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
