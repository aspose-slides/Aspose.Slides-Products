---
title: PHP で PNG を JPG に変換する
url: /ja/php-java/conversion/png-to-jpg/
keywords: PNG から JPG へ、PNG から JPG への変換、PHP API、PHP ライブラリ、PNG、JPG
description: PHP で PNG を JPG に変換します。 PowerPoint PHP API を使用して PNG ファイルを JPG に変換します
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP で PNG を JPG に変換する" h2="MicrosoftやOpen Office、Adobe PDFなどのソフトウェアを使用せずに、Microsoft PowerPointおよびOpenOfficeプレゼンテーションファイルを作成、マージ、検査、または変換する機能を備えたアプリケーションの開発に役立つ強力なPowerPoint PHPライブラリ。" >}}

{{% blocks/products/pf/feature-page-section h2="PHP で PNG を JPG に変換する" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/ja/php-java/) は、プレゼンテーション ファイルを作成および操作するための強力な PHP ライブラリです。さらに、PNG を JPG に柔軟に変換する方法を提供します。 **Aspose.Slides for PHP via Java** を使用すると、開発者やアプリケーションはわずか数行の PHP コードで PNG ファイルを JPG ファイルに変換できます。

最新のドキュメント処理 API である Aspose.Slides for PHP は、PNG ファイルを JPG ファイル フォーマットにすばやくエクスポートします。 Aspose PowerPoint ライブラリを使用すると、PNG を JPG やその他の多くのファイル形式に変換できます

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PHP を使用して PNG を JPG に変換します" %}}
PNG を JPG に変換するには、PNG ファイルからプレゼンテーションを作成し、JPG として保存する必要があります。

{{% blocks/products/pf/agp/code-block title="PNG を JPG に変換するための PHP コード" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.png';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for PHP API を使用して PNG を JPG に変換する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、PHP で PNG を JPG に変換する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/ja/php-java/) をインストールします。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PHP プロジェクトにライブラリ参照を追加 (ライブラリをインポート) します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ソース PNG ファイルを PHP で開きます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を JPG ファイルとして保存します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PNG を他のサポートされている形式に変換する" subTitle="PNG を変換して、他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/png-to-html/" name="PNG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}