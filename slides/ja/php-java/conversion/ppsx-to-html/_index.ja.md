---
title: PHPでPPSXをHTMLに変換する
weight: 1930
url: /ja/php-java/conversion/ppsx-to-html/ 
keywords: "Convert, PowerPoint, PPSX, HTML, Presentation, PHP"
description: PPSXからHTMLへのPHP変換のサンプルコード。 PPSXファイルからHTMLファイルへのバッチ変換にはPowerPointPHPAPIを使用します。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="PHPでPPSXをHTMLに変換する" h2="PPSXをHTMLに変換するための強力なPowerPointPHPライブラリ" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="PHPでPPSXをHTMLに変換する" %}}

プログラムでPPSXファイルをHTMLに変換する必要がありますか？ [* Aspose.Slides for PHP via Java *]（https://products.aspose.com/slides/ja/php-java/）を使用すると、開発者は数行のPHPコードでPPSXをHTML形式に変換できます。 。

最新のプレゼンテーション処理APIとして、Aspose.SlidesforPHPはPPSXからHTMLをすばやく作成します。 [ブラウザ]（https://products.aspose.app/slides/conversion）でPPSXからHTMLへの変換の品質をテストします。 Aspose PowerPoint PPTXライブラリを使用すると、PPSXファイルを多くの一般的な形式に変換できます。

次のコマンドを使用して、[Composer]（https://packagist.org/packages/aspose/slides）からライブラリをインストールできます。

{{% blocks/products/pf/agp/code-block title="コンソール/ターミナル" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="PHPでPPSXをHTMLに変換する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、PHPを使用してPPSXファイルをHTMLに変換する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentationクラスのインスタンスを含むPPSXファイルをロードします
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
パラメータとして出力ファイルパスとSaveFormat。HTMLを指定しながら、`save`メソッドを呼び出します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPSXファイルは指定されたパスに保存されます
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

{{% blocks/products/pf/agp/code-block title="このサンプルコードは、PPSXからHTMLへのPHP変換を示しています" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsx");
try
{
    $pres->save("output.html", SaveFormat::Html5);
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
 
{{% blocks/products/pf/agp/content h2="PHPでPPSXをHTMLとして保存します" %}}
無料アプリを使用して、PPSXからHTMLへの変換プロセスのデモをご覧ください。 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PPSX to HTML" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="PPSXを他の多くのファイル形式に変換することもできます。以下のサポートされている他の変換を参照してください" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="ビットマップ画像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" description="OpenDocumentフラットXMLプレゼンテーション" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="グラフィカルな交換フォーマット" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-jpg/" name="PPSX TO JPG" description="JPEG画像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocumentプレゼンテーション形式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument標準フォーマット" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="ポータブルドキュメントフォーマット" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-png/" name="PPSX TO PNG" description="ポータブルネットワークグラフィックス" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-pot/" name="PPSX TO POT" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="MicrosoftPowerPointテンプレートプレゼンテーション" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="マクロ対応のスライドショー" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="マクロ対応のプレゼンテーションファイル" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="XMLプレゼンテーション形式を開く" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="スケーラブルベクターグラフィックス" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="SWFフォーマット" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="タグ付き画像形式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/php-java/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="XML用紙仕様" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}