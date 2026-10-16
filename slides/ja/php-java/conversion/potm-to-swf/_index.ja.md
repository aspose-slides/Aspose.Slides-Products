---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PHPでPOTMをSWFに変換する
weight: 1240
url: /ja/php-java/conversion/potm-to-swf/ 
keywords: "Convert, PowerPoint, POTM, SWF, Presentation, PHP"
description: POTMからSWFへのPHP変換のサンプルコード。 POTMファイルからSWFファイルへのバッチ変換にはPowerPointPHPAPIを使用します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PHPでPOTMをSWFに変換する" h2="POTMをSWFに変換するための強力なPowerPointPHPライブラリ"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHPでPOTMをSWFに変換する" %}}

プログラムでPOTMファイルをSWFに変換する必要がありますか？ [* Aspose.Slides for PHP via Java *](https://products.aspose.com/slides/ja/php-java/)を使用すると、開発者は数行のPHPコードでPOTMをSWF形式に変換できます。 。

最新のプレゼンテーション処理APIとして、Aspose.SlidesforPHPはPOTMからSWFをすばやく作成します。 [ブラウザ](https://products.aspose.app/slides/conversion)でPOTMからSWFへの変換の品質をテストします。 Aspose PowerPoint PPTXライブラリを使用すると、POTMファイルを多くの一般的な形式に変換できます。

次のコマンドを使用して、[Composer](https://packagist.org/packages/aspose/slides)からライブラリをインストールできます。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="コンソール/ターミナル" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHPでPOTMをSWFとして保存します" %}}

無料アプリを使用して、POTMからSWFへの変換プロセスのデモをご覧ください。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="このサンプルコードは、POTMからSWFへのPHP変換を示しています" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potm");
try
{
    $pres->save("output.swf", SaveFormat::Swf);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PHPでPOTMをSWFに変換する方法" intro="これらは、PHPを使用してPOTMファイルをSWFに変換する手順です。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentationクラスのインスタンスを含むPOTMファイルをロードします{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}パラメータとして出力ファイルパスとSaveFormat。SWFを指定しながら、`save`メソッドを呼び出します{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}POTMファイルは指定されたパスに保存されます{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="システム要求" intro="PHP変換サンプルソースコードを実行する前に、次の前提条件があることを確認してください。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PHP 7をインストールし、PHPへのパスをシステムの `PATH`変数に追加し、`php.ini`ファイルで`allow_url_include`を`On`に設定します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}JREをインストールします。8。`JAVA_HOME`環境変数をインストールされたJREの場所へのパスとして設定します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apache Tomcat 8.0をインストールします（[詳細](https://docs.aspose.com/slides/php-java/installation/)を参照）。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert POTM to SWF"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他のサポートされている変換" subTitle="POTMを他の多くのファイル形式に変換することもできます。以下のサポートされている他の変換を参照してください" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-bmp/" name="POTM TO BMP" description="ビットマップ画像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-fodp/" name="POTM TO FODP" description="OpenDocumentフラットXMLプレゼンテーション" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-gif/" name="POTM TO GIF" description="グラフィカルな交換フォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-html/" name="POTM TO HTML" description="ハイパーテキストマークアップ言語" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-jpg/" name="POTM TO JPG" description="JPEG画像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-odp/" name="POTM TO ODP" description="OpenDocumentプレゼンテーション形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-otp/" name="POTM TO OTP" description="OpenDocument標準フォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-pdf/" name="POTM TO PDF" description="ポータブルドキュメントフォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-png/" name="POTM TO PNG" description="ポータブルネットワークグラフィックス" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-pot/" name="POTM TO POT" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-potx/" name="POTM TO POTX" description="MicrosoftPowerPointテンプレートプレゼンテーション" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-pps/" name="POTM TO PPS" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="マクロ対応のスライドショー" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="マクロ対応のプレゼンテーションファイル" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="XMLプレゼンテーション形式を開く" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-svg/" name="POTM TO SVG" description="スケーラブルベクターグラフィックス" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-tiff/" name="POTM TO TIFF" description="タグ付き画像形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/potm-to-xps/" name="POTM TO XPS" description="XML用紙仕様" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
