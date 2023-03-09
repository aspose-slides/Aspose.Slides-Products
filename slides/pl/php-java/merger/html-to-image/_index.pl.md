---
title: Połącz HTML z obrazem w PHP
url: /pl/php-java/merger/html-to-image/
keywords: Połącz HTML z obrazem, HTML z obrazem, dołącz do HTML, połącz HTML, obraz, PHP API, bibliotekę PHP
description: Połącz HTML z obrazem w PHP. Użyj API biblioteki PHP, aby połączyć HTML z obrazem
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Scal obraz w PHP" h2="Szybka i wieloplatformowa biblioteka PHP do łączenia HTML z obrazami za pomocą kodu PHP" >}}

{{% blocks/products/pf/feature-page-section h2="Połącz HTML z obrazem za pomocą Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/pl/php-java/) to potężna biblioteka PHP używana do łączenia i manipulowania prezentacjami, dokumentami HTML i innymi plikami. Łącząc HTML z obrazem, skutecznie łączysz zawartość dokumentów HTML w celu uzyskania pojedynczego obrazu. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Połącz HTML z obrazem w PHP" %}}
Używając [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/pl/php-java/), możesz szybko łączyć pliki obrazów za pomocą zaledwie kilku linijek kodu

{{% blocks/products/pf/agp/code-block title="Kod PHP do łączenia HTML z obrazem" offSpacer="true" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $filename1 = 'file1.html';
    $f1 = fopen($filename1, 'r');
    if ($f1) {
        $contents1 = fread($f1, filesize($filename1));
        fclose($f1);
    }
    
    $pres->getSlides()->addFromHtml($contents1);
    
    $filename2 = 'file2.html';
    $f2 = fopen($filename2, 'r');
    if ($f2) {
        $contents2 = fread($f2, filesize($filename2));
        fclose($f2);
    }
    
    $pres->getSlides()->addFromHtml($contents2);

    $img = $pres->getSlides()->get_Item(0)->getThumbnail(2, 2);
    $imageio = new Java("javax.imageio.ImageIO");
    $javafile = new Java("java.io.File", "merged-image.png");
    $imageio->write($img, "PNG", $javafile);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Jak scalić HTML z obrazem w PHP" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj **Aspose.Slides dla PHP przez Javę**. Zobacz [**Instalacja**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj bibliotekę jako odniesienie w swoim projekcie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utwórz wystąpienie klasy Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj dokumenty HTML, które chcesz scalić.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz powstały obraz.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Scal inne pliki" subTitle="Możesz także łączyć pliki w innych formatach, aby uzyskać jeden plik" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
    
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}