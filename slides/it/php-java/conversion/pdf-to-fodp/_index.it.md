---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti PDF in FODP in PHP
weight: 650
url: /it/php-java/conversion/pdf-to-fodp/ 
keywords: "Convert, PowerPoint, PDF, FODP, Presentation, PHP"
description: Codice di esempio per la conversione PHP da PDF a FODP. Usa l'API PHP di PowerPoint per la conversione batch di file PDF in file FODP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti PDF in FODP in PHP" h2="Potente libreria PHP di PowerPoint per la conversione da PDF a FODP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti PDF in FODP in PHP" %}}

Devi convertire i file PDF in FODP a livello di codice? Utilizzando [*Aspose.Slides per PHP via Java*](https://products.aspose.com/slides/it/php-java/) qualsiasi sviluppatore può convertire il formato PDF in FODP con poche righe di codice PHP .

In quanto moderna API di elaborazione delle presentazioni, Aspose.Slides per PHP crea rapidamente FODP da PDF. Verifica la qualità della conversione da PDF a FODP direttamente nel tuo [browser](https://products.aspose.app/slides/conversion). La libreria Aspose PowerPoint PPTX ti consente di convertire i file PDF in molti formati popolari.

È possibile installare la libreria da [Composer](https://packagist.org/packages/aspose/slides) utilizzando il comando seguente:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminale" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Salva PDF come FODP in PHP" %}}

Usa l'app gratuita per vedere una dimostrazione del processo di conversione da PDF a FODP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Questo codice di esempio mostra la conversione PHP da PDF a FODP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come convertire PDF in FODP in PHP" intro="Questi sono i passaggi per convertire un file PDF in FODP usando PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file PDF con un'istanza della classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama il metodo `save` mentre specifichi il percorso del file di output e SaveFormat.FODP come parametri{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Il file PDF verrà salvato nel percorso specificato{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Requisiti di sistema" intro="Prima di eseguire il codice sorgente di esempio di conversione PHP, assicurati di disporre dei seguenti prerequisiti." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa PHP 7, aggiungi il percorso di PHP alla variabile `PATH` di sistema e imposta `allow_url_include` su `On` nel file `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installare JRE 8. Impostare la variabile di ambiente `JAVA_HOME` come percorso per la posizione JRE installata.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa Apache Tomcat 8.0 (vedi [altro](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Realizzato con Aspose.Slides" title="Converti PDF in FODP online" description="L'app gratuita Aspose.Slides Conversion è realizzata con [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/it/php-java/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PDF." button="Apri Aspose.Slides Conversion" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" upload="Trascina o carica il tuo file" saveAs="Salva come" convert="Converti" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides converte i file prima di scrivere codice.
- Carica file PDF e salvali come FODP.
- Scarica il risultato o converti altri file.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altre conversioni supportate" subTitle="Puoi anche convertire PDF in molti altri formati di file. Vedi altre conversioni supportate di seguito" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-bmp/" name="PDF TO BMP" description="Immagine bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-gif/" name="PDF TO GIF" description="Formato di scambio grafico" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-html/" name="PDF TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" description="Immagine JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-odp/" name="PDF TO ODP" description="Formato di presentazione OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-otp/" name="PDF TO OTP" description="Formato standard OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-png/" name="PDF TO PNG" description="Grafica di rete portatile" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-pot/" name="PDF TO POT" description="File modello di Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-potm/" name="PDF TO POTM" description="File modello Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-potx/" name="PDF TO POTX" description="Presentazione del modello di Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-pps/" name="PDF TO PPS" description="Presentazione di PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="Presentazione con attivazione macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="Presentazione di PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-ppt/" name="PDF TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="File di presentazione abilitato per le macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="Apri il formato di presentazione XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-svg/" name="PDF TO SVG" description="Grafica vettoriale scalabile" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-swf/" name="PDF TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="Formato immagine contrassegnato" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-xps/" name="PDF TO XPS" description="Specifiche della carta XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
