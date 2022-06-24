---
title: Преобразование презентации Microsoft PowerPoint в PDF на PHP
url: /ru/php-java/conversion/
keyslides: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP API для преобразования PPT в PDF. Преобразование презентаций в JPG, PNG и другие форматы на PHP.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование презентации Microsoft<sup>®</sup> PowerPoint в PDF на PHP" h2="Исходные коды PHP для различных случаев преобразования для преобразования PPT в PDF, PNG, HTML, JPEG, PPTX и другие форматы." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides для PHP через Java](https://products.aspose.com/slides/ru/php-java/) — это мощная локальная библиотека классов, используемая для обработки и работы с презентациями. Разработчикам легко и быстро конвертировать PowerPoint в PDF. Получите результаты в кратчайшие сроки для автоматизации бизнес-процессов. Мы обсуждаем здесь несколько случаев чтения или загрузки любых входных данных [поддерживаемые форматы PowerPoint](https://docs.aspose.com/slides/php-java/supported-file-formats/) и записи или сохранения в любом поддерживаемом выходном формате. . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование PowerPoint в PDF на PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/ru/php-java/) позволяет конвертировать файлы в форматах PowerPoint PPT, PPTX и OpenOffice ODP в PDF. Чтобы преобразовать презентацию в PDF, просто передайте имя файла и формат сохранения методу Presentation.save. Класс Presentation предоставляет метод save, который можно вызвать для преобразования всей презентации PPT, PPTX или ODP в документ PDF.

{{% blocks/products/pf/feature-page-code h3="PHP Преобразование PowerPoint в PDF" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Преобразование PDF в PPT в PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/ru/php-java/) позволяет импортировать презентации из PDF-файлов. По сути, вы можете преобразовать PDF в презентацию PowerPoint. Чтобы преобразовать PDF в Powerpoint, выполните следующие действия:
- Создать экземпляр объекта класса «Презентация».
- Вызовите метод `addFromPdf` и передайте файл PDF.
- Используйте метод «сохранить», чтобы сохранить файл в формате PowerPoint.

{{% blocks/products/pf/feature-page-code h3="Преобразование PHP PDF в Powerpoint" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Преобразование PPT в PDF с пользовательскими параметрами в PHP" %}}

Для точного преобразования слайдов PowerPoint в PDF программисты могут загрузить документ с помощью класса «Presentation» и использовать класс «PdfOptions» для всех конкретных и пользовательских параметров, таких как уровень сжатия текста, качество Jpeg, поведение метафайлов, преобразование скрытых слайдов, а также выбор определенные слайды и многое другое. Даже есть возможность защитить преобразованный PDF-файл паролем.
{{% blocks/products/pf/feature-page-code h3="Преобразование PHP PowerPoint в PDF с пользовательскими настройками" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Преобразование Microsoft PowerPoint в HTML в PHP" %}}
Когда когда-нибудь возникает необходимость встроить презентации в веб-страницы, необходимо преобразовать слайды в HTML. 
{{% blocks/products/pf/feature-page-code h3="PHP-код для преобразования PowerPoint в HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Конвертировать PowerPoint в JPG" %}}
Преобразование форматов Microsoft<sup>®</sup> PowerPoint в изображения JPEG, PNG, TIFF и т. д. — еще один распространенный вариант использования, в основном используемый для создания эскизов слайдов. 
{{% blocks/products/pf/feature-page-code h3="Код конвертера PHP PPT в JPG" %}}
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