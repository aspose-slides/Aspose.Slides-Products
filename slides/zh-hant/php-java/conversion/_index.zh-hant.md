---
title: 在 PHP 中將 Microsoft PowerPoint 演示文稿轉換為 PDF
url: /zh-hant/php-java/conversion/
keyslides: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP API 將 PPT 轉換為 PDF。在 PHP 中將演示文稿轉換為 JPG、PNG 和其他格式。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint 演示文稿到 PHP 中的 PDF 轉換" h2="不同轉換案例的PHP源代碼，可將PPT轉換為PDF、PNG、HTML、JPEG、PPTX等格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides for PHP via Java](https://products.aspose.com/slides/zh-hant/php-java/) 是一個強大的本地類庫，用於處理和處理演示文稿。開發人員可以輕鬆快速準確地將 PowerPoint 轉換為 PDF。立即獲得結果，實現業務流程自動化。我們在這裡討論讀取或加載任何輸入 [支持的 PowerPoint 格式](https://docs.aspose.com/slides/php-java/supported-file-formats/) 並寫入或保存為任何支持的輸出格式的幾種情況. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PHP中的PowerPoint到PDF轉換" %}}
[Aspose.Slides](https://products.aspose.com/slides/zh-hant/php-java/) 允許您將 PowerPoint PPT、PPTX 和 OpenOffice ODP 格式的文件轉換為 PDF。要將演示文稿轉換為 PDF，只需將文件名和保存格式傳遞給 `Presentation.save` 方法。 `Presentation` 類公開了 `save` 方法，可以調用該方法將整個 PPT、PPTX 或 ODP 演示文稿轉換為 PDF 文檔。

{{% blocks/products/pf/feature-page-code h3="PHP PowerPoint 到 PDF 轉換" %}}

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

{{% blocks/products/pf/feature-page-section  h2="PHP中的PDF到PPT轉換" %}}
[Aspose.Slides](https://products.aspose.com/slides/zh-hant/php-java/) 允許您從 PDF 導入演示文稿。本質上，您可以將 PDF 轉換為 PowerPoint 演示文稿。要將 PDF 轉換為 Powerpoint，請執行以下步驟：
- 實例化 `Presentation` 類的對象。
- 調用 `addFromPdf` 方法並傳遞 PDF 文件。
- 使用 `save` 方法以 PowerPoint 格式保存文件。

{{% blocks/products/pf/feature-page-code h3="PHP PDF 到 Powerpoint 轉換" %}}

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


{{% blocks/products/pf/feature-page-section  h2="使用 PHP 中的自定義選項將 PPT 轉換為 PDF" %}}

為了將 PowerPoint 幻燈片準確地轉換為 PDF，程序員可以使用 `Presentation` 類加載文檔，並使用 `PdfOptions` 類進行所有特定和自定義選項，例如文本壓縮級別、Jpeg 質量、元文件的行為、轉換隱藏幻燈片以及選擇特定的幻燈片等等。甚至可以選擇使用密碼保護轉換後的 PDF 文件。
{{% blocks/products/pf/feature-page-code h3="帶有自定義設置的 PHP PowerPoint 到 PDF 轉換" %}}

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


{{% blocks/products/pf/feature-page-section  h2="PHP 中的 Microsoft PowerPoint 到 HTML 轉換" %}}
當需要在網頁中嵌入演示文稿時，就需要將幻燈片轉換為 HTML。 
{{% blocks/products/pf/feature-page-code h3="用於 PowerPoint 到 HTML 轉換的 PHP 代碼" %}}

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

{{% blocks/products/pf/feature-page-section  h2="將 PowerPoint 轉換為 JPG" %}}
將 Microsoft<sup>®</sup> PowerPoint 格式轉換為圖像 JPEG、PNG、TIFF 等是另一個常見的用例，主要用於創建幻燈片縮略圖。 
{{% blocks/products/pf/feature-page-code h3="PHP PPT to JPG 轉換器代碼" %}}
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