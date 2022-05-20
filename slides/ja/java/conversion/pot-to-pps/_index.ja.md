---
title: Javaを介してPOTをPPSに変換する
weight: 2090
url: /ja/java/conversion/pot-to-pps/ 
description: POT形式からPPSファイルへのサンプルJava変換コード。このサンプルコードを使用して、PowerPointおよびOpenOfficeプレゼンテーションをWebまたはデスクトップJavaベースのアプリケーション内のPPSにエクスポートします。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Javaを介してPOTをPPSに変換する" h2="オンプレミスJavaライブラリを使用して単一または複数のページをPPSに変換するためのPOTからPPSへのJava変換。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Javaを使用してPOTをPPSに変換する方法" %}}

 POTをPPSにレンダリングするために、
 [Aspose.Slides for Java]（https://products.aspose.com/slides/ja/java）
 機能豊富で強力で使いやすいJavaプラットフォーム用の変換APIであるAPI。最新バージョンはから直接ダウンロードできます
 [Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides）
 次の構成をpom.xmlに追加して、Mavenベースのプロジェクトにインストールします。

{{% blocks/products/pf/agp/code-block title="リポジトリ" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依存" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-slides</artifactId>
<version>version of aspose-slides API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Javaを介してPOTをPPSに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Java開発者は、わずか数行のコードでPOTフ​​ァイルをPPSに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1.Presentationクラスのインスタンスを含むPOTファイルをロードします
1.出力ファイルのパスとSaveFormatを指定しながら、Presentation.saveメソッドを呼び出します
1.PPSファイルは指定されたパスに保存されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Java変換サンプルコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

-MicrosoftWindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用のJavaランタイム環境と互換性のあるOS。
-Mavenから直接最新バージョンのAspose.SlidesforJavaを入手します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="POTからPPSへのJava変換ソースコード" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("template.pot");
// save the presentation as PPS
presentation.save("output.pps", SaveFormat.Pps);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="pot-to-pps"
        sectionTitle="POTをPPSに変換するための無料アプリ" 
        sectionDescription="[無料のMP4 To MP3アプリを試してください](https://products.aspose.app/slides/video/mp4-to-mp3/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="また、POTを、以下にリストされているいくつかを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-bmp/" name="POT TO BMP" description="ビットマップ画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-gif/" name="POT TO GIF" description="グラフィカルな交換形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-html/" name="POT TO HTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-jpeg/" name="POT TO JPEG" description="JPEG画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-odp/" name="POT TO ODP" description="OpenDocumentプレゼンテーション形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-otp/" name="POT TO OTP" description="OpenDocument標準フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-pdf/" name="POT TO PDF" description="ポータブルドキュメントフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-png/" name="POT TO PNG" description="ポータブルネットワークグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-potm/" name="POT TO POTM" description="MicrosoftPowerPointテンプレートファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-potx/" name="POT TO POTX" description="MicrosoftPowerPointテンプレートプレゼンテーション" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-ppsm/" name="POT TO PPSM" description="マクロ対応のスライドショー" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-ppsx/" name="POT TO PPSX" description="PowerPointのスライドショー" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-pptm/" name="POT TO PPTM" description="マクロ対応のプレゼンテーションファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-pptx/" name="POT TO PPTX" description="XMLプレゼンテーション形式を開く" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-svg/" name="POT TO SVG" description="スケーラブルベクターグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-swf/" name="POT TO SWF" description="SWFフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-tiff/" name="POT TO TIFF" description="タグ付き画像形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pot-to-xps/" name="POT TO XPS" description="XML用紙仕様" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}