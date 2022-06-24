---
title: 在 PHP 中将 Microsoft PowerPoint 演示文稿转换为 PDF
url: /zh/php-java/conversion/
keywords: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP API 将 PPT 转换为 PDF。在 PHP 中将演示文稿转换为 JPG、PNG 和其他格式。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint 演示文稿到 PHP 中的 PDF 转换" h2="不同转换案例的PHP源代码，可将PPT转换为PDF、PNG、HTML、JPEG、PPTX等格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides for PHP via Java](https://products.aspose.com/slides/zh/php-java/) 是一个强大的本地类库，用于处理和处理演示文稿。开发人员可以轻松快速准确地将 PowerPoint 转换为 PDF。立即获得结果，实现业务流程自动化。我们在这里讨论读取或加载任何输入 [支持的 PowerPoint 格式](https://docs.aspose.com/slides/php-java/supported-file-formats/) 并写入或保存为任何支持的输出格式的几种情况. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PHP中的PowerPoint到PDF转换" %}}
[Aspose.Slides](https://products.aspose.com/slides/zh/php-java/) 允许您将 PowerPoint PPT、PPTX 和 OpenOffice ODP 格式的文件转换为 PDF。要将演示文稿转换为 PDF，只需将文件名和保存格式传递给 `Presentation.save` 方法。 `Presentation` 类公开了 `save` 方法，可以调用该方法将整个 PPT、PPTX 或 ODP 演示文稿转换为 PDF 文档。

{{% blocks/products/pf/feature-page-code h3="PHP PowerPoint 到 PDF 转换" %}}

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

{{% blocks/products/pf/feature-page-section  h2="PHP中的PDF到PPT转换" %}}
[Aspose.Slides](https://products.aspose.com/slides/zh/php-java/) 允许您从 PDF 导入演示文稿。本质上，您可以将 PDF 转换为 PowerPoint 演示文稿。要将 PDF 转换为 Powerpoint，请执行以下步骤：
- 实例化 `Presentation` 类的对象。
- 调用 `addFromPdf` 方法并传递 PDF 文件。
- 使用 `save` 方法以 PowerPoint 格式保存文件。

{{% blocks/products/pf/feature-page-code h3="PHP PDF 到 Powerpoint 转换" %}}

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


{{% blocks/products/pf/feature-page-section  h2="使用 PHP 中的自定义选项将 PPT 转换为 PDF" %}}

为了将 PowerPoint 幻灯片准确地转换为 PDF，程序员可以使用 `Presentation` 类加载文档，并使用 `PdfOptions` 类进行所有特定和自定义选项，例如文本压缩级别、Jpeg 质量、元文件的行为、转换隐藏幻灯片以及选择特定的幻灯片等等。甚至可以选择使用密码保护转换后的 PDF 文件。
{{% blocks/products/pf/feature-page-code h3="带有自定义设置的 PHP PowerPoint 到 PDF 转换" %}}

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


{{% blocks/products/pf/feature-page-section  h2="PHP 中的 Microsoft PowerPoint 到 HTML 转换" %}}
当需要在网页中嵌入演示文稿时，就需要将幻灯片转换为 HTML。 
{{% blocks/products/pf/feature-page-code h3="用于 PowerPoint 到 HTML 转换的 PHP 代码" %}}

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

{{% blocks/products/pf/feature-page-section  h2="将 PowerPoint 转换为 JPG" %}}
将 Microsoft<sup>®</sup> PowerPoint 格式转换为图像 JPEG、PNG、TIFF 等是另一个常见的用例，主要用于创建幻灯片缩略图。 
{{% blocks/products/pf/feature-page-code h3="PHP PPT to JPG 转换器代码" %}}
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