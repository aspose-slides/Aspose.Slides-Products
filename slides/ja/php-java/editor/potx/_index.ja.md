---
title: PHP で POTX を編集
url: /ja/php-java/editor/potx/
keywords: POTX の編集、PowerPoint の編集、POTX、PowerPoint、PHP API、PHP ライブラリ
description: PHP で POTX を編集します。 PHP ライブラリ API を使用して POTX ファイルを編集する
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP で POTX を編集" h2="PHP コードを使用して POTX を編集するための高速でクロスプラットフォームの PHP ライブラリ" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides を使用して POTX を編集" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/ja/php-java/) は、プレゼンテーションをすばやく簡単に編集するための強力な PHP ライブラリです。幅広い機能をユーザーに提供し、プロ並みのスライドをすぐに作成できるようにします。 Aspose を使用すると、ユーザーはテキストを編集したり、イメージ、アニメーション、トランジションをプレゼンテーションに追加したり、フォント タイプや色の選択などのさまざまなフォーマット オプションを適用したりできます。さらに、このライブラリは PowerPoint (PPT) ファイルと OpenOffice プレゼンテーション (ODP) 形式の両方をサポートしているため、互換性の問題が発生することなく、さまざまなプラットフォーム間でプレゼンテーションを簡単に共有できます。次のプレゼンテーションを作成または編集する際に Aspose のライブラリの機能を活用することで、スライドの見栄えを毎回良くすることができます!
新しいテキスト行を追加することで、POTX ファイルを編集できます。 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PHP で POTX を編集" %}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/ja/php-java/) を使用すると、新しいテキスト行を POTX ドキュメントに追加できます。数行のコード。

{{% blocks/products/pf/agp/code-block title="POTX を編集するための PHP コード" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potx");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.potx", SaveFormat::Potx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="PHP で POTX を編集する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for PHP via Java** をインストールします。 [**インストール**](https://docs.aspose.com/slides/php-java/installation/) を参照してください。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ライブラリを参照としてプロジェクトに追加します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーション クラスのインスタンスを作成します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
編集する POTX プレゼンテーションを読み込みます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
新しいテキスト行を追加します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
変更したファイルを保存します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="他のファイルを編集する" subTitle="他の形式のファイルを編集することもできます" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}