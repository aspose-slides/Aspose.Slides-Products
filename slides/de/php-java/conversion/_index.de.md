---
title: Konvertierung von Microsoft PowerPoint-Präsentationen in PDF in PHP
url: /de/php-java/conversion/
keywords: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP-API zum Konvertieren von PPT in PDF. Konvertieren Sie Präsentationen in JPG, PNG und andere Formate in PHP.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint-Präsentation in PDF-Konvertierung in PHP" h2="PHP-Quellcodes für verschiedene Konvertierungsfälle zum Konvertieren von PPT in PDF, PNG, HTML, JPEG, PPTX und andere Formate." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides for PHP via Java](https://products.aspose.com/slides/de/php-java/) ist eine leistungsstarke On-Premise-Klassenbibliothek, die zum Verarbeiten und Arbeiten mit Präsentationen verwendet wird. Für die Entwickler ist es einfach, PowerPoint schnell und genau in PDF umzuwandeln. Erhalten Sie innerhalb kürzester Zeit die Ergebnisse für die Automatisierung der Geschäftsprozesse. Wir diskutieren hier einige Fälle zum Lesen oder Laden von Eingaben [unterstützte PowerPoint-Formate](https://docs.aspose.com/slides/php-java/supported-file-formats/) und zum Schreiben oder Speichern in einem beliebigen unterstützten Ausgabeformat . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint-zu-PDF-Konvertierung in PHP" %}}
Mit [Aspose.Slides](https://products.aspose.com/slides/de/php-java/) können Sie Dateien in den Formaten PowerPoint PPT, PPTX und OpenOffice ODP in PDF konvertieren. Um eine Präsentation in PDF umzuwandeln, übergeben Sie einfach den Dateinamen und das Speicherformat an die Methode „Presentation.save“. Die „Presentation“-Klasse legt die „save“-Methode offen, die aufgerufen werden kann, um die gesamte PPT-, PPTX- oder ODP-Präsentation in ein PDF-Dokument zu konvertieren.

{{% blocks/products/pf/feature-page-code h3="PHP-PowerPoint-zu-PDF-Konvertierung" %}}

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

{{% blocks/products/pf/feature-page-section  h2="PDF-zu-PPT-Konvertierung in PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/de/php-java/) ermöglicht Ihnen das Importieren von Präsentationen aus PDFs. Im Wesentlichen können Sie ein PDF in eine PowerPoint-Präsentation konvertieren. Führen Sie die folgenden Schritte aus, um PDF in Powerpoint zu konvertieren:
- Instanziieren Sie ein Objekt der Klasse "Präsentation".
- Rufen Sie die `addFromPdf`-Methode auf und übergeben Sie die PDF-Datei.
- Verwenden Sie die „Speichern“-Methode, um die Datei im PowerPoint-Format zu speichern.

{{% blocks/products/pf/feature-page-code h3="PHP-PDF-zu-Powerpoint-Konvertierung" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PPT in PDF mit benutzerdefinierten Optionen in PHP" %}}

Um PowerPoint-Folien genau in PDF zu konvertieren, können Programmierer das Dokument mit der Klasse „Präsentation“ laden und die Klasse „PdfOptions“ für alle spezifischen und benutzerdefinierten Optionen wie Textkomprimierungsstufe, JPEG-Qualität, das Verhalten von Metadateien, Konvertieren versteckter Folien sowie Auswählen verwenden bestimmte Folien und mehr. Es besteht sogar die Möglichkeit, die konvertierte PDF-Datei mit einem Passwort zu schützen.
{{% blocks/products/pf/feature-page-code h3="PHP-Konvertierung von PowerPoint in PDF mit benutzerdefinierten Einstellungen" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Konvertierung von Microsoft PowerPoint in HTML in PHP" %}}
Wann immer Präsentationen in Webseiten eingebettet werden müssen, müssen Folien in HTML konvertiert werden. 
{{% blocks/products/pf/feature-page-code h3="PHP-Code für PowerPoint-zu-HTML-Konvertierung" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PowerPoint in JPG" %}}
Das Konvertieren von Microsoft<sup>®</sup> PowerPoint-Formaten in JPEG-, PNG-, TIFF-Bilder usw. ist ein weiterer häufiger Anwendungsfall, der hauptsächlich zum Erstellen von Miniaturansichten von Folien verwendet wird. 
{{% blocks/products/pf/feature-page-code h3="PHP-PPT-zu-JPG-Konvertercode" %}}
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