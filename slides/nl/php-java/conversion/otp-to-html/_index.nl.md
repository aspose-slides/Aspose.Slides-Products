---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer OTP naar HTML in PHP
weight: 460
url: /nl/php-java/conversion/otp-to-html/ 
keywords: "Convert, PowerPoint, OTP, HTML, Presentation, PHP"
description: Voorbeeldcode voor OTP naar HTML PHP-conversie. Gebruik PowerPoint PHP API voor batchconversie van OTP-bestanden naar HTML-bestanden.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer OTP naar HTML in PHP" h2="Krachtige PowerPoint PHP-bibliotheek voor het converteren van OTP naar HTML"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer OTP naar HTML in PHP" %}}

Wilt u OTP-bestanden programmatisch naar HTML converteren? Met behulp van [*Aspose.Slides voor PHP via Java*](https://products.aspose.com/slides/nl/php-java/) kan elke ontwikkelaar OTP naar HTML-indeling converteren met slechts een paar regels PHP-code .

Als een moderne API voor het verwerken van presentaties, maakt Aspose.Slides voor PHP snel HTML van OTP. Test de kwaliteit van de conversie van OTP naar HTML rechtstreeks in uw [browser](https://products.aspose.app/slides/conversion). Met de Aspose PowerPoint PPTX-bibliotheek kunt u OTP-bestanden converteren naar veel populaire formaten.

U kunt de bibliotheek installeren vanaf [Composer](https://packagist.org/packages/aspose/slides) met behulp van de volgende opdracht:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sla OTP op als HTML in PHP" %}}

Gebruik de gratis app om een ​​demonstratie te zien van het conversieproces van OTP naar HTML.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Deze voorbeeldcode toont OTP naar HTML PHP-conversie" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.otp");
try
{
    $pres->save("output.html", SaveFormat::Html5);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe OTP naar HTML te converteren in PHP" intro="Dit zijn de stappen om een ​​OTP bestand naar HTML te converteren met behulp van PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad OTP bestand met een instantie van de klasse Presentatie{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de `save`-methode aan terwijl u het pad van het uitvoerbestand & SaveFormat.HTML specificeert als parameters{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}OTP bestand wordt opgeslagen op het opgegeven pad{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="systeem vereisten" intro="Voordat u de broncode van het PHP-conversievoorbeeld uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer PHP 7, voeg pad naar PHP toe aan systeemvariabele `PATH` en zet `allow_url_include` op `On` in `php.ini`-bestand.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer JRE 8. Stel de `JAVA_HOME` omgevingsvariabele in als een pad naar de geïnstalleerde JRE-locatie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer Apache Tomcat 8.0 (zie [meer](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Gebouwd met Aspose.Slides" title="OTP online converteren naar HTML" description="De gratis app Aspose.Slides Conversion is gebouwd met [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/nl/php-java/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen OTP-bestanden." button="Aspose.Slides Conversion openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" upload="Sleep of upload uw bestand" saveAs="Opslaan als" convert="Converteren" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides bestanden converteert voordat u code schrijft.
- Upload OTP-bestanden en sla ze op als HTML.
- Download het resultaat of converteer meer bestanden.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde conversies" subTitle="U kunt OTP ook naar vele andere bestandsindelingen converteren. Bekijk hieronder andere ondersteunde conversies" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-bmp/" name="OTP TO BMP" description="Bitmap afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-fodp/" name="OTP TO FODP" description="OpenDocument Flat XML-presentatie" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-gif/" name="OTP TO GIF" description="Grafisch uitwisselingsformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-jpg/" name="OTP TO JPG" description="JPEG-afbeelding" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-odp/" name="OTP TO ODP" description="Presentatie-indeling OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-pdf/" name="OTP TO PDF" description="Draagbaar documentformaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-png/" name="OTP TO PNG" description="Draagbare netwerkgrafieken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-pot/" name="OTP TO POT" description="Microsoft PowerPoint-sjabloonbestanden" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-potm/" name="OTP TO POTM" description="Microsoft PowerPoint-sjabloonbestand" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-potx/" name="OTP TO POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-pps/" name="OTP TO PPS" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="Diavoorstelling met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-ppt/" name="OTP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-pptm/" name="OTP TO PPTM" description="Presentatiebestand met macro's" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-pptx/" name="OTP TO PPTX" description="Open XML-presentatie-indeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-svg/" name="OTP TO SVG" description="Schaalbare vectorafbeeldingen" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-swf/" name="OTP TO SWF" description="SWF-formaat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-tiff/" name="OTP TO TIFF" description="Gelabelde afbeeldingsindeling" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/conversion/otp-to-xps/" name="OTP TO XPS" description="XML-papierspecificaties" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
