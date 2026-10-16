---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj POT na SVG w JavaScript
url: /pl/nodejs-net/conversion/pot-to-svg/
keywords: POT na SVG, Konwertuj POT na SVG, API Node.js, Biblioteka JavaScript, POT, SVG
description: Konwertuj POT na SVG w JavaScript. Użyj API biblioteki Node.js, aby przekonwertować pliki POT na SVG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj POT na SVG w JavaScript" h2="Aspose.Slides dla Node.js za pośrednictwem .NET to potężna i łatwa w obsłudze biblioteka, która umożliwia konwersję prezentacji PowerPoint do różnych formatów w JavaScript. Obsługuje wszystkie elementy i formaty prezentacji oraz zapewnia bogate API umożliwiające dostęp i modyfikację ich. Umożliwia także eksport slajdów do różnych formatów w celu dalszego przetwarzania lub udostępniania." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj POT na SVG za pomocą JavaScript" variant="code" %}}

Aby przekonwertować plik POT na SVG, musisz utworzyć prezentację z pliku POT i zapisać ją jako SVG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod JavaScript do konwersji POT na SVG" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pot");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slideByteArray = pres.slides.get(i).getAsSvg();
        fs.writeFile('slide" + i + ".svg', Buffer.from(slideByteArray), (err) => {
            if (err)
                console.error(err);
        });
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj POT na SVG w Node.js" %}}

[**Aspose.Slides dla Node.js przez .NET**](https://products.aspose.com/slides/pl/nodejs-net/) to potężna biblioteka Node.js do tworzenia plików prezentacji i manipulowania nimi. Ponadto zapewnia elastyczne sposoby konwersji POT na SVG. Używając **Aspose.Slides dla Node.js za pośrednictwem .NET**, każdy programista lub aplikacja może przekonwertować pliki POT na pliki SVG za pomocą zaledwie kilku linijek kodu.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla Node.js za pośrednictwem .NET szybko eksportuje pliki POT do formatów plików SVG. Biblioteka Aspose PowerPoint umożliwia konwersję plików POT na SVG i wiele innych formatów plików

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować POT na SVG przy użyciu Aspose.Slides dla Node.js za pośrednictwem interfejsu API .NET" intro="Aby przekonwertować POT na SVG przy użyciu Aspose.Slides dla Node.js poprzez .NET, musisz zaimportować pakiet do swojego pliku JavaScript i utworzyć instancję klasy Prezentacja. Klasa Prezentacja reprezentuje dokument programu PowerPoint i udostępnia metody uzyskiwania dostępu do jego elementów oraz manipulowania nimi." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj [**Aspose.Slides dla Node.js przez .NET**](https://products.aspose.com/slides/pl/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do swojego projektu Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otwórz pliki źródłowe POT w Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz wynik jako plik SVG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konwertuj POT na inne obsługiwane formaty" subTitle="Możesz także przekonwertować POT i zapisać w innych formatach plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-pptx/" name="POT TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-ppt/" name="POT TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-pdf/" name="POT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-html/" name="POT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-png/" name="POT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-bmp/" name="POT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-jpg/" name="POT TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-fodp/" name="POT TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-gif/" name="POT TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-odp/" name="POT TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-otp/" name="POT TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-potm/" name="POT TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-potx/" name="POT TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-pps/" name="POT TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-ppsm/" name="POT TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-ppsx/" name="POT TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-pptm/" name="POT TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-net/conversion/pot-to-tiff/" name="POT TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
