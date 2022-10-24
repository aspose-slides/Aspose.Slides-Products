---
title: Converteer PPS naar PDF in PHP
weight: 1550
url: /nl/php-java/conversion/pps-to-pdf/ 
keywords: "Convert, PowerPoint, PPS, PDF, Presentation, PHP"
description: Voorbeeldcode voor PPS naar PDF PHP-conversie. Gebruik PowerPoint PHP API voor batchconversie van PPS-bestanden naar PDF-bestanden.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converteer PPS naar PDF in PHP" h2="Krachtige PowerPoint PHP-bibliotheek voor het converteren van PPS naar PDF" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Converteer PPS naar PDF in PHP" %}}

Wilt u PPS-bestanden programmatisch naar PDF converteren? Met behulp van [*Aspose.Slides voor PHP via Java*](https://products.aspose.com/slides/nl/php-java/) kan elke ontwikkelaar PPS naar PDF-indeling converteren met slechts een paar regels PHP-code .

Als een moderne API voor het verwerken van presentaties, maakt Aspose.Slides voor PHP snel PDF van PPS. Test de kwaliteit van de conversie van PPS naar PDF rechtstreeks in uw [browser](https://products.aspose.app/slides/conversion). Met de Aspose PowerPoint PPTX-bibliotheek kunt u PPS-bestanden converteren naar veel populaire formaten.

U kunt de bibliotheek installeren vanaf [Composer](https://packagist.org/packages/aspose/slides) met behulp van de volgende opdracht:

{{% blocks/products/pf/agp/code-block title="Console/Terminal" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Hoe PPS naar PDF te converteren in PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om een ​​PPS bestand naar PDF te converteren met behulp van PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad PPS bestand met een instantie van de klasse Presentatie
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Roep de `save`-methode aan terwijl u het pad van het uitvoerbestand & SaveFormat.PDF specificeert als parameters
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPS bestand wordt opgeslagen op het opgegeven pad
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Voordat u de broncode van het PHP-conversievoorbeeld uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

1. Installeer PHP 7, voeg pad naar PHP toe aan systeemvariabele `PATH` en zet `allow_url_include` op `On` in `php.ini`-bestand.
1. Installeer JRE 8. Stel de `JAVA_HOME` omgevingsvariabele in als een pad naar de geïnstalleerde JRE-locatie.
1. Installeer Apache Tomcat 8.0 (zie [meer](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Deze voorbeeldcode toont PPS naar PDF PHP-conversie" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pps");
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
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Sla PPS op als PDF in PHP" %}}
Gebruik de gratis app om een ​​demonstratie te zien van het conversieproces van PPS naar PDF. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PPS to PDF" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="U kunt PPS ook naar vele andere bestandsindelingen converteren. Bekijk hieronder andere ondersteunde conversies" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-bmp/" name="PPS TO BMP" description="Bitmap afbeelding" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-fodp/" name="PPS TO FODP" description="OpenDocument Flat XML-presentatie" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-gif/" name="PPS TO GIF" description="Grafisch uitwisselingsformaat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-html/" name="PPS TO HTML" description="Hypertekst-opmaaktaal" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-jpg/" name="PPS TO JPG" description="JPEG-afbeelding" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-odp/" name="PPS TO ODP" description="Presentatie-indeling OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-otp/" name="PPS TO OTP" description="Standaardformaat OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-png/" name="PPS TO PNG" description="Draagbare netwerkgrafieken" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-pot/" name="PPS TO POT" description="Microsoft PowerPoint-sjabloonbestanden" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-potm/" name="PPS TO POTM" description="Microsoft PowerPoint-sjabloonbestand" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-potx/" name="PPS TO POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Diavoorstelling met macro's" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-pptm/" name="PPS TO PPTM" description="Presentatiebestand met macro's" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Open XML-presentatie-indeling" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-svg/" name="PPS TO SVG" description="Schaalbare vectorafbeeldingen" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-swf/" name="PPS TO SWF" description="SWF-formaat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Gelabelde afbeeldingsindeling" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/pps-to-xps/" name="PPS TO XPS" description="XML-papierspecificaties" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}