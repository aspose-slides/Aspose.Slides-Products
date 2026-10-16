---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: A FODP konvertálása ODP formátumra PHP-ben
weight: 50
url: /hu/php-java/conversion/fodp-to-odp/ 
keywords: "Convert, PowerPoint, FODP, ODP, Presentation, PHP"
description: Mintakód a FODP és a ODP PHP konvertáláshoz. Használja a PowerPoint PHP API-t a FODP fájlok ODP fájlokká történő kötegelt konvertálásához.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="A FODP konvertálása ODP formátumra PHP-ben" h2="Hatékony PowerPoint PHP-könyvtár a FODP ODP formátumba való konvertálásához"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A FODP konvertálása ODP formátumra PHP-ben" %}}

Programozottan kell konvertálnia a FODP fájlokat ODP formátumba? Az [*Aspose.Slides for PHP Java segítségével*](https://products.aspose.com/slides/hu/php-java/) használatával bármely fejlesztő néhány sor PHP kóddal konvertálhatja a FODP fájlt ODP formátumba. .

Modern prezentációfeldolgozási API-ként az Aspose.Slides for PHP gyorsan létrehozza a ODP fájlt a FODP formátumból. Tesztelje a FODP–ODP konverzió minőségét közvetlenül a [böngészőjében](https://products.aspose.app/slides/conversion). Az Aspose PowerPoint PPTX könyvtár lehetővé teszi, hogy a(z) FODP fájlokat számos népszerű formátumba konvertálja.

A könyvtárat a [Composer](https://packagist.org/packages/aspose/slides) webhelyről telepítheti a következő paranccsal:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konzol/Terminál" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Mentse a FODP fájlt ODP néven PHP-ben" %}}

Az ingyenes alkalmazás segítségével megtekintheti a FODP és a ODP közötti konverziós folyamat bemutatóját.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ez a mintakód a FODP és a ODP közötti PHP-konverziót mutatja" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.fodp");
try
{
    $pres->save("output.odp", SaveFormat::Odp);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="A(z) FODP konvertálása ODP formátumra PHP-ben" intro="Ezek a lépések egy FODP fájl konvertálásához ODP formátumba PHP használatával." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a FODP fájlt a Presentation osztály egy példányával{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a "save" metódust, miközben paraméterként adja meg a kimeneti fájl elérési útját és a SaveFormat.ODP{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}A(z) FODP fájl a megadott elérési útra kerül mentésre{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="rendszerkövetelmények" intro="A PHP konverziós mintaforráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse a PHP 7-et, adja meg a PHP elérési útját a rendszer PATH változójához, és állítsa az `allow_url_include` értéket `On-ra a `php.ini` fájlban.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse a JRE-t 8. Állítsa be a "JAVA_HOME" környezeti változót a telepített JRE hely elérési útjaként.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az Apache Tomcat 8.0-t (lásd [tovább](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert FODP to ODP"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott konverziók" subTitle="A(z) FODP fájlt sok más fájlformátumra is konvertálhatja. Lásd alább a többi támogatott konverziót" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-bmp/" name="FODP TO BMP" description="Bittérképes kép" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-gif/" name="FODP TO GIF" description="Grafikus csereformátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-html/" name="FODP TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-jpg/" name="FODP TO JPG" description="JPEG kép" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-otp/" name="FODP TO OTP" description="OpenDocument szabványos formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-pdf/" name="FODP TO PDF" description="Hordozható dokumentum formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-png/" name="FODP TO PNG" description="Hordozható hálózati grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-pot/" name="FODP TO POT" description="Microsoft PowerPoint sablonfájlok" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-potm/" name="FODP TO POTM" description="Microsoft PowerPoint sablonfájl" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-potx/" name="FODP TO POTX" description="Microsoft PowerPoint sablon bemutató" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-pps/" name="FODP TO PPS" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Makró-képes diavetítés" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-svg/" name="FODP TO SVG" description="Méretezhető vektorgrafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-swf/" name="FODP TO SWF" description="SWF formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Címkézett képformátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/fodp-to-xps/" name="FODP TO XPS" description="XML papírspecifikációk" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
