---
title: Szerkessze a POT fájlt PHP-ben
url: /hu/php-java/editor/pot/
keywords: Szerkesztés POT, PowerPoint szerkesztése, POT, PowerPoint, PHP API, PHP Library
description: Szerkessze a POT fájlt PHP-ben. Használja a PHP könyvtár API-t a POT fájlok szerkesztéséhez
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Szerkessze a POT fájlt PHP-ben" h2="Nagy sebességű és platformok közötti PHP-könyvtár a POT szerkesztéséhez PHP-kóddal" >}}

{{% blocks/products/pf/feature-page-section h2="Szerkessze a POT fájlt az Aspose.Slides használatával" %}}

Az [**Aspose.Slides for PHP Java-n keresztül**](https://products.aspose.com/slides/hu/php-java/) egy hatékony PHP-könyvtár a prezentációk gyors és egyszerű szerkesztéséhez. A funkciók széles skáláját kínálja a felhasználóknak, amelyek segítségével pillanatok alatt professzionális megjelenésű diákat hozhatnak létre. Az Aspose segítségével a felhasználók szöveget szerkeszthetnek, képeket, animációkat és átmeneteket adhatnak prezentációjukhoz, valamint különféle formázási beállításokat alkalmazhatnak, például betűtípust és színválasztást. Ezenkívül a könyvtár támogatja a PowerPoint (PPT) fájlokat és az OpenOffice Presentation (ODP) formátumokat is, ami minden eddiginél egyszerűbbé teszi a prezentációk megosztását különböző platformokon, kompatibilitási problémák nélkül. Ha kihasználja az Aspose könyvtárának erejét a következő prezentáció létrehozásakor vagy szerkesztésekor, biztos lehet benne, hogy diákjai minden alkalommal nagyszerűen fognak kinézni!
Szerkeszthet egy POT fájlt, ha új szövegsort ad hozzá. 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Szerkessze a POT fájlt PHP-ben" %}}
Az [**Aspose.Slides for PHP Java-n keresztül**](https://products.aspose.com/slides/hu/php-java/) használatával új szövegsort adhat a POT dokumentumhoz, mindössze egy néhány sor kódot.

{{% blocks/products/pf/agp/code-block title="PHP kód a POT szerkesztéséhez" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pot");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.pot", SaveFormat::Pot);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A POT szerkesztése PHP-ben" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az **Aspose.Slides for PHP-t Java-n keresztül**. Lásd: [**Telepítés**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adja hozzá a könyvtárat referenciaként a projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hozzon létre egy példányt a Prezentáció osztályból.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltse be a szerkeszteni kívánt POT prezentációt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy új szövegsort.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse el a módosított fájlt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Más fájlok szerkesztése" subTitle="Más formátumú fájlokat is szerkeszthet" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}