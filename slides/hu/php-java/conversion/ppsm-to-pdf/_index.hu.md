---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: A PPSM konvertálása PDF formátumra PHP-ben
weight: 1760
url: /hu/php-java/conversion/ppsm-to-pdf/ 
keywords: "Convert, PowerPoint, PPSM, PDF, Presentation, PHP"
description: Mintakód a PPSM és a PDF PHP konvertáláshoz. Használja a PowerPoint PHP API-t a PPSM fájlok PDF fájlokká történő kötegelt konvertálásához.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="A PPSM konvertálása PDF formátumra PHP-ben" h2="Hatékony PowerPoint PHP-könyvtár a PPSM PDF formátumba való konvertálásához"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A PPSM konvertálása PDF formátumra PHP-ben" %}}

Programozottan kell konvertálnia a PPSM fájlokat PDF formátumba? Az [*Aspose.Slides for PHP Java segítségével*](https://products.aspose.com/slides/hu/php-java/) használatával bármely fejlesztő néhány sor PHP kóddal konvertálhatja a PPSM fájlt PDF formátumba. .

Modern prezentációfeldolgozási API-ként az Aspose.Slides for PHP gyorsan létrehozza a PDF fájlt a PPSM formátumból. Tesztelje a PPSM–PDF konverzió minőségét közvetlenül a [böngészőjében](https://products.aspose.app/slides/conversion). Az Aspose PowerPoint PPTX könyvtár lehetővé teszi, hogy a(z) PPSM fájlokat számos népszerű formátumba konvertálja.

A könyvtárat a [Composer](https://packagist.org/packages/aspose/slides) webhelyről telepítheti a következő paranccsal:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konzol/Terminál" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Mentse a PPSM fájlt PDF néven PHP-ben" %}}

Az ingyenes alkalmazás segítségével megtekintheti a PPSM és a PDF közötti konverziós folyamat bemutatóját.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ez a mintakód a PPSM és a PDF közötti PHP-konverziót mutatja" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsm");
try
{
    $pres->save("output.pdf", SaveFormat::Pdf);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="A(z) PPSM konvertálása PDF formátumra PHP-ben" intro="Ezek a lépések egy PPSM fájl konvertálásához PDF formátumba PHP használatával." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPSM fájlt a Presentation osztály egy példányával{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a "save" metódust, miközben paraméterként adja meg a kimeneti fájl elérési útját és a SaveFormat.PDF{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}A(z) PPSM fájl a megadott elérési útra kerül mentésre{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="rendszerkövetelmények" intro="A PHP konverziós mintaforráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse a PHP 7-et, adja meg a PHP elérési útját a rendszer PATH változójához, és állítsa az `allow_url_include` értéket `On-ra a `php.ini` fájlban.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse a JRE-t 8. Állítsa be a "JAVA_HOME" környezeti változót a telepített JRE hely elérési útjaként.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az Apache Tomcat 8.0-t (lásd [tovább](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Az Aspose.Slides segítségével készült" title="PPSM konvertálása PDF formátumba online" description="Az ingyenes Aspose.Slides Conversion alkalmazás az [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/hu/php-java/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPSM fájljaival." button="Aspose.Slides Conversion megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" upload="Húzza ide vagy töltse fel a fájlt" saveAs="Mentés másként" convert="Konvertálás" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan konvertálja a fájlokat az Aspose.Slides, mielőtt kódot írna.
- Töltsön fel PPSM fájlokat, és mentse őket PDF formátumban.
- Töltse le az eredményt, vagy konvertáljon további fájlokat.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott konverziók" subTitle="A(z) PPSM fájlt sok más fájlformátumra is konvertálhatja. Lásd alább a többi támogatott konverziót" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Bittérképes kép" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-fodp/" name="PPSM TO FODP" description="OpenDocument Flat XML-bemutató" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Grafikus csereformátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-jpg/" name="PPSM TO JPG" description="JPEG kép" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="OpenDocument prezentációs formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="OpenDocument szabványos formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-png/" name="PPSM TO PNG" description="Hordozható hálózati grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Microsoft PowerPoint sablonfájlok" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Microsoft PowerPoint sablonfájl" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Microsoft PowerPoint sablon bemutató" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="PowerPoint diavetítés" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Méretezhető vektorgrafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="SWF formátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Címkézett képformátum" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="XML papírspecifikációk" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
