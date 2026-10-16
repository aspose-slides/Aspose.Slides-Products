---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PHP で PDF を PNG に変換する
url: /ja/php-java/conversion/pdf-to-png/
keywords: PDF から PNG へ、PDF から PNG への変換、PHP API、PHP ライブラリ、PDF、PNG
description: PHP で PDF を PNG に変換します。 PowerPoint PHP API を使用して PDF ファイルを PNG に変換します
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PHP で PDF を PNG に変換する" h2="MicrosoftやOpen Office、Adobe PDFなどのソフトウェアを使用せずに、Microsoft PowerPointおよびOpenOfficeプレゼンテーションファイルを作成、マージ、検査、または変換する機能を備えたアプリケーションの開発に役立つ強力なPowerPoint PHPライブラリ。" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP を使用して PDF を PNG に変換します" variant="code" %}}

PDF を PNG に変換するには、PDF ファイルからプレゼンテーションを作成し、PNG として保存する必要があります。

{{< blocks/products/pf/slides-design-update-10-2026/code title="PDF を PNG に変換するための PHP コード" >}}
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
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".png");
        $imageio->write($bmp, "PNG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP で PDF を PNG に変換する" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/ja/php-java/) は、プレゼンテーション ファイルを作成および操作するための強力な PHP ライブラリです。さらに、PDF を PNG に柔軟に変換する方法を提供します。 **Aspose.Slides for PHP via Java** を使用すると、開発者やアプリケーションはわずか数行の PHP コードで PDF ファイルを PNG ファイルに変換できます。

最新のドキュメント処理 API である Aspose.Slides for PHP は、PDF ファイルを PNG ファイル フォーマットにすばやくエクスポートします。 Aspose PowerPoint ライブラリを使用すると、PDF を PNG やその他の多くのファイル形式に変換できます

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Aspose.Slides for PHP API を使用して PDF を PNG に変換する方法" intro="これらは、PHP で PDF を PNG に変換する手順です。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/ja/php-java/) をインストールします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PHP プロジェクトにライブラリ参照を追加 (ライブラリをインポート) します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ソース PDF ファイルを PHP で開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}結果を PNG ファイルとして保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="無料のオンラインコンバーター"
  description="[Python で PPT を HTML に変換する方法](https://products.aspose.com/slides/ja/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="PDF を他のサポートされている形式に変換する" subTitle="PDF を変換して、他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
