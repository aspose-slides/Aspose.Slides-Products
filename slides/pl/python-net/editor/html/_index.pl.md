---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edytuj kod HTML w Pythonie
url: /pl/python-net/editor/html/
keywords: Edytuj HTML, HTML, Python API, Python Library
description: Edytuj kod HTML w Pythonie. Użyj interfejsu API biblioteki Pythona, aby edytować plik HTML
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edytuj kod HTML w Pythonie" h2="Szybka i wieloplatformowa biblioteka Pythona do edycji HTML przy użyciu kodu Pythona" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edytuj kod HTML w Pythonie" variant="code" %}}

Używając [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/pl/python-net/), możesz dodać nowy wiersz tekstu do dokumentu HTML za pomocą zaledwie kilku linie kodu.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod Pythona do edycji HTML" >}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    with open("page.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("page.html", slides.export.SaveFormat.HTML5)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edytuj HTML za pomocą Aspose.Slides" %}}

[**Aspose.Slides for Python przez .NET**](https://products.aspose.com/slides/pl/python-net/) to potężna biblioteka Pythona używana do manipulowania i edytowania prezentacji, dokumentów HTML i innych plików . Możesz edytować dokument HTML, dodając do niego nowy wiersz tekstu.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak edytować HTML w Pythonie" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj bibliotekę jako odniesienie w swoim projekcie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utwórz wystąpienie klasy Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Załaduj dokument HTML, który chcesz edytować.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj nowy wiersz tekstu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz zmieniony plik HTML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Zbudowano z Aspose.Slides" title="Edytuj pliki PPTX online" description="Bezpłatna aplikacja Aspose.Slides Editor została zbudowana z użyciem [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pl/python-net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPTX." button="Otwórz Aspose.Slides Editor" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides przetwarza Twoje pliki, zanim napiszesz kod.
- Prześlij pliki PPTX i od razu je edytuj.
- Zapisz i pobierz edytowany plik.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Edytuj inne pliki" subTitle="Możesz także edytować pliki w innych formatach" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
