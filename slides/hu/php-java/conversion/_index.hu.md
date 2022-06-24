---
title: Microsoft PowerPoint prezentáció konvertálása PDF-be PHP-ben
url: /hu/php-java/conversion/
keyslides: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP API a PPT PDF-be konvertálásához. Konvertálja a prezentációkat JPG, PNG és más formátumokba PHP-ben.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint prezentáció PDF formátumú konvertálása PHP-ben" h2="PHP forráskódok különböző konverziós esetekhez a PPT PDF, PNG, HTML, JPEG, PPTX és más formátumokká konvertálásához." >}}

{{% blocks/products/pf/feature-page-summary %}}

Az [Aspose.Slides for PHP Java-n keresztül](https://products.aspose.com/slides/hu/php-java/) egy hatékony helyszíni osztálykönyvtár, amelyet prezentációk feldolgozására és kezelésére használnak. A fejlesztők könnyen konvertálhatják a PowerPoint-ot PDF-be gyorsan és pontosan. Gyorsan elérheti az eredményeket az üzleti folyamatok automatizálásával. Itt néhány olyan esetet tárgyalunk, amikor be kell olvasni vagy betölteni a bemeneti [támogatott PowerPoint-formátumokat](https://docs.aspose.com/slides/php-java/supported-file-formats/), és bármilyen támogatott kimeneti formátumba írni vagy menteni. . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint konvertálása PDF-be PHP-ben" %}}
Az [Aspose.Slides](https://products.aspose.com/slides/hu/php-java/) lehetővé teszi a PowerPoint PPT, PPTX és OpenOffice ODP formátumú fájlok PDF formátumba konvertálását. Egy prezentáció PDF formátumba konvertálásához egyszerűen adja át a fájl nevét és a mentési formátumot a "Presentation.save" metódusnak. A "Presentation" osztály felfedi a "mentés" metódust, amely meghívható a teljes PPT, PPTX vagy ODP prezentáció PDF dokumentummá konvertálásához.

{{% blocks/products/pf/feature-page-code h3="PHP PowerPoint konvertálása PDF-be" %}}

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

{{% blocks/products/pf/feature-page-section  h2="PDF konvertálása PPT-be PHP-ben" %}}
Az [Aspose.Slides](https://products.aspose.com/slides/hu/php-java/) lehetővé teszi prezentációk importálását PDF-fájlokból. Lényegében a PDF-fájlt PowerPoint bemutatóvá alakíthatja. A PDF-fájl Powerpoint formátumba konvertálásához kövesse az alábbi lépéseket:
- Példányosítson egy objektumot a "Prezentáció" osztályból.
- Hívja meg az "addFromPdf" metódust, és adja át a PDF-fájlt.
- Használja a "mentés" módszert a fájl PowerPoint formátumba mentéséhez.

{{% blocks/products/pf/feature-page-code h3="PHP PDF konvertálása Powerpointba" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Konvertálja a PPT-t PDF-be a PHP egyéni beállításaival" %}}

A PowerPoint diák PDF formátumba való pontos konvertálásához a programozók betölthetik a dokumentumot a "Presentation" osztály segítségével, és használhatják a "PdfOptions" osztályt az összes speciális és egyéni beállításhoz, mint például a szövegtömörítési szint, a Jpeg minőség, a metafájlok viselkedése, a rejtett diák konvertálása és a kijelölés. konkrét diák és így tovább. Még arra is van lehetőség, hogy a konvertált PDF fájlt jelszóval védje.
{{% blocks/products/pf/feature-page-code h3="PHP PowerPoint konvertálás PDF-be egyéni beállításokkal" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint konvertálása HTML-be PHP-ben" %}}
Amikor valamikor prezentációkat kell beágyazni a weboldalakba, akkor a diákat HTML formátumba kell konvertálni. 
{{% blocks/products/pf/feature-page-code h3="PHP kód a PowerPoint HTML konvertálásához" %}}

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

{{% blocks/products/pf/feature-page-section  h2="A PowerPoint konvertálása JPG formátumba" %}}
A Microsoft<sup>®</sup> PowerPoint formátumok JPEG, PNG, TIFF stb. formátumú képekké konvertálása egy másik gyakori felhasználási eset, amelyet többnyire diabélyegképek létrehozására használnak. 
{{% blocks/products/pf/feature-page-code h3="PHP PPT JPG konvertáló kód" %}}
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