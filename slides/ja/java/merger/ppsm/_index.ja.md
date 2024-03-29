---
title: Javaを介してPPSMファイルをマージする
weight: 3190
url: /ja/java/merger/ppsm/ 
description: JSP/JSFアプリケーションおよびデスクトップアプリケーション用のJavaランタイム環境でPPSMドキュメントを組み合わせるためのJavaサンプルコード。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="JavaでPPSM形式をマージする" h2="サーバー側のJavaAPIを使用したネイティブPPSMドキュメントのマージ。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Javaを使用してPPSMファイルをマージする方法" %}}

 PPSMファイルをマージするために、
 [Aspose.Slides for Java]（https://products.aspose.com/slides/ja/java）
 機能豊富で強力で使いやすいJavaプラットフォーム用のマージAPIであるAPI。最新バージョンはから直接ダウンロードできます
 [Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides）
 次の構成をpom.xmlに追加して、Mavenベースのプロジェクトにインストールします。

{{% blocks/products/pf/agp/code-block title="リポジトリ" offSpacer="true" %}}

```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依存" offSpacer="true" %}}

```xml

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


{{< blocks/products/pf/agp/feature-section-col title="JavaでPPSMファイルをマージする手順" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="[Aspose.Slides for Java]（https://products.aspose.com/slides/ja/java）APIとマージおよび連結する基本的なドキュメントは、わずか数行のコードで実行できます。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentationクラスのインスタンスを含む最初のPPSMファイルをロードします。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentationクラスのインスタンスを含む2番目のPPSMドキュメントをロードします。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
2番目のPPSMファイルの各スライドをループします。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
反復ごとに、addClone（）を使用して最初のファイルでスライドを追加します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
save（）メソッドを使用して、指定したパスに保存します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for Javaは、すべての主要なプラットフォームとオペレーティングシステムでサポートされています。次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

-MicrosoftWindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用のJavaランタイム環境と互換性のあるOS。
-最新バージョンのAspose.SlidesforJavaを直接入手する
 [Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides）。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPSMファイルのマージ-Java" offSpacer="" %}}

```cs
// Load first PPSM File
Presentation prest1 = new Presentation("prest1.ppsm");

// Load second PPSM File
Presentation prest2 = new Presentation("prest2.ppsm");

// Merge
for (ISlide slide : prest2.getSlides()) {
	// Merge from source to target
	prest1.getSlides().addClone(slide);
}

// Save the File
prest1.save("merged-presentation.ppsm", SaveFormat.Ppsm);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="PDFファイルをオンラインで結合" sectionDescription="[Python で PDF をマージする方法](https://products.aspose.com/slides/ja/python-net/merge/pdf/)" >}}

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Slides forJavaAPIについて" %}}

 Aspose.Slides APIを使用して、Microsoft PowerPointドキュメントの読み取り、書き込み、操作、およびPDF、XPS、HTML、TIFF、ODP、その他のさまざまな形式への変換を行うことができます。新しいファイルを最初から作成し、サポートされている関連する形式で保存できます。 Aspose.Slidesは、プレゼンテーション、スライド、要素を作成、解析、または操作するためのスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアに依存しません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online PPSM Merger Live Demos" sectionDescription="Merge PPSM documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/merger). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPSM files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be merged and concatenated instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPSM" readMoreLink="https://docs.fileformat.com/presentation/ppsm/" >}}
Files with PPSM extension represent Macro-enabled Slide Show file format created with Microsoft PowerPoint 2007 or higher. Another similar file format is PPTM which differs in opening with Microsoft PowerPoint in editable format instead of running as Slide Show. When run as slide show, the PPSM file shows the presentation slides with contents intact in the slide show and is in read-only mode by default. PPSM files can still be edited in Microsoft PowerPoint by opening it in PowerPoint. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされているマージ形式" subTitle="Javaを使用すると、を含む他の多くのファイル形式をマージすることもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/odp/" name="ODP" description="OpenDocumentプレゼンテーション形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/otp/" name="OTP" description="OpenDocument標準フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/pot/" name="POT" description="MicrosoftPowerPointテンプレートファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/potm/" name="POTM" description="MicrosoftPowerPointテンプレートファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/potx/" name="POTX" description="MicrosoftPowerPointテンプレートプレゼンテーション" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/pps/" name="PPS" description="PowerPointのスライドショー" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/ppsx/" name="PPSX" description="PowerPointのスライドショー" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/pptm/" name="PPTM" description="マクロ対応のプレゼンテーションファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/pptx/" name="PPTX" description="XMLプレゼンテーション形式を開く" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}