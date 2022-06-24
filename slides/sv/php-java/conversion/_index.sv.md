---
title: Microsoft PowerPoint Presentation Konvertering till PDF i PHP
url: /sv/php-java/conversion/
keywords: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP API för att konvertera PPT till PDF. Konvertera presentationer till JPG, PNG och andra format i PHP.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint-presentation till PDF-konvertering i PHP" h2="PHP-källkoder för olika konverteringsfall för att konvertera PPT till PDF, PNG, HTML, JPEG, PPTX och andra format." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides för PHP via Java](https://products.aspose.com/slides/sv/php-java/) är ett kraftfullt lokalt klassbibliotek som används för att bearbeta och arbeta med presentationer. Det är lätt för utvecklarna att konvertera PowerPoint till PDF med snabbhet och noggrannhet. Få resultaten inom nolltid för att automatisera affärsprocesserna. Vi diskuterar här några fall för att läsa eller ladda indata [PowerPoint-format som stöds](https://docs.aspose.com/slides/php-java/supported-file-formats/) och skriva eller spara till vilket utdataformat som stöds . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint till PDF-konvertering i PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/sv/php-java/) låter dig konvertera filer i PowerPoint PPT-, PPTX- och OpenOffice ODP-format till PDF. För att konvertera en presentation till PDF, skicka helt enkelt filnamnet och spara formatet till metoden `Presentation.save`. Klassen `Presentation` exponerar `spara`-metoden som kan anropas för att konvertera hela PPT-, PPTX- eller ODP-presentationen till ett PDF-dokument.

{{% blocks/products/pf/feature-page-code h3="PHP PowerPoint till PDF-konvertering" %}}

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

{{% blocks/products/pf/feature-page-section  h2="PDF till PPT-konvertering i PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/sv/php-java/) låter dig importera presentationer från PDF-filer. I huvudsak får du konvertera en PDF till en PowerPoint-presentation. För att konvertera PDF till Powerpoint, gå igenom dessa steg:
- Instantiera ett objekt av klassen 'Presentation'.
- Anropa "addFromPdf"-metoden och skicka PDF-filen.
- Använd "spara"-metoden för att spara filen i PowerPoint-format.

{{% blocks/products/pf/feature-page-code h3="PHP PDF till Powerpoint-konvertering" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Konvertera PPT till PDF med anpassade alternativ i PHP" %}}

För att konvertera PowerPoint-bilder till PDF korrekt kan programmerare ladda dokumentet med klassen 'Presentation' och använda klassen 'PdfOptions' för alla specifika och anpassade alternativ som textkomprimeringsnivå, Jpeg-kvalitet, beteendet hos metafiler, konvertera dolda bilder samt välja specifika bilder och mer. Även det finns möjlighet att skydda den konverterade PDF-filen med lösenord.
{{% blocks/products/pf/feature-page-code h3="PHP PowerPoint till PDF-konvertering med anpassade inställningar" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint till HTML-konvertering i PHP" %}}
När det någonsin finns behov av att bädda in presentationer på webbsidor, då finns det ett behov av att konvertera bilder till HTML. 
{{% blocks/products/pf/feature-page-code h3="PHP-kod för PowerPoint till HTML-konvertering" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Konvertera PowerPoint till JPG" %}}
Att konvertera Microsoft<sup>®</sup> PowerPoint-format till bilder JPEG, PNG, TIFF etc är ett annat vanligt användningsfall som oftast används för att skapa miniatyrbilder av bilder. 
{{% blocks/products/pf/feature-page-code h3="PHP PPT till JPG Converter Code" %}}
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