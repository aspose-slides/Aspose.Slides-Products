---
title: Microsoft PowerPoint-presentatieconversie naar PDF in PHP
url: /nl/php-java/conversion/
keyslides: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP API om PPT naar PDF te converteren. Converteer presentaties naar JPG, PNG en andere formaten in PHP.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint-presentatie naar PDF-conversie in PHP" h2="PHP-broncodes voor verschillende conversiegevallen om PPT naar PDF, PNG, HTML, JPEG, PPTX en andere formaten te converteren." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides voor PHP via Java](https://products.aspose.com/slides/nl/php-java/) is een krachtige lokale klassenbibliotheek die wordt gebruikt voor het verwerken van en werken met presentaties. Het is gemakkelijk voor de ontwikkelaars om PowerPoint snel en nauwkeurig naar PDF te converteren. Binnen de kortste keren de resultaten voor het automatiseren van de bedrijfsprocessen. We bespreken hier enkele gevallen om invoer [ondersteunde PowerPoint-indelingen](https://docs.aspose.com/slides/php-java/supported-file-formats/) te lezen of te laden en te schrijven of op te slaan in een ondersteund uitvoerformaat . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint naar PDF-conversie in PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/nl/php-java/) stelt u in staat bestanden in PowerPoint PPT-, PPTX- en OpenOffice ODP-indelingen naar PDF te converteren. Om een ​​presentatie naar PDF te converteren, geeft u eenvoudig de bestandsnaam door en slaat u het formaat op met de `Presentation.save`-methode. De klasse `Presentation` onthult de `save`-methode die kan worden aangeroepen om de hele PPT-, PPTX- of ODP-presentatie naar een PDF-document te converteren.

{{% blocks/products/pf/feature-page-code h3="PHP PowerPoint naar PDF conversie" %}}

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

{{% blocks/products/pf/feature-page-section  h2="PDF naar PPT-conversie in PHP" %}}
Met [Aspose.Slides](https://products.aspose.com/slides/nl/php-java/) kunt u presentaties importeren uit PDF's. In wezen kunt u een PDF converteren naar een PowerPoint-presentatie. Om PDF naar Powerpoint te converteren, doorloop je deze stappen:
- Instantieer een object van de klasse 'Presentatie'.
- Roep de methode `addFromPdf` aan en geef het PDF-bestand door.
- Gebruik de `save`-methode om het bestand op te slaan in PowerPoint-indeling.

{{% blocks/products/pf/feature-page-code h3="PHP PDF naar PowerPoint conversie" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Converteer PPT naar PDF met aangepaste opties in PHP" %}}

Om PowerPoint-dia's nauwkeurig naar PDF te converteren, kunnen programmeurs het document laden met behulp van de klasse 'Presentation' en de klasse 'PdfOptions' gebruiken voor alle specifieke en aangepaste opties zoals tekstcompressieniveau, JPEG-kwaliteit, het gedrag van metabestanden, het converteren van verborgen dia's en het selecteren specifieke dia's en meer. Er is zelfs een optie om het geconverteerde PDF-bestand met een wachtwoord te beveiligen.
{{% blocks/products/pf/feature-page-code h3="PHP PowerPoint naar PDF-conversie met aangepaste instellingen" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint naar HTML-conversie in PHP" %}}
Wanneer het ooit nodig is om presentaties in webpagina's in te sluiten, dan is het nodig om dia's naar HTML te converteren. 
{{% blocks/products/pf/feature-page-code h3="PHP-code voor conversie van PowerPoint naar HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Converteer PowerPoint naar JPG" %}}
Het converteren van Microsoft<sup>®</sup> PowerPoint-formaten naar afbeeldingen JPEG, PNG, TIFF enz. is een ander veelvoorkomend gebruik dat meestal wordt gebruikt voor het maken van miniaturen van dia's. 
{{% blocks/products/pf/feature-page-code h3="PHP PPT naar JPG-conversiecode" %}}
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