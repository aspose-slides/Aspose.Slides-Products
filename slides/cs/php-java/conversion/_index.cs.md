---
title: Konverze prezentace Microsoft PowerPoint do PDF v PHP
url: /cs/php-java/conversion/
keyslides: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP API pro převod PPT do PDF. Převeďte prezentace do JPG, PNG a dalších formátů v PHP.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Prezentace Microsoft<sup>®</sup> PowerPoint Konverze do PDF v PHP" h2="Zdrojové kódy PHP pro různé případy převodu pro převod PPT do PDF, PNG, HTML, JPEG, PPTX a dalších formátů." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides pro PHP přes Javu](https://products.aspose.com/slides/cs/php-java/) je výkonná místní knihovna tříd používaná pro zpracování a práci s prezentacemi. Pro vývojáře je snadné rychle a přesně převést PowerPoint do PDF. Získejte výsledky během okamžiku pro automatizaci obchodních procesů. Diskutujeme zde o několika případech čtení nebo načítání jakéhokoli vstupu [podporované formáty PowerPoint](https://docs.aspose.com/slides/php-java/supported-file-formats/) a zápisu nebo uložení do libovolného podporovaného výstupního formátu . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Převod PowerPoint do PDF v PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/cs/php-java/) umožňuje převádět soubory ve formátech PowerPoint PPT, PPTX a OpenOffice ODP do PDF. Chcete-li převést prezentaci do PDF, jednoduše předejte název souboru a formát uložení do metody `Presentation.save`. Třída `Presentation` odhaluje metodu `save`, kterou lze zavolat pro převod celé prezentace PPT, PPTX nebo ODP do dokumentu PDF.

{{% blocks/products/pf/feature-page-code h3="Konverze PHP PowerPoint do PDF" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Převod PDF na PPT v PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/cs/php-java/) umožňuje importovat prezentace z PDF. V podstatě můžete převést PDF na prezentaci v PowerPointu. Chcete-li převést PDF do Powerpointu, postupujte takto:
- Vytvořte instanci objektu třídy `Presentation`.
- Zavolejte metodu `addFromPdf` a předejte soubor PDF.
- Pomocí metody `save` uložte soubor ve formátu PowerPoint.

{{% blocks/products/pf/feature-page-code h3="Konverze PHP PDF do Powerpointu" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Převeďte PPT do PDF s vlastními možnostmi v PHP" %}}

Pro přesný převod PowerPoint snímků do PDF mohou programátoři načíst dokument pomocí třídy „Presentation“ a použít třídu „PdfOptions“ pro všechny specifické a vlastní možnosti, jako je úroveň komprese textu, kvalita Jpeg, chování metasouborů, převod skrytých snímků a také výběr. konkrétní snímky a další. Dokonce existuje možnost chránit převedený soubor PDF heslem.
{{% blocks/products/pf/feature-page-code h3="Konverze PHP PowerPoint do PDF s vlastním nastavením" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Převod Microsoft PowerPoint do HTML v PHP" %}}
Kdykoli je potřeba vložit prezentace na webové stránky, pak je potřeba převést snímky do HTML. 
{{% blocks/products/pf/feature-page-code h3="PHP kód pro převod PowerPoint do HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Převést PowerPoint do JPG" %}}
Převod formátů Microsoft<sup>®</sup> PowerPoint na obrázky JPEG, PNG, TIFF atd. je dalším běžným případem použití, který se většinou používá pro vytváření miniatur snímků. 
{{% blocks/products/pf/feature-page-code h3="Kód převodu PHP PPT na JPG" %}}
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