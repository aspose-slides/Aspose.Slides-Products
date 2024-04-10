---
title: Konwertuj PPSM na BMP w JavaScript
url: /pl/nodejs-net/conversion/ppsm-to-bmp/
keywords: PPSM na BMP, Konwertuj PPSM na BMP, API Node.js, Biblioteka JavaScript, PPSM, BMP
description: Konwertuj PPSM na BMP w JavaScript. Użyj API biblioteki Node.js, aby przekonwertować pliki PPSM na BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konwertuj PPSM na BMP w JavaScript" h2="Aspose.Slides dla Node.js za pośrednictwem .NET to potężna i łatwa w obsłudze biblioteka, która umożliwia konwersję prezentacji PowerPoint do różnych formatów w JavaScript. Obsługuje wszystkie elementy i formaty prezentacji oraz zapewnia bogate API umożliwiające dostęp i modyfikację ich. Umożliwia także eksport slajdów do różnych formatów w celu dalszego przetwarzania lub udostępniania." >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj PPSM na BMP w Node.js" %}}

[**Aspose.Slides dla Node.js przez .NET**](https://products.aspose.com/slides/pl/nodejs-net/) to potężna biblioteka Node.js do tworzenia plików prezentacji i manipulowania nimi. Ponadto zapewnia elastyczne sposoby konwersji PPSM na BMP. Używając **Aspose.Slides dla Node.js za pośrednictwem .NET**, każdy programista lub aplikacja może przekonwertować pliki PPSM na pliki BMP za pomocą zaledwie kilku linijek kodu.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla Node.js za pośrednictwem .NET szybko eksportuje pliki PPSM do formatów plików BMP. Biblioteka Aspose PowerPoint umożliwia konwersję plików PPSM na BMP i wiele innych formatów plików

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj PPSM na BMP za pomocą JavaScript" %}}
Aby przekonwertować plik PPSM na BMP, musisz utworzyć prezentację z pliku PPSM i zapisać ją jako BMP.

{{% blocks/products/pf/agp/code-block title="Kod JavaScript do konwersji PPSM na BMP" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.ppsm");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".bmp", ImageFormat.Bmp); 
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak przekonwertować PPSM na BMP przy użyciu Aspose.Slides dla Node.js za pośrednictwem interfejsu API .NET" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Aby przekonwertować PPSM na BMP przy użyciu Aspose.Slides dla Node.js poprzez .NET, musisz zaimportować pakiet do swojego pliku JavaScript i utworzyć instancję klasy Prezentacja. Klasa Prezentacja reprezentuje dokument programu PowerPoint i udostępnia metody uzyskiwania dostępu do jego elementów oraz manipulowania nimi." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj [**Aspose.Slides dla Node.js przez .NET**](https://products.aspose.com/slides/pl/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do swojego projektu Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otwórz pliki źródłowe PPSM w Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik jako plik BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konwertuj PPSM na inne obsługiwane formaty" subTitle="Możesz także przekonwertować PPSM i zapisać w innych formatach plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-html/" name="PPSM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-png/" name="PPSM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-jpg/" name="PPSM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-fodp/" name="PPSM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-gif/" name="PPSM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-odp/" name="PPSM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-otp/" name="PPSM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-pot/" name="PPSM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-potm/" name="PPSM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-potx/" name="PPSM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-pps/" name="PPSM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-svg/" name="PPSM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/nodejs-net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}