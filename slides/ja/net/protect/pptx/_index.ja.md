---
title: .NETを介してPPTXドキュメントを保護およびロックする
weight: 5000
url: /ja/net/protect/pptx/ 
description: .NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームでパスワードを使用してPPTXファイルをロックするためのC＃ソースコード。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C＃を介してPPTXファイルを暗号化する" h2=".NETライブラリを使用したPPTX形式を含むPowerPointプレゼンテーションをパスワードで保護します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C＃を使用してPPTXファイルを保護する方法" %}}

 PPTXファイルを保護するために、
 [Aspose.Slides for .NET]（https://products.aspose.com/slides/ja/net）
 C＃プラットフォーム用の機能が豊富で強力で使いやすいドキュメント保護APIであるAPI。開ける
 [NuGet]（https://www.nuget.org/packages/aspose.slides.net）
 パッケージマネージャー、検索
 ** Aspose.Slides **
 とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="Aspose.Slides" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="C＃を介してPPTXを保護する" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="次のワークフローを実行するには、プロジェクトで参照されている[aspose.slides.dll]（https://downloads.aspose.com/slides/net）が必要です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションのインスタンスを使用してPPTXをロードします
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
IProtectionManager.Encryptメソッドでプレゼンテーションを保護します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果をPPTX形式で保存する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for .NETは、すべての主要なオペレーティングシステムでサポートされています。次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

-Microsoft Windows、または.NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームと互換性のあるOS
-MicrosoftVisualStudioのような開発環境
-プロジェクトで参照されているAspose.Slidesfor.NET

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="指示" offSpacer="" %}}

```cs

// instantiate Presentation object with path to PPTX file
var presentation = new Slides.Presentation();

// protect the presenttaion with password
presentation.ProtectionManager.Encrypt("password");

// save presentation to a PPTX file
presentation.Save("protected.pptx", Slides.Export.SaveFormat.Pptx);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Slides for.NETAPIについて" %}}

 Aspose.Slides APIを使用して、Microsoft PowerPointドキュメントの読み取り、書き込み、操作、およびPDF、XPS、HTML、TIFF、ODP、その他のさまざまな形式への変換を行うことができます。新しいファイルを最初から作成し、サポートされている関連する形式で保存できます。 Aspose.Slidesは、プレゼンテーション、スライド、要素を作成、解析、または操作するためのスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアに依存しません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Protect PPTX" sectionDescription="Check our live demos to [encrypt PPTX files](https://products.aspose.app/slides/protect/pptx) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload PPTX file and hit the \"Unlock\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant PPTX file from the link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている保護フォーマット" subTitle="C＃を使用すると、を含む他の形式を簡単に保護できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/protect/odp/" name="ODP" description="OpenDocumentプレゼンテーション形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/protect/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}