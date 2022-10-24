---
title: Converti PPSX in PNG in PHP
weight: 1980
url: /it/php-java/conversion/ppsx-to-png/ 
keywords: "Convert, PowerPoint, PPSX, PNG, Presentation, PHP"
description: Codice di esempio per la conversione PHP da PPSX a PNG. Usa l'API PHP di PowerPoint per la conversione batch di file PPSX in file PNG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti PPSX in PNG in PHP" h2="Potente libreria PHP di PowerPoint per la conversione da PPSX a PNG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Converti PPSX in PNG in PHP" %}}

Devi convertire i file PPSX in PNG a livello di codice? Utilizzando [*Aspose.Slides per PHP via Java*](https://products.aspose.com/slides/it/php-java/) qualsiasi sviluppatore può convertire il formato PPSX in PNG con poche righe di codice PHP .

In quanto moderna API di elaborazione delle presentazioni, Aspose.Slides per PHP crea rapidamente PNG da PPSX. Verifica la qualità della conversione da PPSX a PNG direttamente nel tuo [browser](https://products.aspose.app/slides/conversion/ppt-to-png). La libreria Aspose PowerPoint PPTX ti consente di convertire i file PPSX in molti formati popolari.

È possibile installare la libreria da [Composer](https://packagist.org/packages/aspose/slides) utilizzando il comando seguente:

{{% blocks/products/pf/agp/code-block title="Console/Terminale" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Come convertire PPSX in PNG in PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per convertire un file PPSX in PNG usando PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica il file PPSX con un'istanza della classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chiama il metodo `save` mentre specifichi il percorso del file di output e SaveFormat.PNG come parametri
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Il file PPSX verrà salvato nel percorso specificato
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

{{% blocks/products/pf/agp/code-block title="Questo codice di esempio mostra la conversione PHP da PPSX a PNG" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsx");
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
 
{{% blocks/products/pf/agp/content h2="Salva PPSX come PNG in PHP" %}}
Usa l'app gratuita per vedere una dimostrazione del processo di conversione da PPSX a PNG. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PPSX to PNG" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire PPSX in molti altri formati di file. Vedi altre conversioni supportate di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Immagine bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" description="Presentazione XML piatta di OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Formato di scambio grafico" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-jpg/" name="PPSX TO JPG" description="Immagine JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="Formato di presentazione OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Formato standard OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Formato documento portatile" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-pot/" name="PPSX TO POT" description="File modello di Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="File modello Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Presentazione del modello di Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="Presentazione di PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Presentazione con attivazione macro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="File di presentazione abilitato per le macro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Apri il formato di presentazione XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Grafica vettoriale scalabile" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Formato immagine contrassegnato" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="Specifiche della carta XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}