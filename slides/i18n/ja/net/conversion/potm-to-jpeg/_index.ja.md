---
title: C＃を介してPOTMをJPEGに変換する
weight: 6160
url: /ja/net/conversion/potm-to-jpeg/ 
description: POTMからJPEGC＃への変換のサンプルコード。 VB.NET、Asp.NET、または任意の.NETベースのアプリケーション内でのバッチPOTMファイルからJPEGへの変換にAPIサンプルコードを使用します。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C＃を介してPOTMをJPEGに変換する" h2="PowerPoint®POTMファイルを.NETFramework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォーム上のJPEGにエクスポートします" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POTM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C＃を使用してPOTMをJPEGに変換する方法" %}}

 POTMをJPEGに変換するには、
 [Aspose.Slides for .NET]（https://products.aspose.com/slides/net）
 機能が豊富で強力で使いやすいC＃プラットフォーム用のドキュメント操作および変換APIであるAPI。開ける
 [NuGet]（https://www.nuget.org/packages/aspose.slides.net）
 パッケージマネージャー、検索
 Aspose.Slides
 とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="パッケージマネージャーコンソールコマンド" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="C＃を介してPOTMをJPEGに変換する手順" >}}

{{< blocks/products/pf/agp/steps-block-autogen name=".NET開発者は、わずか数行のコードでPOTMファイルを簡単にロードしてJPEGに変換できます。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentationクラスのインスタンスを含むPOTMファイルをロードします
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションの各スライドを繰り返します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
反復ごとにフルスケール画像をビットマップとして作成します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
パラメータとしてJPEGファイル拡張子とImageFormat.Jpegを使用してBitmap.Saveメソッドを呼び出します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 .NET変換サンプルソースコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

-Microsoft Windows、または.NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームと互換性のあるOS。
-MicrosoftVisualStudioのような開発環境。
-プロジェクトで参照されているAspose.Slidesfor.NETDLL。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="このサンプルコードは、POTMからJPEGへのC＃変換を示しています" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.potm"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in JPEG format
        bitmap.Save(string.Format("Slide_{0}.jpeg", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
    }
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="potm-to-jpeg"
        sectionTitle="POTMをJPEGに変換するための無料アプリ" 
        sectionDescription="[PPTをJPGに変換するために無料のアプリを試してみてください](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="POTMを、以下にリストされているいくつかを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-bmp/" name="POTM TO BMP" description="ビットマップ画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-emf/" name="POTM TO EMF" description="強化されたメタファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-gif/" name="POTM TO GIF" description="グラフィカルな交換形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-html/" name="POTM TO HTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-odp/" name="POTM TO ODP" description="OpenDocumentプレゼンテーション形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-otp/" name="POTM TO OTP" description="OpenDocument標準フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-pdf/" name="POTM TO PDF" description="ポータブルドキュメントフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-png/" name="POTM TO PNG" description="ポータブルネットワークグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-pot/" name="POTM TO POT" description="MicrosoftPowerPointテンプレートファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-potx/" name="POTM TO POTX" description="MicrosoftPowerPointテンプレートプレゼンテーション" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-pps/" name="POTM TO PPS" description="PowerPointのスライドショー" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="マクロ対応のスライドショー" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="PowerPointのスライドショー" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-pptm/" name="POTM TO PPTM" description="マクロ対応のプレゼンテーションファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-pptx/" name="POTM TO PPTX" description="XMLプレゼンテーション形式を開く" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-svg/" name="POTM TO SVG" description="スケーラブルベクターグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-swf/" name="POTM TO SWF" description="SWFフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-tiff/" name="POTM TO TIFF" description="タグ付き画像形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/potm-to-xps/" name="POTM TO XPS" description="XML用紙仕様" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}