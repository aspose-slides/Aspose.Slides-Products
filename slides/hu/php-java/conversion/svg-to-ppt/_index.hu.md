---
title: A SVG konvertálása PPT formátumra PHP-ben
url: /hu/php-java/conversion/svg-to-ppt/
keywords: SVG to PPT, SVG konvertálása PPT formátumba, PHP API, PHP Library, SVG, PPT
description: A SVG konvertálása PPT formátumra PHP-ben. Használja a PowerPoint PHP API-t a SVG fájlok konvertálásához PPT formátumba
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="A SVG konvertálása PPT formátumra PHP-ben" h2="Hatékony PowerPoint PHP-könyvtár, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására bármilyen szoftver, például Microsoft vagy Open Office, Adobe PDF használata nélkül." >}}

{{% blocks/products/pf/feature-page-section h2="A SVG konvertálása PPT formátumra PHP-ben" %}}

Az [**Aspose.Slides for PHP Java-n keresztül**](https://products.aspose.com/slides/hu/php-java/) egy hatékony PHP-könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a SVG PPT formátumra való konvertálására. Az **Aspose.Slides for PHP Java-n keresztül** használatával bármely fejlesztő vagy alkalmazás képes konvertálni a SVG fájlokat PPT fájlokra, mindössze néhány sor PHP kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for PHP gyorsan exportál SVG fájlokat PPT fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) SVG fájl konvertálását PPT-re és sok más fájlformátumra

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a(z) SVG fájlt PPT formátumra PHP segítségével" %}}
A SVG formátum PPT formátumra konvertálásához létre kell hoznia egy prezentációt a SVG fájlból, és el kell mentenie PPT néven.

{{% blocks/products/pf/agp/code-block title="PHP kód a(z) SVG PPT formátumba való konvertálásához" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="A SVG konvertálása PPT formátumba az Aspose.Slides for PHP API segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a SVG PPT formátumra konvertálásához PHP-ben." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az [**Aspose.Slides for PHP programot Java-n keresztül**](https://products.aspose.com/slides/hu/php-java/) alkalmazást.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a PHP projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nyissa meg a forrás SVG fájljait PHP-ben.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PPT fájlként.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ingyenes online konverter" sectionDescription="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="A(z) SVG konvertálása más támogatott formátumokká" subTitle="A SVG formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/svg-to-pptx/" name="SVG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}