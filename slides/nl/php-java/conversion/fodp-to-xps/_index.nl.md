---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer FODP naar XPS in PHP
weight: 210
url: /nl/php-java/conversion/fodp-to-xps/ 
keywords: "Convert, PowerPoint, FODP, XPS, Presentation, PHP"
description: Voorbeeldcode voor FODP naar XPS PHP-conversie. Gebruik PowerPoint PHP API voor batchconversie van FODP-bestanden naar XPS-bestanden.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer FODP naar XPS in PHP" h2="Krachtige PowerPoint PHP-bibliotheek voor het converteren van FODP naar XPS"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer FODP naar XPS in PHP" %}}

Wilt u FODP-bestanden programmatisch naar XPS converteren? Met behulp van [*Aspose.Slides voor PHP via Java*](https://products.aspose.com/slides/nl/php-java/) kan elke ontwikkelaar FODP naar XPS-indeling converteren met slechts een paar regels PHP-code .

Als een moderne API voor het verwerken van presentaties, maakt Aspose.Slides voor PHP snel XPS van FODP. Test de kwaliteit van de conversie van FODP naar XPS rechtstreeks in uw [browser](https://products.aspose.app/slides/conversion). Met de Aspose PowerPoint PPTX-bibliotheek kunt u FODP-bestanden converteren naar veel populaire formaten.

U kunt de bibliotheek installeren vanaf [Composer](https://packagist.org/packages/aspose/slides) met behulp van de volgende opdracht:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sla FODP op als XPS in PHP" %}}

Gebruik de gratis app om een ​​demonstratie te zien van het conversieproces van FODP naar XPS.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Deze voorbeeldcode toont FODP naar XPS PHP-conversie" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.fodp");
try
{
    $pres->save("output.xps", SaveFormat::Xps);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe FODP naar XPS te converteren in PHP" intro="Dit zijn de stappen om een ​​FODP bestand naar XPS te converteren met behulp van PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad FODP bestand met een instantie van de klasse Presentatie{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de `save`-methode aan terwijl u het pad van het uitvoerbestand & SaveFormat.XPS specificeert als parameters{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}FODP bestand wordt opgeslagen op het opgegeven pad{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="systeem vereisten" intro="Voordat u de broncode van het PHP-conversievoorbeeld uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer PHP 7, voeg pad naar PHP toe aan systeemvariabele `PATH` en zet `allow_url_include` op `On` in `php.ini`-bestand.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer JRE 8. Stel de `JAVA_HOME` omgevingsvariabele in als een pad naar de geïnstalleerde JRE-locatie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer Apache Tomcat 8.0 (zie [meer](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Gebouwd met Aspose.Slides" title="FODP online converteren naar XPS" description="De gratis app Aspose.Slides Conversion is gebouwd met [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/nl/php-java/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen FODP-bestanden." button="Aspose.Slides Conversion openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" upload="Sleep of upload uw bestand" saveAs="Opslaan als" convert="Converteren" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides bestanden converteert voordat u code schrijft.
- Upload FODP-bestanden en sla ze op als XPS.
- Download het resultaat of converteer meer bestanden.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde conversies" subTitle="U kunt FODP ook naar vele andere bestandsindelingen converteren. Bekijk hieronder andere ondersteunde conversies" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-bmp/" name="FODP TO BMP" description="Bitmap afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-gif/" name="FODP TO GIF" description="Grafisch uitwisselingsformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-html/" name="FODP TO HTML" description="Hypertekst-opmaaktaal" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-jpg/" name="FODP TO JPG" description="JPEG-afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-odp/" name="FODP TO ODP" description="Presentatie-indeling OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-otp/" name="FODP TO OTP" description="Standaardformaat OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-pdf/" name="FODP TO PDF" description="Draagbaar documentformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-png/" name="FODP TO PNG" description="Draagbare netwerkgrafieken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-pot/" name="FODP TO POT" description="Microsoft PowerPoint-sjabloonbestanden" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-potm/" name="FODP TO POTM" description="Microsoft PowerPoint-sjabloonbestand" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-potx/" name="FODP TO POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-pps/" name="FODP TO PPS" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Diavoorstelling met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Presentatiebestand met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Open XML-presentatie-indeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-svg/" name="FODP TO SVG" description="Schaalbare vectorafbeeldingen" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-swf/" name="FODP TO SWF" description="SWF-formaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Gelabelde afbeeldingsindeling" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
