---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte PPTM do POTM v PHP
weight: 2420
url: /cs/php-java/conversion/pptm-to-potm/ 
keywords: "Convert, PowerPoint, PPTM, POTM, Presentation, PHP"
description: Ukázkový kód pro konverzi PHP z PPTM do POTM. Použijte PowerPoint PHP API pro dávkový převod souborů PPTM na soubory POTM.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte PPTM do POTM v PHP" h2="Výkonná PowerPoint PHP knihovna pro převod PPTM do POTM"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte PPTM do POTM v PHP" %}}

Potřebujete převést soubory PPTM do POTM programově? Pomocí [*Aspose.Slides pro PHP přes Java*](https://products.aspose.com/slides/cs/php-java/) může každý vývojář převést PPTM do formátu POTM pomocí několika řádků kódu PHP .

Aspose.Slides pro PHP jako moderní API pro zpracování prezentací rychle vytváří POTM z PPTM. Otestujte kvalitu převodu PPTM na POTM přímo ve svém [prohlížeči](https://products.aspose.app/slides/conversion). Knihovna Aspose PowerPoint PPTX vám umožňuje převádět soubory PPTM do mnoha oblíbených formátů.

Knihovnu můžete nainstalovat z [Composer](https://packagist.org/packages/aspose/slides) pomocí následujícího příkazu:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konzole/terminál" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Uložit PPTM jako POTM v PHP" %}}

Použijte bezplatnou aplikaci a podívejte se na ukázku procesu převodu PPTM do POTM.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tento ukázkový kód ukazuje konverzi PHP z PPTM do POTM" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptm");
try
{
    $pres->save("output.potm", SaveFormat::Potm);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak převést PPTM do POTM v PHP" intro="Toto jsou kroky k převodu souboru PPTM na POTM pomocí PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPTM s instancí třídy Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte metodu `save`, přičemž jako parametry zadejte cestu k výstupnímu souboru a SaveFormat.POTM{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Soubor PPTM bude uložen do zadané cesty{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Požadavky na systém" intro="Před spuštěním ukázkového zdrojového kódu konverze PHP se ujistěte, že máte následující předpoklady." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte PHP 7, přidejte cestu k PHP do systémové proměnné `PATH` a nastavte `allow_url_include` na `On` v souboru `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte JRE 8. Nastavte proměnnou prostředí `JAVA_HOME` jako cestu k nainstalovanému umístění JRE.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte Apache Tomcat 8.0 (viz [více](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPTM to POTM"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované konverze" subTitle="Můžete také převést PPTM do mnoha dalších formátů souborů. Další podporované konverze naleznete níže" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Bitmapový obrázek" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-fodp/" name="PPTM TO FODP" description="OpenDocument Flat XML prezentace" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Grafický výměnný formát" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-html/" name="PPTM TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-jpg/" name="PPTM TO JPG" description="Obrázek JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Formát prezentace OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-otp/" name="PPTM TO OTP" description="Standardní formát OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Přenosný formát dokumentu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-png/" name="PPTM TO PNG" description="Přenosná síťová grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-pot/" name="PPTM TO POT" description="Soubory šablon Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Prezentace PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Prezentace s podporou maker" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Prezentace PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Formát otevřené prezentace XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Škálovatelná vektorová grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="Formát SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Formát tagovaného obrázku" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Specifikace papíru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
