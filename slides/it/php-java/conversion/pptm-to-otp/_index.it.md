---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti PPTM in OTP in PHP
weight: 2380
url: /it/php-java/conversion/pptm-to-otp/ 
keywords: "Convert, PowerPoint, PPTM, OTP, Presentation, PHP"
description: Codice di esempio per la conversione PHP da PPTM a OTP. Usa l'API PHP di PowerPoint per la conversione batch di file PPTM in file OTP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti PPTM in OTP in PHP" h2="Potente libreria PHP di PowerPoint per la conversione da PPTM a OTP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti PPTM in OTP in PHP" %}}

Devi convertire i file PPTM in OTP a livello di codice? Utilizzando [*Aspose.Slides per PHP via Java*](https://products.aspose.com/slides/it/php-java/) qualsiasi sviluppatore può convertire il formato PPTM in OTP con poche righe di codice PHP .

In quanto moderna API di elaborazione delle presentazioni, Aspose.Slides per PHP crea rapidamente OTP da PPTM. Verifica la qualità della conversione da PPTM a OTP direttamente nel tuo [browser](https://products.aspose.app/slides/conversion). La libreria Aspose PowerPoint PPTX ti consente di convertire i file PPTM in molti formati popolari.

È possibile installare la libreria da [Composer](https://packagist.org/packages/aspose/slides) utilizzando il comando seguente:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminale" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Salva PPTM come OTP in PHP" %}}

Usa l'app gratuita per vedere una dimostrazione del processo di conversione da PPTM a OTP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Questo codice di esempio mostra la conversione PHP da PPTM a OTP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptm");
try
{
    $pres->save("output.otp", SaveFormat::Otp);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come convertire PPTM in OTP in PHP" intro="Questi sono i passaggi per convertire un file PPTM in OTP usando PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file PPTM con un'istanza della classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama il metodo `save` mentre specifichi il percorso del file di output e SaveFormat.OTP come parametri{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Il file PPTM verrà salvato nel percorso specificato{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Requisiti di sistema" intro="Prima di eseguire il codice sorgente di esempio di conversione PHP, assicurati di disporre dei seguenti prerequisiti." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa PHP 7, aggiungi il percorso di PHP alla variabile `PATH` di sistema e imposta `allow_url_include` su `On` nel file `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installare JRE 8. Impostare la variabile di ambiente `JAVA_HOME` come percorso per la posizione JRE installata.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa Apache Tomcat 8.0 (vedi [altro](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Realizzato con Aspose.Slides" title="Converti PPTM in OTP online" description="L'app gratuita Aspose.Slides Conversion è realizzata con [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/it/php-java/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPTM." button="Apri Aspose.Slides Conversion" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" upload="Trascina o carica il tuo file" saveAs="Salva come" convert="Converti" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides converte i file prima di scrivere codice.
- Carica file PPTM e salvali come OTP.
- Scarica il risultato o converti altri file.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altre conversioni supportate" subTitle="Puoi anche convertire PPTM in molti altri formati di file. Vedi altre conversioni supportate di seguito" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Immagine bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-fodp/" name="PPTM TO FODP" description="Presentazione XML piatta di OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Formato di scambio grafico" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-html/" name="PPTM TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-jpg/" name="PPTM TO JPG" description="Immagine JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Formato di presentazione OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Formato documento portatile" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-png/" name="PPTM TO PNG" description="Grafica di rete portatile" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-pot/" name="PPTM TO POT" description="File modello di Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-potm/" name="PPTM TO POTM" description="File modello Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Presentazione del modello di Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Presentazione di PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Presentazione con attivazione macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Presentazione di PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Apri il formato di presentazione XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Grafica vettoriale scalabile" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Formato immagine contrassegnato" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Specifiche della carta XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
