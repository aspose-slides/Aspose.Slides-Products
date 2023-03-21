---
title: A PDF konvertálása PNG formátumra PHP-ben
url: /hu/php-java/conversion/pdf-to-png/
keywords: PDF to PNG, PDF konvertálása PNG formátumba, PHP API, PHP Library, PDF, PNG
description: A PDF konvertálása PNG formátumra PHP-ben. Használja a PowerPoint PHP API-t a PDF fájlok konvertálásához PNG formátumba
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="A PDF konvertálása PNG formátumra PHP-ben" h2="Hatékony PowerPoint PHP-könyvtár, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására bármilyen szoftver, például Microsoft vagy Open Office, Adobe PDF használata nélkül." >}}

{{% blocks/products/pf/feature-page-section h2="A PDF konvertálása PNG formátumra PHP-ben" %}}

Az [**Aspose.Slides for PHP Java-n keresztül**](https://products.aspose.com/slides/hu/php-java/) egy hatékony PHP-könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a PDF PNG formátumra való konvertálására. Az **Aspose.Slides for PHP Java-n keresztül** használatával bármely fejlesztő vagy alkalmazás képes konvertálni a PDF fájlokat PNG fájlokra, mindössze néhány sor PHP kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for PHP gyorsan exportál PDF fájlokat PNG fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) PDF fájl konvertálását PNG-re és sok más fájlformátumra

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a(z) PDF fájlt PNG formátumra PHP segítségével" %}}
A PDF formátum PNG formátumra konvertálásához létre kell hoznia egy prezentációt a PDF fájlból, és el kell mentenie PNG néven.

{{% blocks/products/pf/agp/code-block title="PHP kód a(z) PDF PNG formátumba való konvertálásához" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");
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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A PDF konvertálása PNG formátumba az Aspose.Slides for PHP API segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a PDF PNG formátumra konvertálásához PHP-ben." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az [**Aspose.Slides for PHP programot Java-n keresztül**](https://products.aspose.com/slides/hu/php-java/) alkalmazást.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a PHP projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nyissa meg a forrás PDF fájljait PHP-ben.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PNG fájlként.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ingyenes online konverter" sectionDescription="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="A(z) PDF konvertálása más támogatott formátumokká" subTitle="A PDF formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pdf-to-xml/" name="PDF TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}