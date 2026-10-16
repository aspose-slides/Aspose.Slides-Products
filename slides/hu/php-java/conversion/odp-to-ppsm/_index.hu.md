---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: A ODP konvertálása PPSM formátumra PHP-ben
weight: 340
url: /hu/php-java/conversion/odp-to-ppsm/ 
keywords: "Convert, PowerPoint, ODP, PPSM, Presentation, PHP"
description: Mintakód a ODP és a PPSM PHP konvertáláshoz. Használja a PowerPoint PHP API-t a ODP fájlok PPSM fájlokká történő kötegelt konvertálásához.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="A ODP konvertálása PPSM formátumra PHP-ben" h2="Hatékony PowerPoint PHP-könyvtár a ODP PPSM formátumba való konvertálásához"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A ODP konvertálása PPSM formátumra PHP-ben" %}}

Programozottan kell konvertálnia a ODP fájlokat PPSM formátumba? Az [*Aspose.Slides for PHP Java segítségével*](https://products.aspose.com/slides/hu/php-java/) használatával bármely fejlesztő néhány sor PHP kóddal konvertálhatja a ODP fájlt PPSM formátumba. .

Modern prezentációfeldolgozási API-ként az Aspose.Slides for PHP gyorsan létrehozza a PPSM fájlt a ODP formátumból. Tesztelje a ODP–PPSM konverzió minőségét közvetlenül a [böngészőjében](https://products.aspose.app/slides/conversion). Az Aspose PowerPoint PPTX könyvtár lehetővé teszi, hogy a(z) ODP fájlokat számos népszerű formátumba konvertálja.

A könyvtárat a [Composer](https://packagist.org/packages/aspose/slides) webhelyről telepítheti a következő paranccsal:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konzol/Terminál" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Mentse a ODP fájlt PPSM néven PHP-ben" %}}

Az ingyenes alkalmazás segítségével megtekintheti a ODP és a PPSM közötti konverziós folyamat bemutatóját.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ez a mintakód a ODP és a PPSM közötti PHP-konverziót mutatja" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.odp");
try
{
    $pres->save("output.ppsm", SaveFormat::Ppsm);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="A(z) ODP konvertálása PPSM formátumra PHP-ben" intro="Ezek a lépések egy ODP fájl konvertálásához PPSM formátumba PHP használatával." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a ODP fájlt a Presentation osztály egy példányával{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a "save" metódust, miközben paraméterként adja meg a kimeneti fájl elérési útját és a SaveFormat.PPSM{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}A(z) ODP fájl a megadott elérési útra kerül mentésre{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="rendszerkövetelmények" intro="A PHP konverziós mintaforráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse a PHP 7-et, adja meg a PHP elérési útját a rendszer PATH változójához, és állítsa az `allow_url_include` értéket `On-ra a `php.ini` fájlban.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse a JRE-t 8. Állítsa be a "JAVA_HOME" környezeti változót a telepített JRE hely elérési útjaként.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az Apache Tomcat 8.0-t (lásd [tovább](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert ODP to PPSM"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott konverziók" subTitle="A(z) ODP fájlt sok más fájlformátumra is konvertálhatja. Lásd alább a többi támogatott konverziót" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-bmp/" name="ODP TO BMP" description="Bittérképes kép" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-fodp/" name="ODP TO FODP" description="OpenDocument Flat XML-bemutató" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-gif/" name="ODP TO GIF" description="Grafikus csereformátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-html/" name="ODP TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-jpg/" name="ODP TO JPG" description="JPEG kép" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-otp/" name="ODP TO OTP" description="OpenDocument szabványos formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-pdf/" name="ODP TO PDF" description="Hordozható dokumentum formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-png/" name="ODP TO PNG" description="Hordozható hálózati grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-pot/" name="ODP TO POT" description="Microsoft PowerPoint sablonfájlok" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-potm/" name="ODP TO POTM" description="Microsoft PowerPoint sablonfájl" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-potx/" name="ODP TO POTX" description="Microsoft PowerPoint sablon bemutató" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-pps/" name="ODP TO PPS" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-svg/" name="ODP TO SVG" description="Méretezhető vektorgrafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-swf/" name="ODP TO SWF" description="SWF formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Címkézett képformátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/odp-to-xps/" name="ODP TO XPS" description="XML papírspecifikációk" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
