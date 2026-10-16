---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti PPTX in PDF in PHP
weight: 2600
url: /it/php-java/conversion/pptx-to-pdf/ 
keywords: "Convert, PowerPoint, PPTX, PDF, Presentation, PHP"
description: Codice di esempio per la conversione PHP da PPTX a PDF. Usa l'API PHP di PowerPoint per la conversione batch di file PPTX in file PDF.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti PPTX in PDF in PHP" h2="Potente libreria PHP di PowerPoint per la conversione da PPTX a PDF"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti PPTX in PDF in PHP" %}}

Devi convertire i file PPTX in PDF a livello di codice? Utilizzando [*Aspose.Slides per PHP via Java*](https://products.aspose.com/slides/it/php-java/) qualsiasi sviluppatore può convertire il formato PPTX in PDF con poche righe di codice PHP .

In quanto moderna API di elaborazione delle presentazioni, Aspose.Slides per PHP crea rapidamente PDF da PPTX. Verifica la qualità della conversione da PPTX a PDF direttamente nel tuo [browser](https://products.aspose.app/slides/conversion). La libreria Aspose PowerPoint PPTX ti consente di convertire i file PPTX in molti formati popolari.

È possibile installare la libreria da [Composer](https://packagist.org/packages/aspose/slides) utilizzando il comando seguente:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminale" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Salva PPTX come PDF in PHP" %}}

Usa l'app gratuita per vedere una dimostrazione del processo di conversione da PPTX a PDF.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Questo codice di esempio mostra la conversione PHP da PPTX a PDF" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptx");
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come convertire PPTX in PDF in PHP" intro="Questi sono i passaggi per convertire un file PPTX in PDF usando PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file PPTX con un'istanza della classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama il metodo `save` mentre specifichi il percorso del file di output e SaveFormat.PDF come parametri{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Il file PPTX verrà salvato nel percorso specificato{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Requisiti di sistema" intro="Prima di eseguire il codice sorgente di esempio di conversione PHP, assicurati di disporre dei seguenti prerequisiti." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa PHP 7, aggiungi il percorso di PHP alla variabile `PATH` di sistema e imposta `allow_url_include` su `On` nel file `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installare JRE 8. Impostare la variabile di ambiente `JAVA_HOME` come percorso per la posizione JRE installata.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa Apache Tomcat 8.0 (vedi [altro](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPTX to PDF"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altre conversioni supportate" subTitle="Puoi anche convertire PPTX in molti altri formati di file. Vedi altre conversioni supportate di seguito" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Immagine bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-fodp/" name="PPTX TO FODP" description="Presentazione XML piatta di OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Formato di scambio grafico" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-html/" name="PPTX TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-jpg/" name="PPTX TO JPG" description="Immagine JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-odp/" name="PPTX TO ODP" description="Formato di presentazione OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-otp/" name="PPTX TO OTP" description="Formato standard OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-png/" name="PPTX TO PNG" description="Grafica di rete portatile" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-pot/" name="PPTX TO POT" description="File modello di Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-potm/" name="PPTX TO POTM" description="File modello Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Presentazione del modello di Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-pps/" name="PPTX TO PPS" description="Presentazione di PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Presentazione con attivazione macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="Presentazione di PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="File di presentazione abilitato per le macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-svg/" name="PPTX TO SVG" description="Grafica vettoriale scalabile" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-swf/" name="PPTX TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Formato immagine contrassegnato" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptx-to-xps/" name="PPTX TO XPS" description="Specifiche della carta XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
