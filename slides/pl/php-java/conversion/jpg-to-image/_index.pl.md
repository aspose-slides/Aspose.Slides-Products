---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj JPG na Image w PHP
url: /pl/php-java/conversion/jpg-to-image/
keywords: JPG do Image, Konwersja JPG do Image, API PHP, Biblioteka PHP, JPG, Image
description: Konwertuj JPG na Image w PHP. Użyj PowerPoint PHP API do konwersji plików JPG na Image
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj JPG na Image w PHP" h2="Potężna biblioteka PowerPoint PHP, która pomaga w tworzeniu aplikacji z możliwością tworzenia, łączenia, sprawdzania lub konwertowania plików prezentacji Microsoft PowerPoint i OpenOffice bez użycia oprogramowania takiego jak Microsoft lub Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj JPG na Image za pomocą PHP" variant="code" %}}

Aby przekonwertować JPG na Image, musisz utworzyć Prezentację z pliku JPG i zapisać ją jako Image.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod PHP do konwersji JPG na Image" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.jpg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".png");
        $imageio->write($bmp, "PNG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj JPG na Image w PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/pl/php-java/) to potężna biblioteka PHP do tworzenia i manipulowania plikami prezentacji. Ponadto zapewnia elastyczne sposoby konwersji JPG na Image. Korzystając z **Aspose.Slides for PHP via Java**, każdy programista lub aplikacja może konwertować pliki JPG na Image za pomocą zaledwie kilku wierszy kodu PHP.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla PHP szybko eksportuje pliki JPG do formatów plików Image. Biblioteka Aspose PowerPoint umożliwia konwersję JPG do Image i wielu innych formatów plików

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować JPG na Image przy użyciu Aspose.Slides dla PHP API" intro="Oto kroki, aby przekonwertować JPG na Image w PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj [**Aspose.Slides dla PHP przez Javę**](https://products.aspose.com/slides/pl/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj odniesienie do biblioteki (zaimportuj bibliotekę) do swojego projektu PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otwórz źródłowe pliki JPG w PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz wynik jako plik Image.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Darmowy konwerter online"
  description="[Jak przekonwertować PPT na HTML w Pythonie](https://products.aspose.com/slides/pl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konwertuj JPG na inne obsługiwane formaty" subTitle="Możesz także przekonwertować JPG i zapisać do innych formatów plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/jpg-to-html/" name="JPG TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
