---
title: Konwersja prezentacji programu Microsoft PowerPoint do formatu PDF w PHP
url: /pl/php-java/conversion/
keywords: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP API do konwersji PPT na PDF. Konwertuj prezentacje do JPG, PNG i innych formatów w PHP.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Prezentacja Microsoft<sup>®</sup> PowerPoint do konwersji PDF w PHP" h2="Kody źródłowe PHP dla różnych przypadków konwersji do konwersji PPT na PDF, PNG, HTML, JPEG, PPTX i inne formaty." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides dla PHP przez Javę](https://products.aspose.com/slides/pl/php-java/) to potężna lokalna biblioteka klas używana do przetwarzania i pracy z prezentacjami. Deweloperzy mogą łatwo i szybko przekonwertować PowerPoint na PDF. Uzyskaj wyniki w krótkim czasie, aby zautomatyzować procesy biznesowe. Omawiamy tutaj kilka przypadków, w których można odczytać lub załadować dowolne dane wejściowe [obsługiwane formaty PowerPoint](https://docs.aspose.com/slides/php-java/supported-file-formats/) oraz zapisać lub zapisać w dowolnym obsługiwanym formacie wyjściowym . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konwersja PowerPoint do PDF w PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/pl/php-java/) umożliwia konwersję plików w formatach PowerPoint PPT, PPTX i OpenOffice ODP do formatu PDF. Aby przekonwertować prezentację do formatu PDF, po prostu przekaż nazwę pliku i zapisz format do metody `Presentation.save`. Klasa `Presentation` udostępnia metodę `save`, którą można wywołać w celu przekonwertowania całej prezentacji PPT, PPTX lub ODP na dokument PDF.

{{% blocks/products/pf/feature-page-code h3="Konwersja PHP PowerPoint do PDF" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Konwersja PDF do PPT w PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/pl/php-java/) umożliwia importowanie prezentacji z plików PDF. Zasadniczo możesz przekonwertować plik PDF na prezentację PowerPoint. Aby przekonwertować plik PDF do programu PowerPoint, wykonaj następujące kroki:
- Utwórz wystąpienie obiektu klasy `Prezentacja`.
- Wywołaj metodę `addFromPdf` i przekaż plik PDF.
- Użyj metody „zapisz”, aby zapisać plik w formacie PowerPoint.

{{% blocks/products/pf/feature-page-code h3="Konwersja PHP z PDF do PowerPoint" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Konwertuj PPT na PDF z niestandardowymi opcjami w PHP" %}}

Aby dokładnie przekonwertować slajdy PowerPointa na PDF, programiści mogą załadować dokument za pomocą klasy `Presentation` i użyć klasy `PdfOptions` dla wszystkich specyficznych i niestandardowych opcji, takich jak poziom kompresji tekstu, jakość JPEG, zachowanie metaplików, konwertowanie ukrytych slajdów, a także zaznaczanie konkretne slajdy i nie tylko. Nawet istnieje możliwość ochrony przekonwertowanego pliku PDF hasłem.
{{% blocks/products/pf/feature-page-code h3="Konwersja PHP PowerPoint do PDF z ustawieniami niestandardowymi" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Konwersja Microsoft PowerPoint do HTML w PHP" %}}
Zawsze, gdy zachodzi potrzeba osadzania prezentacji na stronach internetowych, konieczne jest przekonwertowanie slajdów do formatu HTML. 
{{% blocks/products/pf/feature-page-code h3="Kod PHP do konwersji programu PowerPoint do HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Konwertuj PowerPoint na JPG" %}}
Konwertowanie formatów Microsoft<sup>®</sup> PowerPoint na obrazy JPEG, PNG, TIFF itp. to kolejny typowy przypadek użycia najczęściej używany do tworzenia miniatur slajdów. 
{{% blocks/products/pf/feature-page-code h3="Kod konwertera PHP PPT na JPG" %}}
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