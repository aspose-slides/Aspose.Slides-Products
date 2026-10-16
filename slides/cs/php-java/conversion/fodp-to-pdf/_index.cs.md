---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte FODP do PDF v PHP
weight: 70
url: /cs/php-java/conversion/fodp-to-pdf/ 
keywords: "Convert, PowerPoint, FODP, PDF, Presentation, PHP"
description: Ukázkový kód pro konverzi PHP z FODP do PDF. Použijte PowerPoint PHP API pro dávkový převod souborů FODP na soubory PDF.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte FODP do PDF v PHP" h2="Výkonná PowerPoint PHP knihovna pro převod FODP do PDF"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte FODP do PDF v PHP" %}}

Potřebujete převést soubory FODP do PDF programově? Pomocí [*Aspose.Slides pro PHP přes Java*](https://products.aspose.com/slides/cs/php-java/) může každý vývojář převést FODP do formátu PDF pomocí několika řádků kódu PHP .

Aspose.Slides pro PHP jako moderní API pro zpracování prezentací rychle vytváří PDF z FODP. Otestujte kvalitu převodu FODP na PDF přímo ve svém [prohlížeči](https://products.aspose.app/slides/conversion). Knihovna Aspose PowerPoint PPTX vám umožňuje převádět soubory FODP do mnoha oblíbených formátů.

Knihovnu můžete nainstalovat z [Composer](https://packagist.org/packages/aspose/slides) pomocí následujícího příkazu:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konzole/terminál" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Uložit FODP jako PDF v PHP" %}}

Použijte bezplatnou aplikaci a podívejte se na ukázku procesu převodu FODP do PDF.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tento ukázkový kód ukazuje konverzi PHP z FODP do PDF" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.fodp");
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak převést FODP do PDF v PHP" intro="Toto jsou kroky k převodu souboru FODP na PDF pomocí PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor FODP s instancí třídy Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte metodu `save`, přičemž jako parametry zadejte cestu k výstupnímu souboru a SaveFormat.PDF{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Soubor FODP bude uložen do zadané cesty{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Požadavky na systém" intro="Před spuštěním ukázkového zdrojového kódu konverze PHP se ujistěte, že máte následující předpoklady." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte PHP 7, přidejte cestu k PHP do systémové proměnné `PATH` a nastavte `allow_url_include` na `On` v souboru `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte JRE 8. Nastavte proměnnou prostředí `JAVA_HOME` jako cestu k nainstalovanému umístění JRE.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte Apache Tomcat 8.0 (viz [více](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert FODP to PDF"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované konverze" subTitle="Můžete také převést FODP do mnoha dalších formátů souborů. Další podporované konverze naleznete níže" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-bmp/" name="FODP TO BMP" description="Bitmapový obrázek" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-gif/" name="FODP TO GIF" description="Grafický výměnný formát" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-html/" name="FODP TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-jpg/" name="FODP TO JPG" description="Obrázek JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-odp/" name="FODP TO ODP" description="Formát prezentace OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-otp/" name="FODP TO OTP" description="Standardní formát OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-png/" name="FODP TO PNG" description="Přenosná síťová grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-pot/" name="FODP TO POT" description="Soubory šablon Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-potm/" name="FODP TO POTM" description="Soubor šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-potx/" name="FODP TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-pps/" name="FODP TO PPS" description="Prezentace PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Prezentace s podporou maker" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="Prezentace PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Soubor prezentace s podporou maker" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Formát otevřené prezentace XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-svg/" name="FODP TO SVG" description="Škálovatelná vektorová grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-swf/" name="FODP TO SWF" description="Formát SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Formát tagovaného obrázku" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/fodp-to-xps/" name="FODP TO XPS" description="Specifikace papíru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
