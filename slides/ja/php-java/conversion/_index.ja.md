---
title: PHPでのMicrosoftPowerPointプレゼンテーションのPDFへの変換
url: /ja/php-java/conversion/
keywords: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PPTをPDFに変換するPHPAPI。 PHPでプレゼンテーションをJPG、PNG、その他の形式に変換します。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup>PHPでのPowerPointプレゼンテーションからPDFへの変換" h2="PPTをPDF、PNG、HTML、JPEG、PPTXおよびその他の形式に変換するためのさまざまな変換ケースのPHPソースコード。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides for PHP via Java]（https://products.aspose.com/slides/ja/php-java/）は、プレゼンテーションの処理と操作に使用される強力なオンプレミスクラスライブラリです。開発者は、PowerPointをPDFに高速かつ正確に変換するのは簡単です。ビジネスプロセスを自動化するために、すぐに結果を取得します。ここでは、入力[サポートされているPowerPoint形式]（https://docs.aspose.com/slides/php-java/supported-file-formats/）を読み取ったり読み込んだり、サポートされている出力形式に書き込んだり保存したりするいくつかのケースについて説明します。 。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PHPでのPowerPointからPDFへの変換" %}}
[Aspose.Slides]（https://products.aspose.com/slides/ja/php-java/）を使用すると、PowerPoint PPT、PPTX、およびOpenOfficeODP形式のファイルをPDFに変換できます。プレゼンテーションをPDFに変換するには、ファイル名と保存形式を`Presentation.save`メソッドに渡すだけです。 `Presentation`クラスは、PPT、PPTX、またはODPプレゼンテーション全体をPDFドキュメントに変換するために呼び出すことができる`save`メソッドを公開します。

{{% blocks/products/pf/feature-page-code h3="PHPPowerPointからPDFへの変換" %}}

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

{{% blocks/products/pf/feature-page-section  h2="PHPでのPDFからPPTへの変換" %}}
[Aspose.Slides]（https://products.aspose.com/slides/ja/php-java/）を使用すると、PDFからプレゼンテーションをインポートできます。基本的に、PDFをPowerPointプレゼンテーションに変換することができます。 PDFをPowerpointに変換するには、次の手順を実行します。
-`Presentation`クラスのオブジェクトをインスタンス化します。
-`addFromPdf`メソッドを呼び出し、PDFファイルを渡します。
-`save`メソッドを使用して、ファイルをPowerPoint形式で保存します。

{{% blocks/products/pf/feature-page-code h3="PHPPDFからパワーポイントへの変換" %}}

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


{{% blocks/products/pf/feature-page-section  h2="PHPのカスタムオプションを使用してPPTをPDFに変換する" %}}

PowerPointスライドをPDFに正確に変換するために、プログラマーは `Presentation`クラスを使用してドキュメントをロードし、テキスト圧縮レベル、Jpeg品質、メタファイルの動作、非表示のスライドの変換、選択など、すべての特定のカスタムオプションに`PdfOptions`クラスを使用できます。特定のスライドなど。変換されたPDFファイルをパスワードで保護するオプションもあります。
{{% blocks/products/pf/feature-page-code h3="カスタム設定によるPHPPowerPointからPDFへの変換" %}}

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


{{% blocks/products/pf/feature-page-section  h2="PHPでのMicrosoftPowerPointからHTMLへの変換" %}}
Webページ内にプレゼンテーションを埋め込む必要がある場合は常に、スライドをHTMLに変換する必要があります。 
{{% blocks/products/pf/feature-page-code h3="PowerPointからHTMLへの変換用のPHPコード" %}}

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

{{% blocks/products/pf/feature-page-section  h2="PowerPointをJPGに変換する" %}}
Microsoft<sup>®</sup>PowerPoint形式を画像JPEG、PNG、TIFFなどに変換することは、スライドのサムネイルを作成するために主に使用されるもう1つの一般的な使用例です。 
{{% blocks/products/pf/feature-page-code h3="PHPPPTからJPGへのコンバーターコード" %}}
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