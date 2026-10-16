---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte PPSX do PNG v PHP
weight: 1980
url: /cs/php-java/conversion/ppsx-to-png/ 
keywords: "Convert, PowerPoint, PPSX, PNG, Presentation, PHP"
description: Ukázkový kód pro konverzi PHP z PPSX do PNG. Použijte PowerPoint PHP API pro dávkový převod souborů PPSX na soubory PNG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte PPSX do PNG v PHP" h2="Výkonná PowerPoint PHP knihovna pro převod PPSX do PNG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte PPSX do PNG v PHP" %}}

Potřebujete převést soubory PPSX do PNG programově? Pomocí [*Aspose.Slides pro PHP přes Java*](https://products.aspose.com/slides/cs/php-java/) může každý vývojář převést PPSX do formátu PNG pomocí několika řádků kódu PHP .

Aspose.Slides pro PHP jako moderní API pro zpracování prezentací rychle vytváří PNG z PPSX. Otestujte kvalitu převodu PPSX na PNG přímo ve svém [prohlížeči](https://products.aspose.app/slides/conversion/ppt-to-png). Knihovna Aspose PowerPoint PPTX vám umožňuje převádět soubory PPSX do mnoha oblíbených formátů.

Knihovnu můžete nainstalovat z [Composer](https://packagist.org/packages/aspose/slides) pomocí následujícího příkazu:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konzole/terminál" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Uložit PPSX jako PNG v PHP" %}}

Použijte bezplatnou aplikaci a podívejte se na ukázku procesu převodu PPSX do PNG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tento ukázkový kód ukazuje konverzi PHP z PPSX do PNG" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsx");
try
{
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak převést PPSX do PNG v PHP" intro="Toto jsou kroky k převodu souboru PPSX na PNG pomocí PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPSX s instancí třídy Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte metodu `save`, přičemž jako parametry zadejte cestu k výstupnímu souboru a SaveFormat.PNG{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Soubor PPSX bude uložen do zadané cesty{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Požadavky na systém" intro="Před spuštěním ukázkového zdrojového kódu konverze PHP se ujistěte, že máte následující předpoklady." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte PHP 7, přidejte cestu k PHP do systémové proměnné `PATH` a nastavte `allow_url_include` na `On` v souboru `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte JRE 8. Nastavte proměnnou prostředí `JAVA_HOME` jako cestu k nainstalovanému umístění JRE.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte Apache Tomcat 8.0 (viz [více](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPSX to PNG"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované konverze" subTitle="Můžete také převést PPSX do mnoha dalších formátů souborů. Další podporované konverze naleznete níže" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Bitmapový obrázek" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" description="OpenDocument Flat XML prezentace" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Grafický výměnný formát" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-jpg/" name="PPSX TO JPG" description="Obrázek JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="Formát prezentace OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Standardní formát OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Přenosný formát dokumentu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Soubory šablon Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Soubor šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="Prezentace PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Prezentace s podporou maker" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Soubor prezentace s podporou maker" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Formát otevřené prezentace XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Škálovatelná vektorová grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="Formát SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Formát tagovaného obrázku" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="Specifikace papíru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
