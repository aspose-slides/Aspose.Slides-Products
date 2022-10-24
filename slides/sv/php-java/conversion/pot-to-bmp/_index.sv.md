---
title: Konvertera POT till BMP i PHP
weight: 850
url: /sv/php-java/conversion/pot-to-bmp/ 
keywords: "Convert, PowerPoint, POT, BMP, Presentation, PHP"
description: Exempelkod för PHP-konvertering från POT till BMP. Använd PowerPoint PHP API för batchkonvertering av POT-filer till BMP-filer.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera POT till BMP i PHP" h2="Kraftfullt PowerPoint PHP-bibliotek för att konvertera POT till BMP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Konvertera POT till BMP i PHP" %}}

Behöver du konvertera POT-filer till BMP programmatiskt? Genom att använda [*Aspose.Slides för PHP via Java*](https://products.aspose.com/slides/sv/php-java/) kan alla utvecklare konvertera POT till BMP-format med bara några rader PHP-kod .

Som ett modernt presentationsbearbetnings-API skapar Aspose.Slides för PHP snabbt BMP från POT. Testa kvaliteten på konverteringen från POT till BMP direkt i din [webbläsare](https://products.aspose.app/slides/conversion). Aspose PowerPoint PPTX-bibliotek låter dig konvertera POT-filer till många populära format.

Du kan installera biblioteket från [Composer](https://packagist.org/packages/aspose/slides) med följande kommando:

{{% blocks/products/pf/agp/code-block title="Konsol/Terminal" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Hur man konverterar POT till BMP i PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att konvertera en POT-fil till BMP med PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda filen POT med en instans av presentationsklassen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Anropa "spara"-metoden samtidigt som du anger sökväg för utdatafil och SaveFormat.BMP som parametrar
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Filen POT kommer att sparas på den angivna sökvägen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör källkoden för PHP-konverteringsexemplet, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

1. Installera PHP 7, lägg till sökväg till PHP till systemvariabeln "PATH" och ställ in "allow_url_include" till "På" i filen "php.ini".
1. Installera JRE 8. Ställ in miljövariabeln `JAVA_HOME` som en sökväg till den installerade JRE-platsen.
1. Installera Apache Tomcat 8.0 (se [mer](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Den här exempelkoden visar PHP-konvertering från POT till BMP" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pot");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".bmp");
        $imageio->write($bmp, "BMP", $javafile);
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
 
{{% blocks/products/pf/agp/content h2="Spara POT som BMP i PHP" %}}
Använd gratisappen för att se en demonstration av konverteringsprocessen från POT till BMP. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert POT to BMP" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera POT till många andra filformat. Se andra omvandlingar som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-fodp/" name="POT TO FODP" description="OpenDocument platt XML-presentation" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-gif/" name="POT TO GIF" description="Grafiskt utbytesformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-html/" name="POT TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-jpg/" name="POT TO JPG" description="JPEG-bild" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-odp/" name="POT TO ODP" description="OpenDocument presentationsformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-otp/" name="POT TO OTP" description="OpenDocument standardformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-pdf/" name="POT TO PDF" description="Portabelt dokumentformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-png/" name="POT TO PNG" description="Bärbar nätverksgrafik" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-potm/" name="POT TO POTM" description="Microsoft PowerPoint-mallfil" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-potx/" name="POT TO POTX" description="Presentation av Microsoft PowerPoint-mall" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-pps/" name="POT TO PPS" description="PowerPoint-bildspel" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Makroaktiverat bildspel" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-ppsx/" name="POT TO PPSX" description="PowerPoint-bildspel" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-pptm/" name="POT TO PPTM" description="Makroaktiverad presentationsfil" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-pptx/" name="POT TO PPTX" description="Öppna XML-presentationsformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-svg/" name="POT TO SVG" description="Skalbar vektorgrafik" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-swf/" name="POT TO SWF" description="SWF-format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-tiff/" name="POT TO TIFF" description="Taggad bildformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pot-to-xps/" name="POT TO XPS" description="XML-pappersspecifikationer" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}