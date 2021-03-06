---
title: PHPでPPSMをGIFに変換する
weight: 1710
url: /ja/php-java/conversion/ppsm-to-gif/ 
keywords: "Convert, PowerPoint, PPSM, GIF, Presentation, PHP"
description: PPSMからGIFへのPHP変換のサンプルコード。 PPSMファイルからGIFファイルへのバッチ変換にはPowerPointPHPAPIを使用します。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="PHPでPPSMをGIFに変換する" h2="PPSMをGIFに変換するための強力なPowerPointPHPライブラリ" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="PHPでPPSMをGIFに変換する" %}}

プログラムでPPSMファイルをGIFに変換する必要がありますか？ [* Aspose.Slides for PHP via Java *]（https://products.aspose.com/slides/ja/php-java/）を使用すると、開発者は数行のPHPコードでPPSMをGIF形式に変換できます。 。

最新のプレゼンテーション処理APIとして、Aspose.SlidesforPHPはPPSMからGIFをすばやく作成します。 [ブラウザ]（https://products.aspose.app/slides/conversion）でPPSMからGIFへの変換の品質をテストします。 Aspose PowerPoint PPTXライブラリを使用すると、PPSMファイルを多くの一般的な形式に変換できます。

次のコマンドを使用して、[Composer]（https://packagist.org/packages/aspose/slides）からライブラリをインストールできます。

{{% blocks/products/pf/agp/code-block title="コンソール/ターミナル" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="PHPでPPSMをGIFに変換する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、PHPを使用してPPSMファイルをGIFに変換する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentationクラスのインスタンスを含むPPSMファイルをロードします
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
パラメータとして出力ファイルパスとSaveFormat。GIFを指定しながら、`save`メソッドを呼び出します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPSMファイルは指定されたパスに保存されます
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 PHP変換サンプルソースコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

1. PHP 7をインストールし、PHPへのパスをシステムの `PATH`変数に追加し、`php.ini`ファイルで`allow_url_include`を`On`に設定します。
1.JREをインストールします。8。`JAVA_HOME`環境変数をインストールされたJREの場所へのパスとして設定します。
1. Apache Tomcat 8.0をインストールします（[詳細]（https://docs.aspose.com/slides/php-java/installation/）を参照）。 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="このサンプルコードは、PPSMからGIFへのPHP変換を示しています" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsm");
try
{
    $pres->save("output.gif", SaveFormat::Gif);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="PHPでPPSMをGIFとして保存します" %}}
無料アプリを使用して、PPSMからGIFへの変換プロセスのデモをご覧ください。 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PPSM to GIF" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="PPSMを他の多くのファイル形式に変換することもできます。以下のサポートされている他の変換を参照してください" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="ビットマップ画像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-fodp/" name="PPSM TO FODP" description="OpenDocumentフラットXMLプレゼンテーション" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-html/" name="PPSM TO HTML" description="ハイパーテキストマークアップ言語" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-jpg/" name="PPSM TO JPG" description="JPEG画像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="OpenDocumentプレゼンテーション形式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="OpenDocument標準フォーマット" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="ポータブルドキュメントフォーマット" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-png/" name="PPSM TO PNG" description="ポータブルネットワークグラフィックス" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-pot/" name="PPSM TO POT" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="MicrosoftPowerPointテンプレートプレゼンテーション" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="マクロ対応のプレゼンテーションファイル" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="XMLプレゼンテーション形式を開く" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="スケーラブルベクターグラフィックス" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="SWFフォーマット" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="タグ付き画像形式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="XML用紙仕様" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}