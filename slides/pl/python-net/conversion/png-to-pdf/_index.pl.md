---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj PNG na PDF w Pythonie
url: /pl/python-net/conversion/png-to-pdf/
keywords: PNG do PDF, Konwersja PNG do PDF, Python API, Python Library, PNG, PDF
description: Konwertuj PNG na PDF w Pythonie. Użyj interfejsu API biblioteki Pythona, aby przekonwertować pliki PNG na pliki PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj PNG na PDF w Pythonie" h2="Szybka i wieloplatformowa biblioteka Pythona, która pomaga w tworzeniu aplikacji z możliwością tworzenia, scalania, sprawdzania lub konwertowania plików prezentacji Microsoft PowerPoint i OpenOffice bez użycia oprogramowania takiego jak Microsoft lub Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PNG na PDF za pomocą Pythona" variant="code" %}}

Aby przekonwertować PNG na PDF, musisz utworzyć Prezentację z pliku PNG i zapisać ją jako PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod Pythona do konwersji PNG na PDF" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    pres.save("index.pdf", slides.export.SaveFormat.PDF)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PNG na PDF w Pythonie" %}}

[**Aspose.Slides dla Pythona przez .NET**](https://products.aspose.com/slides/pl/python-net/) to potężna biblioteka Pythona do tworzenia i manipulowania plikami prezentacji. Ponadto zapewnia elastyczne sposoby konwersji PNG na PDF. Używając **Aspose.Slides dla Pythona przez .NET**, każdy programista lub aplikacja może konwertować pliki PNG na PDF za pomocą zaledwie kilku wierszy kodu Pythona.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla Pythona szybko eksportuje pliki PNG do formatów plików PDF. Biblioteka Aspose PowerPoint umożliwia konwersję PNG do PDF i wielu innych formatów plików

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować PNG na PDF przy użyciu Aspose.Slides dla Python API" intro="Oto kroki, aby przekonwertować PNG na PDF w Pythonie." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/pl/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do swojego projektu w Pythonie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otwórz źródłowe pliki PNG w Pythonie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz wynik jako plik PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Zbudowano z Aspose.Slides" title="Konwertuj PNG na PDF online" description="Bezpłatna aplikacja Aspose.Slides Conversion została zbudowana z użyciem [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pl/python-net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PNG." button="Otwórz Aspose.Slides Conversion" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" upload="Upuść lub prześlij plik" saveAs="Zapisz jako" convert="Konwertuj" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides konwertuje pliki, zanim napiszesz kod.
- Prześlij pliki PNG i zapisz je jako PDF.
- Pobierz wynik lub przekonwertuj kolejne pliki.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konwertuj PNG na inne obsługiwane formaty" subTitle="Możesz także przekonwertować PNG i zapisać do innych formatów plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
