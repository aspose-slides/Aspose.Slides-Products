---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: A PPTM konvertálása PPS formátumra PHP-ben
weight: 2440
url: /hu/php-java/conversion/pptm-to-pps/ 
keywords: "Convert, PowerPoint, PPTM, PPS, Presentation, PHP"
description: Mintakód a PPTM és a PPS PHP konvertáláshoz. Használja a PowerPoint PHP API-t a PPTM fájlok PPS fájlokká történő kötegelt konvertálásához.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="A PPTM konvertálása PPS formátumra PHP-ben" h2="Hatékony PowerPoint PHP-könyvtár a PPTM PPS formátumba való konvertálásához"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A PPTM konvertálása PPS formátumra PHP-ben" %}}

Programozottan kell konvertálnia a PPTM fájlokat PPS formátumba? Az [*Aspose.Slides for PHP Java segítségével*](https://products.aspose.com/slides/hu/php-java/) használatával bármely fejlesztő néhány sor PHP kóddal konvertálhatja a PPTM fájlt PPS formátumba. .

Modern prezentációfeldolgozási API-ként az Aspose.Slides for PHP gyorsan létrehozza a PPS fájlt a PPTM formátumból. Tesztelje a PPTM–PPS konverzió minőségét közvetlenül a [böngészőjében](https://products.aspose.app/slides/conversion). Az Aspose PowerPoint PPTX könyvtár lehetővé teszi, hogy a(z) PPTM fájlokat számos népszerű formátumba konvertálja.

A könyvtárat a [Composer](https://packagist.org/packages/aspose/slides) webhelyről telepítheti a következő paranccsal:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konzol/Terminál" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Mentse a PPTM fájlt PPS néven PHP-ben" %}}

Az ingyenes alkalmazás segítségével megtekintheti a PPTM és a PPS közötti konverziós folyamat bemutatóját.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ez a mintakód a PPTM és a PPS közötti PHP-konverziót mutatja" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptm");
try
{
    $pres->save("output.pps", SaveFormat::Pps);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="A(z) PPTM konvertálása PPS formátumra PHP-ben" intro="Ezek a lépések egy PPTM fájl konvertálásához PPS formátumba PHP használatával." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPTM fájlt a Presentation osztály egy példányával{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a "save" metódust, miközben paraméterként adja meg a kimeneti fájl elérési útját és a SaveFormat.PPS{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}A(z) PPTM fájl a megadott elérési útra kerül mentésre{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="rendszerkövetelmények" intro="A PHP konverziós mintaforráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse a PHP 7-et, adja meg a PHP elérési útját a rendszer PATH változójához, és állítsa az `allow_url_include` értéket `On-ra a `php.ini` fájlban.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse a JRE-t 8. Állítsa be a "JAVA_HOME" környezeti változót a telepített JRE hely elérési útjaként.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az Apache Tomcat 8.0-t (lásd [tovább](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPTM to PPS"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott konverziók" subTitle="A(z) PPTM fájlt sok más fájlformátumra is konvertálhatja. Lásd alább a többi támogatott konverziót" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Bittérképes kép" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-fodp/" name="PPTM TO FODP" description="OpenDocument Flat XML-bemutató" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Grafikus csereformátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-html/" name="PPTM TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-jpg/" name="PPTM TO JPG" description="JPEG kép" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-odp/" name="PPTM TO ODP" description="OpenDocument prezentációs formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-otp/" name="PPTM TO OTP" description="OpenDocument szabványos formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Hordozható dokumentum formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-png/" name="PPTM TO PNG" description="Hordozható hálózati grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-pot/" name="PPTM TO POT" description="Microsoft PowerPoint sablonfájlok" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Microsoft PowerPoint sablonfájl" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Microsoft PowerPoint sablon bemutató" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Makró-képes diavetítés" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Méretezhető vektorgrafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="SWF formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Címkézett képformátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="XML papírspecifikációk" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
