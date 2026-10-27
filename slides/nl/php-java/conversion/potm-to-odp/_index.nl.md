---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer POTM naar ODP in PHP
weight: 1110
url: /nl/php-java/conversion/potm-to-odp/ 
keywords: "Convert, PowerPoint, POTM, ODP, Presentation, PHP"
description: Voorbeeldcode voor POTM naar ODP PHP-conversie. Gebruik PowerPoint PHP API voor batchconversie van POTM-bestanden naar ODP-bestanden.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer POTM naar ODP in PHP" h2="Krachtige PowerPoint PHP-bibliotheek voor het converteren van POTM naar ODP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer POTM naar ODP in PHP" %}}

Wilt u POTM-bestanden programmatisch naar ODP converteren? Met behulp van [*Aspose.Slides voor PHP via Java*](https://products.aspose.com/slides/nl/php-java/) kan elke ontwikkelaar POTM naar ODP-indeling converteren met slechts een paar regels PHP-code .

Als een moderne API voor het verwerken van presentaties, maakt Aspose.Slides voor PHP snel ODP van POTM. Test de kwaliteit van de conversie van POTM naar ODP rechtstreeks in uw [browser](https://products.aspose.app/slides/conversion). Met de Aspose PowerPoint PPTX-bibliotheek kunt u POTM-bestanden converteren naar veel populaire formaten.

U kunt de bibliotheek installeren vanaf [Composer](https://packagist.org/packages/aspose/slides) met behulp van de volgende opdracht:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sla POTM op als ODP in PHP" %}}

Gebruik de gratis app om een ​​demonstratie te zien van het conversieproces van POTM naar ODP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Deze voorbeeldcode toont POTM naar ODP PHP-conversie" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potm");
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe POTM naar ODP te converteren in PHP" intro="Dit zijn de stappen om een ​​POTM bestand naar ODP te converteren met behulp van PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad POTM bestand met een instantie van de klasse Presentatie{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de `save`-methode aan terwijl u het pad van het uitvoerbestand & SaveFormat.ODP specificeert als parameters{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}POTM bestand wordt opgeslagen op het opgegeven pad{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="systeem vereisten" intro="Voordat u de broncode van het PHP-conversievoorbeeld uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer PHP 7, voeg pad naar PHP toe aan systeemvariabele `PATH` en zet `allow_url_include` op `On` in `php.ini`-bestand.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer JRE 8. Stel de `JAVA_HOME` omgevingsvariabele in als een pad naar de geïnstalleerde JRE-locatie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer Apache Tomcat 8.0 (zie [meer](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Gebouwd met Aspose.Slides" title="POTM online converteren naar ODP" description="De gratis app Aspose.Slides Conversion is gebouwd met [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/nl/php-java/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen POTM-bestanden." button="Aspose.Slides Conversion openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" upload="Sleep of upload uw bestand" saveAs="Opslaan als" convert="Converteren" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides bestanden converteert voordat u code schrijft.
- Upload POTM-bestanden en sla ze op als ODP.
- Download het resultaat of converteer meer bestanden.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde conversies" subTitle="U kunt POTM ook naar vele andere bestandsindelingen converteren. Bekijk hieronder andere ondersteunde conversies" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-bmp/" name="POTM TO BMP" description="Bitmap afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-fodp/" name="POTM TO FODP" description="OpenDocument Flat XML-presentatie" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-gif/" name="POTM TO GIF" description="Grafisch uitwisselingsformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-html/" name="POTM TO HTML" description="Hypertekst-opmaaktaal" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-jpg/" name="POTM TO JPG" description="JPEG-afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-otp/" name="POTM TO OTP" description="Standaardformaat OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-pdf/" name="POTM TO PDF" description="Draagbaar documentformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-png/" name="POTM TO PNG" description="Draagbare netwerkgrafieken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-pot/" name="POTM TO POT" description="Microsoft PowerPoint-sjabloonbestanden" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-potx/" name="POTM TO POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-pps/" name="POTM TO PPS" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Diavoorstelling met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Presentatiebestand met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Open XML-presentatie-indeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-svg/" name="POTM TO SVG" description="Schaalbare vectorafbeeldingen" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-swf/" name="POTM TO SWF" description="SWF-formaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Gelabelde afbeeldingsindeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/potm-to-xps/" name="POTM TO XPS" description="XML-papierspecificaties" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
