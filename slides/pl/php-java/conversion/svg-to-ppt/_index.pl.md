---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj SVG na PPT w PHP
url: /pl/php-java/conversion/svg-to-ppt/
keywords: SVG do PPT, Konwersja SVG do PPT, API PHP, Biblioteka PHP, SVG, PPT
description: Konwertuj SVG na PPT w PHP. Użyj PowerPoint PHP API do konwersji plików SVG na PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj SVG na PPT w PHP" h2="Potężna biblioteka PowerPoint PHP, która pomaga w tworzeniu aplikacji z możliwością tworzenia, łączenia, sprawdzania lub konwertowania plików prezentacji Microsoft PowerPoint i OpenOffice bez użycia oprogramowania takiego jak Microsoft lub Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj SVG na PPT za pomocą PHP" variant="code" %}}

Aby przekonwertować SVG na PPT, musisz utworzyć Prezentację z pliku SVG i zapisać ją jako PPT.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod PHP do konwersji SVG na PPT" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.svg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $svgImage = new SvgImage($contents);
    $image = $pres->getImages()->addImage($svgImage);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.ppt", SaveFormat::Ppt);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj SVG na PPT w PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/pl/php-java/) to potężna biblioteka PHP do tworzenia i manipulowania plikami prezentacji. Ponadto zapewnia elastyczne sposoby konwersji SVG na PPT. Korzystając z **Aspose.Slides for PHP via Java**, każdy programista lub aplikacja może konwertować pliki SVG na PPT za pomocą zaledwie kilku wierszy kodu PHP.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla PHP szybko eksportuje pliki SVG do formatów plików PPT. Biblioteka Aspose PowerPoint umożliwia konwersję SVG do PPT i wielu innych formatów plików

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować SVG na PPT przy użyciu Aspose.Slides dla PHP API" intro="Oto kroki, aby przekonwertować SVG na PPT w PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj [**Aspose.Slides dla PHP przez Javę**](https://products.aspose.com/slides/pl/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj odniesienie do biblioteki (zaimportuj bibliotekę) do swojego projektu PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otwórz źródłowe pliki SVG w PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz wynik jako plik PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Darmowy konwerter online"
  description="[Jak przekonwertować PPT na HTML w Pythonie](https://products.aspose.com/slides/pl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konwertuj SVG na inne obsługiwane formaty" subTitle="Możesz także przekonwertować SVG i zapisać do innych formatów plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/svg-to-pptx/" name="SVG TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
