---
title: Conversion de présentation Microsoft PowerPoint en PDF en PHP
url: /fr/php-java/conversion/
keywords: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: API PHP pour convertir PPT en PDF. Convertissez des présentations en JPG, PNG et autres formats en PHP.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversion de présentation Microsoft<sup>®</sup> PowerPoint en PDF en PHP" h2="Codes sources PHP pour différents cas de conversion pour convertir PPT en PDF, PNG, HTML, JPEG, PPTX et autres formats." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides pour PHP via Java](https://products.aspose.com/slides/fr/php-java/) est une puissante bibliothèque de classes sur site utilisée pour traiter et travailler avec des présentations. Il est facile pour les développeurs de convertir PowerPoint en PDF avec rapidité et précision. Obtenez les résultats en un rien de temps pour automatiser les processus métier. Nous discutons ici de quelques cas pour lire ou charger n'importe quelle entrée [formats PowerPoint pris en charge](https://docs.aspose.com/slides/php-java/supported-file-formats/) et écrire ou enregistrer dans n'importe quel format de sortie pris en charge . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Conversion PowerPoint en PDF en PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/fr/php-java/) vous permet de convertir des fichiers aux formats PowerPoint PPT, PPTX et OpenOffice ODP en PDF. Pour convertir une présentation au format PDF, transmettez simplement le nom du fichier et le format d'enregistrement à la méthode `Presentation.save`. La classe `Presentation` expose la méthode `save` qui peut être appelée pour convertir l'ensemble de la présentation PPT, PPTX ou ODP en un document PDF.

{{% blocks/products/pf/feature-page-code h3="Conversion PHP PowerPoint en PDF" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Conversion PDF en PPT en PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/fr/php-java/) vous permet d'importer des présentations à partir de PDF. Essentiellement, vous pouvez convertir un PDF en une présentation PowerPoint. Pour convertir un PDF en Powerpoint, suivez ces étapes :
- Instancier un objet de la classe `Presentation`.
- Appelez la méthode `addFromPdf` et transmettez le fichier PDF.
- Utilisez la méthode `save` pour enregistrer le fichier au format PowerPoint.

{{% blocks/products/pf/feature-page-code h3="Conversion PHP PDF en PowerPoint" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Convertir PPT en PDF avec des options personnalisées en PHP" %}}

Pour convertir avec précision les diapositives PowerPoint en PDF, les programmeurs peuvent charger le document à l'aide de la classe "Présentation" et utiliser la classe "PdfOptions" pour toutes les options spécifiques et personnalisées telles que le niveau de compression du texte, la qualité Jpeg, le comportement des métafichiers, la conversion des diapositives masquées ainsi que la sélection diapositives spécifiques et plus encore. Même il existe une option pour protéger le fichier PDF converti avec un mot de passe.
{{% blocks/products/pf/feature-page-code h3="Conversion PHP PowerPoint en PDF avec des paramètres personnalisés" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Conversion de Microsoft PowerPoint en HTML en PHP" %}}
Chaque fois qu'il est nécessaire d'intégrer des présentations dans des pages Web, il est nécessaire de convertir les diapositives en HTML. 
{{% blocks/products/pf/feature-page-code h3="Code PHP pour la conversion de PowerPoint en HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Convertir PowerPoint en JPG" %}}
La conversion des formats Microsoft<sup>®</sup> PowerPoint en images JPEG, PNG, TIFF, etc. est un autre cas d'utilisation courant principalement utilisé pour créer des miniatures de diapositives. 
{{% blocks/products/pf/feature-page-code h3="Code de conversion PHP PPT en JPG" %}}
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