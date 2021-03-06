---
title: Převeďte PPTM do JPG v PHP
weight: 2360
url: /cs/php-java/conversion/pptm-to-jpg/ 
keywords: "Convert, PowerPoint, PPTM, JPG, Presentation, PHP"
description: Ukázkový kód pro konverzi PHP z PPTM do JPG. Použijte PowerPoint PHP API pro dávkový převod souborů PPTM na soubory JPG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Převeďte PPTM do JPG v PHP" h2="Výkonná PowerPoint PHP knihovna pro převod PPTM do JPG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Převeďte PPTM do JPG v PHP" %}}

Potřebujete převést soubory PPTM do JPG programově? Pomocí [*Aspose.Slides pro PHP přes Java*](https://products.aspose.com/slides/cs/php-java/) může každý vývojář převést PPTM do formátu JPG pomocí několika řádků kódu PHP .

Aspose.Slides pro PHP jako moderní API pro zpracování prezentací rychle vytváří JPG z PPTM. Otestujte kvalitu převodu PPTM na JPG přímo ve svém [prohlížeči](https://products.aspose.app/slides/conversion/ppt-to-jpg). Knihovna Aspose PowerPoint PPTX vám umožňuje převádět soubory PPTM do mnoha oblíbených formátů.

Knihovnu můžete nainstalovat z [Composer](https://packagist.org/packages/aspose/slides) pomocí následujícího příkazu:

{{% blocks/products/pf/agp/code-block title="Konzole/terminál" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Jak převést PPTM do JPG v PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k převodu souboru PPTM na JPG pomocí PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte soubor PPTM s instancí třídy Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zavolejte metodu `save`, přičemž jako parametry zadejte cestu k výstupnímu souboru a SaveFormat.JPG
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Soubor PPTM bude uložen do zadané cesty
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním ukázkového zdrojového kódu konverze PHP se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

1. Nainstalujte PHP 7, přidejte cestu k PHP do systémové proměnné `PATH` a nastavte `allow_url_include` na `On` v souboru `php.ini`.
1. Nainstalujte JRE 8. Nastavte proměnnou prostředí `JAVA_HOME` jako cestu k nainstalovanému umístění JRE.
1. Nainstalujte Apache Tomcat 8.0 (viz [více](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tento ukázkový kód ukazuje konverzi PHP z PPTM do JPG" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptm");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPEG", $javafile);
    }
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
 
{{% blocks/products/pf/agp/content h2="Uložit PPTM jako JPG v PHP" %}}
Použijte bezplatnou aplikaci a podívejte se na ukázku procesu převodu PPTM do JPG. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PPTM to JPG" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="Můžete také převést PPTM do mnoha dalších formátů souborů. Další podporované konverze naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Bitmapový obrázek" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-fodp/" name="PPTM TO FODP" description="OpenDocument Flat XML prezentace" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Grafický výměnný formát" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-html/" name="PPTM TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Formát prezentace OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-otp/" name="PPTM TO OTP" description="Standardní formát OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Přenosný formát dokumentu" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-png/" name="PPTM TO PNG" description="Přenosná síťová grafika" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-pot/" name="PPTM TO POT" description="Soubory šablon Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Soubor šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Prezentace PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Prezentace s podporou maker" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Prezentace PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Formát otevřené prezentace XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Škálovatelná vektorová grafika" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="Formát SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Formát tagovaného obrázku" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Specifikace papíru XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}