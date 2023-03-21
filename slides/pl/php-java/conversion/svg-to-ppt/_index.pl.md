---
title: Konwertuj SVG na PPT w PHP
url: /pl/php-java/conversion/svg-to-ppt/
keywords: SVG do PPT, Konwersja SVG do PPT, API PHP, Biblioteka PHP, SVG, PPT
description: Konwertuj SVG na PPT w PHP. Użyj PowerPoint PHP API do konwersji plików SVG na PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konwertuj SVG na PPT w PHP" h2="Potężna biblioteka PowerPoint PHP, która pomaga w tworzeniu aplikacji z możliwością tworzenia, łączenia, sprawdzania lub konwertowania plików prezentacji Microsoft PowerPoint i OpenOffice bez użycia oprogramowania takiego jak Microsoft lub Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj SVG na PPT w PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/pl/php-java/) to potężna biblioteka PHP do tworzenia i manipulowania plikami prezentacji. Ponadto zapewnia elastyczne sposoby konwersji SVG na PPT. Korzystając z **Aspose.Slides for PHP via Java**, każdy programista lub aplikacja może konwertować pliki SVG na PPT za pomocą zaledwie kilku wierszy kodu PHP.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla PHP szybko eksportuje pliki SVG do formatów plików PPT. Biblioteka Aspose PowerPoint umożliwia konwersję SVG do PPT i wielu innych formatów plików

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj SVG na PPT za pomocą PHP" %}}
Aby przekonwertować SVG na PPT, musisz utworzyć Prezentację z pliku SVG i zapisać ją jako PPT.

{{% blocks/products/pf/agp/code-block title="Kod PHP do konwersji SVG na PPT" offSpacer="true" %}}

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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak przekonwertować SVG na PPT przy użyciu Aspose.Slides dla PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby przekonwertować SVG na PPT w PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj [**Aspose.Slides dla PHP przez Javę**](https://products.aspose.com/slides/pl/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj odniesienie do biblioteki (zaimportuj bibliotekę) do swojego projektu PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otwórz źródłowe pliki SVG w PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik jako plik PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Darmowy konwerter online" sectionDescription="[Jak przekonwertować PPT na HTML w Pythonie](https://products.aspose.com/slides/pl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Konwertuj SVG na inne obsługiwane formaty" subTitle="Możesz także przekonwertować SVG i zapisać do innych formatów plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/svg-to-pptx/" name="SVG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}