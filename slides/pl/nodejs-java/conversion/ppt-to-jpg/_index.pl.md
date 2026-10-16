---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj PPT na JPG w Node.js
url: /pl/nodejs-java/conversion/ppt-to-jpg/
keywords: PPT na JPG, Konwertuj PPT na JPG, API Node.js, Biblioteka Node.js, PPT, JPG
description: Konwertuj PPT na JPG w Node.js. Użyj interfejsu API biblioteki Node.js, aby przekonwertować pliki PPT na pliki JPG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj PPT na JPG w Node.js" h2="Aspose.Slides dla Node.js za pośrednictwem Java to potężna i łatwa w użyciu biblioteka, która pozwala konwertować prezentacje PowerPoint do różnych formatów w Node.js. Obsługuje wszystkie elementy i formaty prezentacji oraz zapewnia bogate API umożliwiające dostęp i modyfikację ich. Umożliwia także eksport slajdów do różnych formatów w celu dalszego przetwarzania lub udostępniania." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PPT na JPG przy użyciu Node.js" variant="code" %}}

Aby przekonwertować plik PPT na JPG, musisz utworzyć prezentację z pliku PPT i zapisać ją jako JPG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod Node.js do konwersji PPT na JPG" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.ppt");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".jpg");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "jpeg", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PPT na JPG w Node.js" %}}

[**Aspose.Slides dla Node.js przez Javę**](https://products.aspose.com/slides/pl/nodejs-java/) to potężna biblioteka Node.js do tworzenia plików prezentacji i manipulowania nimi. Ponadto zapewnia elastyczne sposoby konwersji PPT na JPG. Używając **Aspose.Slides dla Node.js poprzez Javę**, każdy programista lub aplikacja może przekonwertować pliki PPT na pliki JPG za pomocą zaledwie kilku linijek kodu.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla Node.js szybko eksportuje pliki PPT do formatów plików JPG. Biblioteka Aspose PowerPoint umożliwia konwersję plików PPT na JPG i wiele innych formatów plików

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować PPT na JPG przy użyciu Aspose.Slides dla Node.js poprzez API Java" intro="Aby przekonwertować PPT na JPG przy użyciu Aspose.Slides dla Node.js za pośrednictwem Java, musisz zaimportować pakiet do pliku JavaScript i utworzyć instancję klasy Prezentacja. Klasa Prezentacja reprezentuje dokument programu PowerPoint i udostępnia metody uzyskiwania dostępu do jego elementów oraz manipulowania nimi." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj [**Aspose.Slides dla Node.js przez Javę**](https://products.aspose.com/slides/pl/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do swojego projektu Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otwórz pliki źródłowe PPT w Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz wynik jako plik JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konwertuj PPT na inne obsługiwane formaty" subTitle="Możesz także przekonwertować PPT i zapisać w innych formatach plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-fodp/" name="PPT TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-odp/" name="PPT TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-otp/" name="PPT TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-pot/" name="PPT TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-potm/" name="PPT TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-potx/" name="PPT TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-pps/" name="PPT TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/nodejs-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
