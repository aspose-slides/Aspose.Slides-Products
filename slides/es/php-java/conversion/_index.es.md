---
title: Conversión de presentaciones de Microsoft PowerPoint a PDF en PHP
url: /es/php-java/conversion/
keyslides: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: API de PHP para convertir PPT a PDF. Convierte presentaciones a JPG, PNG y otros formatos en PHP.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversión de presentación de Microsoft<sup>®</sup> PowerPoint a PDF en PHP" h2="Códigos fuente de PHP para diferentes casos de conversión para convertir PPT a PDF, PNG, HTML, JPEG, PPTX y otros formatos." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides for PHP via Java](https://products.aspose.com/slides/es/php-java/) es una potente biblioteca de clases local que se utiliza para procesar y trabajar con presentaciones. Es fácil para los desarrolladores convertir PowerPoint a PDF con rapidez y precisión. Obtenga los resultados en poco tiempo para automatizar los procesos comerciales. Estamos discutiendo aquí algunos casos para leer o cargar cualquier entrada [formatos de PowerPoint compatibles](https://docs.aspose.com/slides/php-java/supported-file-formats/) y escribir o guardar en cualquier formato de salida compatible. . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Conversión de PowerPoint a PDF en PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/es/php-java/) le permite convertir archivos en formato PowerPoint PPT, PPTX y OpenOffice ODP a PDF. Para convertir una presentación a PDF, simplemente pase el nombre del archivo y guarde el formato al método `Presentation.save`. La clase "Presentación" expone el método "guardar" que se puede llamar para convertir toda la presentación PPT, PPTX u ODP en un documento PDF.

{{% blocks/products/pf/feature-page-code h3="Conversión de PHP PowerPoint a PDF" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Conversión de PDF a PPT en PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/es/php-java/) le permite importar presentaciones desde archivos PDF. Esencialmente, puedes convertir un PDF a una presentación de PowerPoint. Para convertir PDF a Powerpoint, sigue estos pasos:
- Instanciar un objeto de la clase `Presentación`.
- Llame al método `addFromPdf` y pase el archivo PDF.
- Use el método `save` para guardar el archivo en formato PowerPoint.

{{% blocks/products/pf/feature-page-code h3="Conversión de PHP PDF a Powerpoint" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Convierta PPT a PDF con opciones personalizadas en PHP" %}}

Para convertir diapositivas de PowerPoint a PDF con precisión, los programadores pueden cargar el documento usando la clase "Presentación" y usar la clase "PdfOptions" para todas las opciones específicas y personalizadas, como el nivel de compresión de texto, la calidad Jpeg, el comportamiento de los metarchivos, la conversión de diapositivas ocultas y la selección. diapositivas específicas y más. Incluso hay una opción para proteger el archivo PDF convertido con contraseña.
{{% blocks/products/pf/feature-page-code h3="Conversión de PHP PowerPoint a PDF con configuraciones personalizadas" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Conversión de Microsoft PowerPoint a HTML en PHP" %}}
Siempre que sea necesario incrustar presentaciones en páginas web, será necesario convertir las diapositivas a HTML. 
{{% blocks/products/pf/feature-page-code h3="Código PHP para la conversión de PowerPoint a HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Convertir PowerPoint a JPG" %}}
La conversión de formatos de Microsoft<sup>®</sup> PowerPoint a imágenes JPEG, PNG, TIFF, etc. es otro caso de uso común que se utiliza principalmente para crear miniaturas de diapositivas. 
{{% blocks/products/pf/feature-page-code h3="Código convertidor de PHP PPT a JPG" %}}
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