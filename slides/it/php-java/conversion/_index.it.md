---
title: Conversione della presentazione di Microsoft PowerPoint in PDF in PHP
url: /it/php-java/conversion/
keywords: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: API PHP per convertire PPT in PDF. Converti presentazioni in JPG, PNG e altri formati in PHP.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> Conversione da presentazione PowerPoint a PDF in PHP" h2="Codici sorgente PHP per diversi casi di conversione per convertire PPT in PDF, PNG, HTML, JPEG, PPTX e altri formati." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides per PHP tramite Java](https://products.aspose.com/slides/it/php-java/) è una potente libreria di classi on-premise utilizzata per elaborare e lavorare con le presentazioni. È facile per gli sviluppatori convertire PowerPoint in PDF con velocità e precisione. Ottieni i risultati in pochissimo tempo per automatizzare i processi aziendali. Stiamo discutendo qui alcuni casi per leggere o caricare qualsiasi input [formati PowerPoint supportati](https://docs.aspose.com/slides/php-java/supported-file-formats/) e scrivere o salvare in qualsiasi formato di output supportato . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Conversione da PowerPoint a PDF in PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/it/php-java/) consente di convertire file in formato PowerPoint PPT, PPTX e OpenOffice ODP in PDF. Per convertire una presentazione in PDF, passa semplicemente il nome del file e salva il formato nel metodo `Presentation.save`. La classe `Presentation` espone il metodo `save` che può essere chiamato per convertire l'intera presentazione PPT, PPTX o ODP in un documento PDF.

{{% blocks/products/pf/feature-page-code h3="Conversione da PHP a PDF" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
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
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf potm-to-pdf potx-to-pdf ppsm-to-pdf odp-to-pdf" >}}

{{% blocks/products/pf/feature-page-section  h2="Conversione da PDF a PPT in PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/it/php-java/) consente di importare presentazioni da PDF. In sostanza, puoi convertire un PDF in una presentazione PowerPoint. Per convertire PDF in Powerpoint, segui questi passaggi:
- Istanziare un oggetto della classe `Presentazione`.
- Chiama il metodo `addFromPdf` e passa il file PDF.
- Usa il metodo `save` per salvare il file nel formato PowerPoint.

{{% blocks/products/pf/feature-page-code h3="Conversione da PDF a PowerPoint" %}}

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
    $pres->save("output.pptx", SaveFormat::Pptx); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-ppt pdf-to-pptx pdf-to-odp pdf-to-png pdf-to-jpg pdf-to-html" >}}


{{% blocks/products/pf/feature-page-section  h2="Converti PPT in PDF con opzioni personalizzate in PHP" %}}

Per convertire accuratamente le diapositive PowerPoint in PDF, i programmatori possono caricare il documento utilizzando la classe "Presentazione" e utilizzare la classe "PdfOptions" per tutte le opzioni specifiche e personalizzate come il livello di compressione del testo, la qualità Jpeg, il comportamento dei metafile, la conversione di diapositive nascoste e la selezione diapositive specifiche e altro ancora. Anche c'è un'opzione per proteggere il file PDF convertito con una password.
{{% blocks/products/pf/feature-page-code h3="Conversione da PHP a PDF con impostazioni personalizzate" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\PdfOptions;
use aspose\slides\PdfTextCompression;
use aspose\slides\PdfCompliance;
 
$pres = new Presentation("input.pptx");
try
{
    $pdfOptions = new PdfOptions();
    $pdfOptions->setJpegQuality(90);
    $pdfOptions->setSaveMetafilesAsPng(true);
    $pdfOptions->setTextCompression(PdfTextCompression::Flate);
    $pdfOptions->setCompliance(PdfCompliance::Pdf15);
    $pres->save("output.pdf", SaveFormat::Pdf, $pdfOptions);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversione da Microsoft PowerPoint a HTML in PHP" %}}
Ogni volta che è necessario incorporare presentazioni all'interno di pagine Web, è necessario convertire le diapositive in HTML. 
{{% blocks/products/pf/feature-page-code h3="Codice PHP per la conversione da PowerPoint a HTML" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\Html5Options;
 
$pres = new Presentation("input.pptx");
try
{
    $html5Options = new Html5Options();
    $html5Options->setAnimateShapes(false);
    $html5Options->setAnimateTransitions(false);
    $pres->save("output.html", SaveFormat::Html5, $html5Options);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Converti PowerPoint in JPG" %}}
La conversione dei formati Microsoft<sup>®</sup> PowerPoint in immagini JPEG, PNG, TIFF ecc. è un altro caso d'uso comune utilizzato principalmente per la creazione di miniature di diapositive. 
{{% blocks/products/pf/feature-page-code h3="Codice del convertitore da PHP PPT a JPG" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
 
$pres = new Presentation("input.pptx");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(1, 1);
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
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-jpg pptx-to-jpg ppt-to-png pptx-to-png ppt-to-gif pptx-to-gif" >}}