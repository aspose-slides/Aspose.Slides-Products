---
title: PHP を使用して PDF、PPT、PPTX およびその他の多くのファイル形式をマージする
url: /ja/php-java/merger/
keywords: マージ、結合、PowerPoint、プレゼンテーション、PHP、Aspose
description: PHP PPT、PPTX、ODP、PDF、PNG、JPG などの複数のファイルをマージします。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Powerpoint、PDF、PPT、またはその他のドキュメントを PHP でマージする" h2="PPT、PPTX、PDF、PNG、JPEG、およびその他の形式をマージするための高速 PHP ライブラリ。" >}}

{{% blocks/products/pf/feature-page-section h2="PHP を使用して PPT、PPTX、PDF をマージする" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/ja/php-java/) は、プレゼンテーション ファイルを作成および操作するための強力な PHP ライブラリです。さらに、複数の PPT/PPTX プレゼンテーションを柔軟に組み合わせることができます。あるプレゼンテーションを別のプレゼンテーションにマージすると、それらのスライドを効果的に 1 つのプレゼンテーションに結合して 1 つのファイルを取得します。 Aspose.Slides では、2 つのプレゼンテーションを異なる方法でマージできます。品質やデータの損失を心配することなく、プレゼンテーションをすべての形状、スタイル、テキスト、書式、コメント、アニメーションなどと結合できます。

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PHP で PowerPoint プレゼンテーションをマージする" %}}
PowerPoint プレゼンテーションを結合するには、あるプレゼンテーションから別のプレゼンテーションにスライドを複製する必要があります。

{{% blocks/products/pf/agp/code-block title="PHP を使用して PPTX ファイルをマージする" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres1 = new Presentation("document1.ppt");
$pres2 = new Presentation("document2.ppt");
try
{
    for ($i = 0; $i < java_values($pres2->getSlides()->size()); $i++) 
    {
        $pres1->getSlides()->addClone($pres2->getSlides()->get_Item($i));
    }

    $pres1->save("merged.ppt", SaveFormat::Ppt);
}
finally
{
    if ($pres1 != null) $pres1->dispose();
    if ($pres2 != null) $pres2->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for PHP API を使用してプレゼンテーションをマージする方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、2 つの PPTX ファイルをマージし、結果を PHP で PDF として保存する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for PHP via Java**](https://docs.aspose.com/slides/php-java/installation/) をインストールします。 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PHP プロジェクトにライブラリ参照を追加 (ライブラリをインポート) します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ソース PPTX ファイルを PHP で開きます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
**addClone** メソッドを使用して PPTX ファイルを結合します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションを保存し、結果を単一の PDF ファイルとして取得します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="マージするその他のサポートされている形式" subTitle="他のファイル形式を組み合わせることもできます。以下のサポートされているその他の形式を参照してください。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/merger/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/merger/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/merger/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/merger/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/merger/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/merger/potm/" name="POTM" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/merger/potx/" name="POTX" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/merger/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/merger/ppsm/" name="PPSM" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/merger/ppsx/" name="PPSX" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/merger/pptm/" name="PPTM" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/merger/fodp/" name="FODP" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/merger/pdf-to-pdf/" name="PDF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}