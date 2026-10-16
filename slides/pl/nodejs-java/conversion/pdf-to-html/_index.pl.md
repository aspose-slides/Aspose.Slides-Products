---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj PDF na HTML w Node.js
url: /pl/nodejs-java/conversion/pdf-to-html/
keywords: PDF na HTML, Konwertuj PDF na HTML, API Node.js, Biblioteka Node.js, PDF, HTML
description: Konwertuj PDF na HTML w Node.js. Użyj interfejsu API biblioteki Node.js, aby przekonwertować pliki PDF na pliki HTML
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj PDF na HTML w Node.js" h2="Aspose.Slides dla Node.js za pośrednictwem Java to potężna i łatwa w użyciu biblioteka, która pozwala konwertować prezentacje PowerPoint do różnych formatów w Node.js. Obsługuje wszystkie elementy i formaty prezentacji oraz zapewnia bogate API umożliwiające dostęp i modyfikację ich. Umożliwia także eksport slajdów do różnych formatów w celu dalszego przetwarzania lub udostępniania." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PDF na HTML przy użyciu Node.js" variant="code" %}}

Aby przekonwertować plik PDF na HTML, musisz utworzyć prezentację z pliku PDF i zapisać ją jako HTML.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod Node.js do konwersji PDF na HTML" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation();
try
{
    pres.getSlides().removeAt(0);
    pres.getSlides().addFromPdf("welcome-to-powerpoint.pdf");

    pres.save("output.html", aspose.slides.SaveFormat.Html5);
}
finally
{
    if (pres != null) pres.dispose();
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PDF na HTML w Node.js" %}}

[**Aspose.Slides dla Node.js przez Javę**](https://products.aspose.com/slides/pl/nodejs-java/) to potężna biblioteka Node.js do tworzenia plików prezentacji i manipulowania nimi. Ponadto zapewnia elastyczne sposoby konwersji PDF na HTML. Używając **Aspose.Slides dla Node.js poprzez Javę**, każdy programista lub aplikacja może przekonwertować pliki PDF na pliki HTML za pomocą zaledwie kilku linijek kodu.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla Node.js szybko eksportuje pliki PDF do formatów plików HTML. Biblioteka Aspose PowerPoint umożliwia konwersję plików PDF na HTML i wiele innych formatów plików

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować PDF na HTML przy użyciu Aspose.Slides dla Node.js poprzez API Java" intro="Aby przekonwertować PDF na HTML przy użyciu Aspose.Slides dla Node.js za pośrednictwem Java, musisz zaimportować pakiet do pliku JavaScript i utworzyć instancję klasy Prezentacja. Klasa Prezentacja reprezentuje dokument programu PowerPoint i udostępnia metody uzyskiwania dostępu do jego elementów oraz manipulowania nimi." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj [**Aspose.Slides dla Node.js przez Javę**](https://products.aspose.com/slides/pl/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do swojego projektu Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otwórz pliki źródłowe PDF w Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz wynik jako plik HTML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konwertuj PDF na inne obsługiwane formaty" subTitle="Możesz także przekonwertować PDF i zapisać w innych formatach plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
