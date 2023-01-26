---
title: PHP で JPG を PPTX に変換する
url: /ja/php-java/conversion/jpg-to-pptx/
keywords: JPG から PPTX へ、JPG から PPTX への変換、PHP API、PHP ライブラリ、JPG、PPTX
description: PHP で JPG を PPTX に変換します。 PowerPoint PHP API を使用して JPG ファイルを PPTX に変換します
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP で JPG を PPTX に変換する" h2="MicrosoftやOpen Office、Adobe PDFなどのソフトウェアを使用せずに、Microsoft PowerPointおよびOpenOfficeプレゼンテーションファイルを作成、マージ、検査、または変換する機能を備えたアプリケーションの開発に役立つ強力なPowerPoint PHPライブラリ。" >}}

{{% blocks/products/pf/feature-page-section h2="PHP で JPG を PPTX に変換する" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/ja/php-java/) は、プレゼンテーション ファイルを作成および操作するための強力な PHP ライブラリです。さらに、JPG を PPTX に柔軟に変換する方法を提供します。 **Aspose.Slides for PHP via Java** を使用すると、開発者やアプリケーションはわずか数行の PHP コードで JPG ファイルを PPTX ファイルに変換できます。

最新のドキュメント処理 API である Aspose.Slides for PHP は、JPG ファイルを PPTX ファイル フォーマットにすばやくエクスポートします。 Aspose PowerPoint ライブラリを使用すると、JPG を PPTX やその他の多くのファイル形式に変換できます

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PHP を使用して JPG を PPTX に変換します" %}}
JPG を PPTX に変換するには、JPG ファイルからプレゼンテーションを作成し、PPTX として保存する必要があります。

{{% blocks/products/pf/agp/code-block title="JPG を PPTX に変換するための PHP コード" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.jpg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.pptx", SaveFormat::Pptx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for PHP API を使用して JPG を PPTX に変換する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、PHP で JPG を PPTX に変換する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/ja/php-java/) をインストールします。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PHP プロジェクトにライブラリ参照を追加 (ライブラリをインポート) します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ソース JPG ファイルを PHP で開きます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を PPTX ファイルとして保存します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="JPG を他のサポートされている形式に変換する" subTitle="JPG を変換して、他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/jpg-to-html/" name="JPG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}