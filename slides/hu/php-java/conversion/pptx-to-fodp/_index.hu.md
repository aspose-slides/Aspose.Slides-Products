---
title: A PPTX konvertálása FODP formátumra PHP-ben
weight: 2540
url: /hu/php-java/conversion/pptx-to-fodp/ 
keywords: "Convert, PowerPoint, PPTX, FODP, Presentation, PHP"
description: Mintakód a PPTX és a FODP PHP konvertáláshoz. Használja a PowerPoint PHP API-t a PPTX fájlok FODP fájlokká történő kötegelt konvertálásához.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="A PPTX konvertálása FODP formátumra PHP-ben" h2="Hatékony PowerPoint PHP-könyvtár a PPTX FODP formátumba való konvertálásához" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="A PPTX konvertálása FODP formátumra PHP-ben" %}}

Programozottan kell konvertálnia a PPTX fájlokat FODP formátumba? Az [*Aspose.Slides for PHP Java segítségével*](https://products.aspose.com/slides/hu/php-java/) használatával bármely fejlesztő néhány sor PHP kóddal konvertálhatja a PPTX fájlt FODP formátumba. .

Modern prezentációfeldolgozási API-ként az Aspose.Slides for PHP gyorsan létrehozza a FODP fájlt a PPTX formátumból. Tesztelje a PPTX–FODP konverzió minőségét közvetlenül a [böngészőjében](https://products.aspose.app/slides/conversion). Az Aspose PowerPoint PPTX könyvtár lehetővé teszi, hogy a(z) PPTX fájlokat számos népszerű formátumba konvertálja.

A könyvtárat a [Composer](https://packagist.org/packages/aspose/slides) webhelyről telepítheti a következő paranccsal:

{{% blocks/products/pf/agp/code-block title="Konzol/Terminál" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="A(z) PPTX konvertálása FODP formátumra PHP-ben" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések egy PPTX fájl konvertálásához FODP formátumba PHP használatával." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltse be a PPTX fájlt a Presentation osztály egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hívja meg a "save" metódust, miközben paraméterként adja meg a kimeneti fájl elérési útját és a SaveFormat.FODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
A(z) PPTX fájl a megadott elérési útra kerül mentésre
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A PHP konverziós mintaforráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

1. Telepítse a PHP 7-et, adja meg a PHP elérési útját a rendszer PATH változójához, és állítsa az `allow_url_include` értéket `On-ra a `php.ini` fájlban.
1. Telepítse a JRE-t 8. Állítsa be a "JAVA_HOME" környezeti változót a telepített JRE hely elérési útjaként.
1. Telepítse az Apache Tomcat 8.0-t (lásd [tovább](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ez a mintakód a PPTX és a FODP közötti PHP-konverziót mutatja" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptx");
try
{
    $pres->save("output.fodp", SaveFormat::Fodp);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Mentse a PPTX fájlt FODP néven PHP-ben" %}}
Az ingyenes alkalmazás segítségével megtekintheti a PPTX és a FODP közötti konverziós folyamat bemutatóját. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PPTX to FODP" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="A(z) PPTX fájlt sok más fájlformátumra is konvertálhatja. Lásd alább a többi támogatott konverziót" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Bittérképes kép" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Grafikus csereformátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-html/" name="PPTX TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-jpg/" name="PPTX TO JPG" description="JPEG kép" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument prezentációs formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument szabványos formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Hordozható dokumentum formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-png/" name="PPTX TO PNG" description="Hordozható hálózati grafika" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-pot/" name="PPTX TO POT" description="Microsoft PowerPoint sablonfájlok" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Microsoft PowerPoint sablonfájl" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Microsoft PowerPoint sablon bemutató" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-pps/" name="PPTX TO PPS" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Makró-képes diavetítés" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-svg/" name="PPTX TO SVG" description="Méretezhető vektorgrafika" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-swf/" name="PPTX TO SWF" description="SWF formátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Címkézett képformátum" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/php-java/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML papírspecifikációk" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}