---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PHPでPPTMをFODPに変換する
weight: 2330
url: /ja/php-java/conversion/pptm-to-fodp/ 
keywords: "Convert, PowerPoint, PPTM, FODP, Presentation, PHP"
description: PPTMからFODPへのPHP変換のサンプルコード。 PPTMファイルからFODPファイルへのバッチ変換にはPowerPointPHPAPIを使用します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PHPでPPTMをFODPに変換する" h2="PPTMをFODPに変換するための強力なPowerPointPHPライブラリ"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHPでPPTMをFODPに変換する" %}}

プログラムでPPTMファイルをFODPに変換する必要がありますか？ [* Aspose.Slides for PHP via Java *](https://products.aspose.com/slides/ja/php-java/)を使用すると、開発者は数行のPHPコードでPPTMをFODP形式に変換できます。 。

最新のプレゼンテーション処理APIとして、Aspose.SlidesforPHPはPPTMからFODPをすばやく作成します。 [ブラウザ](https://products.aspose.app/slides/conversion)でPPTMからFODPへの変換の品質をテストします。 Aspose PowerPoint PPTXライブラリを使用すると、PPTMファイルを多くの一般的な形式に変換できます。

次のコマンドを使用して、[Composer](https://packagist.org/packages/aspose/slides)からライブラリをインストールできます。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="コンソール/ターミナル" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHPでPPTMをFODPとして保存します" %}}

無料アプリを使用して、PPTMからFODPへの変換プロセスのデモをご覧ください。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="このサンプルコードは、PPTMからFODPへのPHP変換を示しています" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptm");
try
{
    $pres->save("output.fodp", SaveFormat::Fodp);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PHPでPPTMをFODPに変換する方法" intro="これらは、PHPを使用してPPTMファイルをFODPに変換する手順です。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentationクラスのインスタンスを含むPPTMファイルをロードします{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}パラメータとして出力ファイルパスとSaveFormat。FODPを指定しながら、`save`メソッドを呼び出します{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTMファイルは指定されたパスに保存されます{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="システム要求" intro="PHP変換サンプルソースコードを実行する前に、次の前提条件があることを確認してください。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PHP 7をインストールし、PHPへのパスをシステムの `PATH`変数に追加し、`php.ini`ファイルで`allow_url_include`を`On`に設定します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}JREをインストールします。8。`JAVA_HOME`環境変数をインストールされたJREの場所へのパスとして設定します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apache Tomcat 8.0をインストールします（[詳細](https://docs.aspose.com/slides/php-java/installation/)を参照）。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPTM to FODP"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他のサポートされている変換" subTitle="PPTMを他の多くのファイル形式に変換することもできます。以下のサポートされている他の変換を参照してください" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="ビットマップ画像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="グラフィカルな交換フォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-html/" name="PPTM TO HTML" description="ハイパーテキストマークアップ言語" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-jpg/" name="PPTM TO JPG" description="JPEG画像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-odp/" name="PPTM TO ODP" description="OpenDocumentプレゼンテーション形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-otp/" name="PPTM TO OTP" description="OpenDocument標準フォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="ポータブルドキュメントフォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-png/" name="PPTM TO PNG" description="ポータブルネットワークグラフィックス" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-pot/" name="PPTM TO POT" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-potm/" name="PPTM TO POTM" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-potx/" name="PPTM TO POTX" description="MicrosoftPowerPointテンプレートプレゼンテーション" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-pps/" name="PPTM TO PPS" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="マクロ対応のスライドショー" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="XMLプレゼンテーション形式を開く" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="スケーラブルベクターグラフィックス" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="SWFフォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="タグ付き画像形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/php-java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="XML用紙仕様" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
