---
title: A PNG konvertálása SVG formátumra PHP-ben
url: /hu/php-java/conversion/png-to-svg/
keywords: PNG to SVG, PNG konvertálása SVG formátumba, PHP API, PHP Library, PNG, SVG
description: A PNG konvertálása SVG formátumra PHP-ben. Használja a PowerPoint PHP API-t a PNG fájlok konvertálásához SVG formátumba
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="A PNG konvertálása SVG formátumra PHP-ben" h2="Hatékony PowerPoint PHP-könyvtár, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására bármilyen szoftver, például Microsoft vagy Open Office, Adobe PDF használata nélkül." >}}

{{% blocks/products/pf/feature-page-section h2="A PNG konvertálása SVG formátumra PHP-ben" %}}

Az [**Aspose.Slides for PHP Java-n keresztül**](https://products.aspose.com/slides/hu/php-java/) egy hatékony PHP-könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a PNG SVG formátumra való konvertálására. Az **Aspose.Slides for PHP Java-n keresztül** használatával bármely fejlesztő vagy alkalmazás képes konvertálni a PNG fájlokat SVG fájlokra, mindössze néhány sor PHP kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for PHP gyorsan exportál PNG fájlokat SVG fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) PNG fájl konvertálását SVG-re és sok más fájlformátumra

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a(z) PNG fájlt SVG formátumra PHP segítségével" %}}
A PNG formátum SVG formátumra konvertálásához létre kell hoznia egy prezentációt a PNG fájlból, és el kell mentenie SVG néven.

{{% blocks/products/pf/agp/code-block title="PHP kód a(z) PNG SVG formátumba való konvertálásához" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.png';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $slide = $pres->getSlides()->get_Item($i);
        $javafos = new Java("java.io.FileOutputStream", "slide_". $i .".svg");
        $slide->writeAsSvg($javafos);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A PNG konvertálása SVG formátumba az Aspose.Slides for PHP API segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a PNG SVG formátumra konvertálásához PHP-ben." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az [**Aspose.Slides for PHP programot Java-n keresztül**](https://products.aspose.com/slides/hu/php-java/) alkalmazást.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a PHP projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nyissa meg a forrás PNG fájljait PHP-ben.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése SVG fájlként.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="A(z) PNG konvertálása más támogatott formátumokká" subTitle="A PNG formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/png-to-html/" name="PNG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}