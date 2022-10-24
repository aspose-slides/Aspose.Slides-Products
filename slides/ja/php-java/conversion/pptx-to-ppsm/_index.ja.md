---
title: PHPでPPTXをPPSMに変換する
weight: 2660
url: /ja/php-java/conversion/pptx-to-ppsm/ 
keywords: "Convert, PowerPoint, PPTX, PPSM, Presentation, PHP"
description: PPTXからPPSMへのPHP変換のサンプルコード。 PPTXファイルからPPSMファイルへのバッチ変換にはPowerPointPHPAPIを使用します。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="PHPでPPTXをPPSMに変換する" h2="PPTXをPPSMに変換するための強力なPowerPointPHPライブラリ" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="PHPでPPTXをPPSMに変換する" %}}

プログラムでPPTXファイルをPPSMに変換する必要がありますか？ [* Aspose.Slides for PHP via Java *]（https://products.aspose.com/slides/ja/php-java/）を使用すると、開発者は数行のPHPコードでPPTXをPPSM形式に変換できます。 。

最新のプレゼンテーション処理APIとして、Aspose.SlidesforPHPはPPTXからPPSMをすばやく作成します。 [ブラウザ]（https://products.aspose.app/slides/conversion）でPPTXからPPSMへの変換の品質をテストします。 Aspose PowerPoint PPTXライブラリを使用すると、PPTXファイルを多くの一般的な形式に変換できます。

次のコマンドを使用して、[Composer]（https://packagist.org/packages/aspose/slides）からライブラリをインストールできます。

{{% blocks/products/pf/agp/code-block title="コンソール/ターミナル" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="PHPでPPTXをPPSMに変換する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、PHPを使用してPPTXファイルをPPSMに変換する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentationクラスのインスタンスを含むPPTXファイルをロードします
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
パラメータとして出力ファイルパスとSaveFormat。PPSMを指定しながら、`save`メソッドを呼び出します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTXファイルは指定されたパスに保存されます
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

{{% blocks/products/pf/agp/code-block title="このサンプルコードは、PPTXからPPSMへのPHP変換を示しています" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptx");
try
{
    $pres->save("output.ppsm", SaveFormat::Ppsm);
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
 
{{% blocks/products/pf/agp/content h2="PHPでPPTXをPPSMとして保存します" %}}
無料アプリを使用して、PPTXからPPSMへの変換プロセスのデモをご覧ください。 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PPTX to PPSM" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="PPTXを他の多くのファイル形式に変換することもできます。以下のサポートされている他の変換を参照してください" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="ビットマップ画像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-fodp/" name="PPTX TO FODP" description="OpenDocumentフラットXMLプレゼンテーション" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-gif/" name="PPTX TO GIF" description="グラフィカルな交換フォーマット" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-html/" name="PPTX TO HTML" description="ハイパーテキストマークアップ言語" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-jpg/" name="PPTX TO JPG" description="JPEG画像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocumentプレゼンテーション形式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument標準フォーマット" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="ポータブルドキュメントフォーマット" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-png/" name="PPTX TO PNG" description="ポータブルネットワークグラフィックス" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-pot/" name="PPTX TO POT" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-potm/" name="PPTX TO POTM" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-potx/" name="PPTX TO POTX" description="MicrosoftPowerPointテンプレートプレゼンテーション" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-pps/" name="PPTX TO PPS" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="マクロ対応のプレゼンテーションファイル" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-svg/" name="PPTX TO SVG" description="スケーラブルベクターグラフィックス" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-swf/" name="PPTX TO SWF" description="SWFフォーマット" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="タグ付き画像形式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML用紙仕様" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}