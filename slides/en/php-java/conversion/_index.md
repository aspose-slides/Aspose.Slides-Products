---
title: Microsoft PowerPoint Presentation Conversion to PDF in PHP 
url: /php-java/conversion/
keywords: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP API to Convert PPT to PDF. Convert Presentations to JPG, PNG and other formats in PHP. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> PowerPoint Presentation to PDF Conversion in PHP" h2="PHP Source Codes for different conversion cases to convert PPT to PDF, PNG, HTML, JPEG, PPTX and other formats." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides for PHP via Java](https://products.aspose.com/slides/php-java/) is a powerful on-premises class library used for processing and working with presentations. It is easy for the developers to convert PowerPoint to PDF with speed and accuracy. Get the results within no time for automating the business processes. We are discussing here few cases to read or load any input [supported PowerPoint formats](https://docs.aspose.com/slides/php-java/supported-file-formats/) and write or save to any supported output format. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint to PDF Conversion in PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/php-java/) allows you to convert files in PowerPoint PPT, PPTX, and OpenOffice ODP formats to PDF. To convert a presentation to PDF, simply pass the file name and save format to the `Presentation.save` method. The `Presentation` class exposes the `save` method that can be called to convert the whole PPT, PPTX, or ODP presentation into a PDF document.

{{% blocks/products/pf/feature-page-code h3="PHP PowerPoint to PDF Conversion" %}}

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

{{% blocks/products/pf/feature-page-section  h2="PDF to PPT Conversion in PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/php-java/) allows you to import presentations from PDFs. Essentially, you get to convert a PDF to a PowerPoint presentation. To convert PDF to Powerpoint, Go through these steps:
- Instantiate an object of the [`Presentation`](https://docs.aspose.com/slides/php-java/api-reference/aspose.slides/presentation/) class.
- Call the [`add_from_pdf`](https://docs.aspose.com/slides/php-java/api-reference/aspose.slides/slidecollection/) method and pass the PDF file.
- Use the `save` method to save the file in the PowerPoint format.

{{% blocks/products/pf/feature-page-code h3="PHP PDF to Powerpoint Conversion" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Convert PPT to PDF with custom options in PHP" %}}

For converting PowerPoint slides to PDF accurately, Programmers can load the document using `Presentation` class and use `PdfOptions` class for all specific and custom options like text compression level, Jpeg quality, the behavior of metafiles, converting hidden slides as well as selecting specific slides and more. Even there is option to protect the converted PDF file with password.
{{% blocks/products/pf/feature-page-code h3="PHP PowerPoint to PDF Conversion with custom settings" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Mircrosoft PowerPoint to HTML Conversion in PHP" %}}
When ever there is need to embed presentations within webpages, then there is need to convert slides to HTML. 
{{% blocks/products/pf/feature-page-code h3="PHP Code for PowerPoint to HTML Conversion" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Convert PowerPoint to JPG" %}}
Converting Microsoft<sup>&reg;</sup> PowerPoint formats to images JPEG, PNG, TIFF etc is another commom use case mostly used for creating slides thumbnails. 
{{% blocks/products/pf/feature-page-code h3="PHP PPT to JPG Converter Code" %}}
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

{{< blocks/slides-app-widget 
    appName="conversion"
    extension=""
    sectionTitle="Convert PowerPoint Presentations online" 
    sectionDescription="[Learn how to convert ppt to pdf in PHP](https://products.aspose.com/slides/php-java/conversion/ppt-to-pdf/)" >}}

{{< /blocks/products/pf/feature-page-wrap >}}