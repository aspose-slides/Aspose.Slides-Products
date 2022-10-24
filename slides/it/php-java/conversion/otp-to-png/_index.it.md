---
title: Converti OTP in PNG in PHP
weight: 500
url: /it/php-java/conversion/otp-to-png/ 
keywords: "Convert, PowerPoint, OTP, PNG, Presentation, PHP"
description: Codice di esempio per la conversione PHP da OTP a PNG. Usa l'API PHP di PowerPoint per la conversione batch di file OTP in file PNG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti OTP in PNG in PHP" h2="Potente libreria PHP di PowerPoint per la conversione da OTP a PNG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Converti OTP in PNG in PHP" %}}

Devi convertire i file OTP in PNG a livello di codice? Utilizzando [*Aspose.Slides per PHP via Java*](https://products.aspose.com/slides/it/php-java/) qualsiasi sviluppatore può convertire il formato OTP in PNG con poche righe di codice PHP .

In quanto moderna API di elaborazione delle presentazioni, Aspose.Slides per PHP crea rapidamente PNG da OTP. Verifica la qualità della conversione da OTP a PNG direttamente nel tuo [browser](https://products.aspose.app/slides/conversion/ppt-to-png). La libreria Aspose PowerPoint PPTX ti consente di convertire i file OTP in molti formati popolari.

È possibile installare la libreria da [Composer](https://packagist.org/packages/aspose/slides) utilizzando il comando seguente:

{{% blocks/products/pf/agp/code-block title="Console/Terminale" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Come convertire OTP in PNG in PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per convertire un file OTP in PNG usando PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica il file OTP con un'istanza della classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chiama il metodo `save` mentre specifichi il percorso del file di output e SaveFormat.PNG come parametri
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Il file OTP verrà salvato nel percorso specificato
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice sorgente di esempio di conversione PHP, assicurati di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

1. Installa PHP 7, aggiungi il percorso di PHP alla variabile `PATH` di sistema e imposta `allow_url_include` su `On` nel file `php.ini`.
1. Installare JRE 8. Impostare la variabile di ambiente `JAVA_HOME` come percorso per la posizione JRE installata.
1. Installa Apache Tomcat 8.0 (vedi [altro](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Questo codice di esempio mostra la conversione PHP da OTP a PNG" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.otp");
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
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Salva OTP come PNG in PHP" %}}
Usa l'app gratuita per vedere una dimostrazione del processo di conversione da OTP a PNG. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert OTP to PNG" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire OTP in molti altri formati di file. Vedi altre conversioni supportate di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-bmp/" name="OTP TO BMP" description="Immagine bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-fodp/" name="OTP TO FODP" description="Presentazione XML piatta di OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-gif/" name="OTP TO GIF" description="Formato di scambio grafico" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-html/" name="OTP TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-jpg/" name="OTP TO JPG" description="Immagine JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-odp/" name="OTP TO ODP" description="Formato di presentazione OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-pdf/" name="OTP TO PDF" description="Formato documento portatile" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-pot/" name="OTP TO POT" description="File modello di Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-potm/" name="OTP TO POTM" description="File modello Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-potx/" name="OTP TO POTX" description="Presentazione del modello di Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-pps/" name="OTP TO PPS" description="Presentazione di PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="Presentazione con attivazione macro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="Presentazione di PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-ppt/" name="OTP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-pptm/" name="OTP TO PPTM" description="File di presentazione abilitato per le macro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-pptx/" name="OTP TO PPTX" description="Apri il formato di presentazione XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-svg/" name="OTP TO SVG" description="Grafica vettoriale scalabile" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-swf/" name="OTP TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-tiff/" name="OTP TO TIFF" description="Formato immagine contrassegnato" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/otp-to-xps/" name="OTP TO XPS" description="Specifiche della carta XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}