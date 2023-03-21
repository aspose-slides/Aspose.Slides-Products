---
title: Konwertuj PNG na SVG w Pythonie
url: /pl/python-net/conversion/png-to-svg/
keywords: PNG do SVG, Konwersja PNG do SVG, Python API, Python Library, PNG, SVG
description: Konwertuj PNG na SVG w Pythonie. Użyj interfejsu API biblioteki Pythona, aby przekonwertować pliki PNG na pliki SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konwertuj PNG na SVG w Pythonie" h2="Szybka i wieloplatformowa biblioteka Pythona, która pomaga w tworzeniu aplikacji z możliwością tworzenia, scalania, sprawdzania lub konwertowania plików prezentacji Microsoft PowerPoint i OpenOffice bez użycia oprogramowania takiego jak Microsoft lub Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj PNG na SVG w Pythonie" %}}

[**Aspose.Slides dla Pythona przez .NET**](https://products.aspose.com/slides/pl/python-net/) to potężna biblioteka Pythona do tworzenia i manipulowania plikami prezentacji. Ponadto zapewnia elastyczne sposoby konwersji PNG na SVG. Używając **Aspose.Slides dla Pythona przez .NET**, każdy programista lub aplikacja może konwertować pliki PNG na SVG za pomocą zaledwie kilku wierszy kodu Pythona.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla Pythona szybko eksportuje pliki PNG do formatów plików SVG. Biblioteka Aspose PowerPoint umożliwia konwersję PNG do SVG i wielu innych formatów plików

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj PNG na SVG za pomocą Pythona" %}}
Aby przekonwertować PNG na SVG, musisz utworzyć Prezentację z pliku PNG i zapisać ją jako SVG.

{{% blocks/products/pf/agp/code-block title="Kod Pythona do konwersji PNG na SVG" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for index in range(pres.slides.length):
        slide = pres.slides[index]

        with open("slide-{index}.svg".format(index = index), "wb") as file:
            slide.write_as_svg(file)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak przekonwertować PNG na SVG przy użyciu Aspose.Slides dla Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby przekonwertować PNG na SVG w Pythonie." >}}

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
Zapisz wynik jako plik SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Darmowy konwerter online" sectionDescription="[Jak przekonwertować PPT na HTML w Pythonie](https://products.aspose.com/slides/pl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Konwertuj PNG na inne obsługiwane formaty" subTitle="Możesz także przekonwertować PNG i zapisać do innych formatów plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/png-to-pdf/" name="PNG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}