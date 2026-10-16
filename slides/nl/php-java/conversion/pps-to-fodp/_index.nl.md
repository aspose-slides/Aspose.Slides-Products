---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer PPS naar FODP in PHP
weight: 1490
url: /nl/php-java/conversion/pps-to-fodp/ 
keywords: "Convert, PowerPoint, PPS, FODP, Presentation, PHP"
description: Voorbeeldcode voor PPS naar FODP PHP-conversie. Gebruik PowerPoint PHP API voor batchconversie van PPS-bestanden naar FODP-bestanden.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer PPS naar FODP in PHP" h2="Krachtige PowerPoint PHP-bibliotheek voor het converteren van PPS naar FODP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer PPS naar FODP in PHP" %}}

Wilt u PPS-bestanden programmatisch naar FODP converteren? Met behulp van [*Aspose.Slides voor PHP via Java*](https://products.aspose.com/slides/nl/php-java/) kan elke ontwikkelaar PPS naar FODP-indeling converteren met slechts een paar regels PHP-code .

Als een moderne API voor het verwerken van presentaties, maakt Aspose.Slides voor PHP snel FODP van PPS. Test de kwaliteit van de conversie van PPS naar FODP rechtstreeks in uw [browser](https://products.aspose.app/slides/conversion). Met de Aspose PowerPoint PPTX-bibliotheek kunt u PPS-bestanden converteren naar veel populaire formaten.

U kunt de bibliotheek installeren vanaf [Composer](https://packagist.org/packages/aspose/slides) met behulp van de volgende opdracht:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sla PPS op als FODP in PHP" %}}

Gebruik de gratis app om een ​​demonstratie te zien van het conversieproces van PPS naar FODP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Deze voorbeeldcode toont PPS naar FODP PHP-conversie" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pps");
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe PPS naar FODP te converteren in PHP" intro="Dit zijn de stappen om een ​​PPS bestand naar FODP te converteren met behulp van PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad PPS bestand met een instantie van de klasse Presentatie{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de `save`-methode aan terwijl u het pad van het uitvoerbestand & SaveFormat.FODP specificeert als parameters{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPS bestand wordt opgeslagen op het opgegeven pad{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="systeem vereisten" intro="Voordat u de broncode van het PHP-conversievoorbeeld uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer PHP 7, voeg pad naar PHP toe aan systeemvariabele `PATH` en zet `allow_url_include` op `On` in `php.ini`-bestand.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer JRE 8. Stel de `JAVA_HOME` omgevingsvariabele in als een pad naar de geïnstalleerde JRE-locatie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer Apache Tomcat 8.0 (zie [meer](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPS to FODP"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde conversies" subTitle="U kunt PPS ook naar vele andere bestandsindelingen converteren. Bekijk hieronder andere ondersteunde conversies" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-bmp/" name="PPS TO BMP" description="Bitmap afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-gif/" name="PPS TO GIF" description="Grafisch uitwisselingsformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-html/" name="PPS TO HTML" description="Hypertekst-opmaaktaal" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-jpg/" name="PPS TO JPG" description="JPEG-afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-odp/" name="PPS TO ODP" description="Presentatie-indeling OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-otp/" name="PPS TO OTP" description="Standaardformaat OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-pdf/" name="PPS TO PDF" description="Draagbaar documentformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-png/" name="PPS TO PNG" description="Draagbare netwerkgrafieken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-pot/" name="PPS TO POT" description="Microsoft PowerPoint-sjabloonbestanden" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-potm/" name="PPS TO POTM" description="Microsoft PowerPoint-sjabloonbestand" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-potx/" name="PPS TO POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Diavoorstelling met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-pptm/" name="PPS TO PPTM" description="Presentatiebestand met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Open XML-presentatie-indeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-svg/" name="PPS TO SVG" description="Schaalbare vectorafbeeldingen" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-swf/" name="PPS TO SWF" description="SWF-formaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Gelabelde afbeeldingsindeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-xps/" name="PPS TO XPS" description="XML-papierspecificaties" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
