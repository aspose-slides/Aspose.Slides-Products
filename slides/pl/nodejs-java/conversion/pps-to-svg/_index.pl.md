---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj PPS na SVG w Node.js
url: /pl/nodejs-java/conversion/pps-to-svg/
keywords: PPS na SVG, Konwertuj PPS na SVG, API Node.js, Biblioteka Node.js, PPS, SVG
description: Konwertuj PPS na SVG w Node.js. Użyj interfejsu API biblioteki Node.js, aby przekonwertować pliki PPS na pliki SVG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj PPS na SVG w Node.js" h2="Aspose.Slides dla Node.js za pośrednictwem Java to potężna i łatwa w użyciu biblioteka, która pozwala konwertować prezentacje PowerPoint do różnych formatów w Node.js. Obsługuje wszystkie elementy i formaty prezentacji oraz zapewnia bogate API umożliwiające dostęp i modyfikację ich. Umożliwia także eksport slajdów do różnych formatów w celu dalszego przetwarzania lub udostępniania." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PPS na SVG przy użyciu Node.js" variant="code" %}}

Aby przekonwertować plik PPS na SVG, musisz utworzyć prezentację z pliku PPS i zapisać ją jako SVG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod Node.js do konwersji PPS na SVG" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.pps");
try
{
    var slide = pres.getSlides().get_Item(0);
    var svgStream = java.newInstanceSync("java.io.FileOutputStream", "image.svg");
    slide.writeAsSvg(svgStream);
    svgStream.close();
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PPS na SVG w Node.js" %}}

[**Aspose.Slides dla Node.js przez Javę**](https://products.aspose.com/slides/pl/nodejs-java/) to potężna biblioteka Node.js do tworzenia plików prezentacji i manipulowania nimi. Ponadto zapewnia elastyczne sposoby konwersji PPS na SVG. Używając **Aspose.Slides dla Node.js poprzez Javę**, każdy programista lub aplikacja może przekonwertować pliki PPS na pliki SVG za pomocą zaledwie kilku linijek kodu.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla Node.js szybko eksportuje pliki PPS do formatów plików SVG. Biblioteka Aspose PowerPoint umożliwia konwersję plików PPS na SVG i wiele innych formatów plików

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować PPS na SVG przy użyciu Aspose.Slides dla Node.js poprzez API Java" intro="Aby przekonwertować PPS na SVG przy użyciu Aspose.Slides dla Node.js za pośrednictwem Java, musisz zaimportować pakiet do pliku JavaScript i utworzyć instancję klasy Prezentacja. Klasa Prezentacja reprezentuje dokument programu PowerPoint i udostępnia metody uzyskiwania dostępu do jego elementów oraz manipulowania nimi." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj [**Aspose.Slides dla Node.js przez Javę**](https://products.aspose.com/slides/pl/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do swojego projektu Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otwórz pliki źródłowe PPS w Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz wynik jako plik SVG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konwertuj PPS na inne obsługiwane formaty" subTitle="Możesz także przekonwertować PPS i zapisać w innych formatach plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-pptx/" name="PPS TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-ppt/" name="PPS TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-pdf/" name="PPS TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-html/" name="PPS TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-png/" name="PPS TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-bmp/" name="PPS TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-jpg/" name="PPS TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-fodp/" name="PPS TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-gif/" name="PPS TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-odp/" name="PPS TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-otp/" name="PPS TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-pot/" name="PPS TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-potm/" name="PPS TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-potx/" name="PPS TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-pptm/" name="PPS TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pps-to-tiff/" name="PPS TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
