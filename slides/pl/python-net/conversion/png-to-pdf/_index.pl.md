---
title: Konwertuj PNG na PDF w Pythonie
url: /pl/python-net/conversion/png-to-pdf/
keywords: PNG do PDF, Konwersja PNG do PDF, Python API, Python Library, PNG, PDF
description: Konwertuj PNG na PDF w Pythonie. Użyj interfejsu API biblioteki Pythona, aby przekonwertować pliki PNG na pliki PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konwertuj PNG na PDF w Pythonie" h2="Szybka i wieloplatformowa biblioteka Pythona, która pomaga w tworzeniu aplikacji z możliwością tworzenia, scalania, sprawdzania lub konwertowania plików prezentacji Microsoft PowerPoint i OpenOffice bez użycia oprogramowania takiego jak Microsoft lub Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj PNG na PDF w Pythonie" %}}

[**Aspose.Slides dla Pythona przez .NET**](https://products.aspose.com/slides/pl/python-net/) to potężna biblioteka Pythona do tworzenia i manipulowania plikami prezentacji. Ponadto zapewnia elastyczne sposoby konwersji PNG na PDF. Używając **Aspose.Slides dla Pythona przez .NET**, każdy programista lub aplikacja może konwertować pliki PNG na PDF za pomocą zaledwie kilku wierszy kodu Pythona.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla Pythona szybko eksportuje pliki PNG do formatów plików PDF. Biblioteka Aspose PowerPoint umożliwia konwersję PNG do PDF i wielu innych formatów plików

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj PNG na PDF za pomocą Pythona" %}}
Aby przekonwertować PNG na PDF, musisz utworzyć Prezentację z pliku PNG i zapisać ją jako PDF.

{{% blocks/products/pf/agp/code-block title="Kod Pythona do konwersji PNG na PDF" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    pres.save("index.pdf", slides.export.SaveFormat.PDF)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak przekonwertować PNG na PDF przy użyciu Aspose.Slides dla Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby przekonwertować PNG na PDF w Pythonie." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/pl/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do swojego projektu w Pythonie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otwórz źródłowe pliki PNG w Pythonie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik jako plik PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konwertuj PNG na inne obsługiwane formaty" subTitle="Możesz także przekonwertować PNG i zapisać do innych formatów plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}