---
title: .NETを介してPPTドキュメント内のテキストを検索および置換します
weight: 1410
url: /ja/net/redaction/ppt/ 
description: .NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォーム上のPPTファイル内の機密情報を編集するためのC＃ソースコード。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C＃でPPTフォーマットを編集する" h2="ネイティブで高性能のPPTは、MicrosoftやAdobe PDFなどのソフトウェアを使用せずに、サーバー側のAspose.Slides for.NETAPIを使用して機密性の高い編集情報を文書化します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C＃を使用してPPTファイルを編集する方法" %}}

 PPTファイルを編集するために、
 [Aspose.Slides for .NET]（https://products.aspose.com/slides/net）
 C＃プラットフォーム用の機能豊富で強力で使いやすいドキュメント操作APIであるAPI。開ける
 [NuGet]（https://www.nuget.org/packages/aspose.slides.net）
 パッケージマネージャー、検索
 ** Aspose.Slides **
 とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="指示" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="C＃でPPTファイルを編集する手順" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="基本的なドキュメント検索と、コンテンツ、コメント、またはメタデータのテキストを[Aspose.Slides for .NET]（https://products.aspose.com/slides/net）APIに置き換えると、わずか数行のコードで実行できます。 PowerPointとOpenOfficeでテキストを検索して置き換えます。正規表現データマッチングを介して、プレゼンテーションのテキスト、コメント、メタデータを編集します。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTプレゼンテーションをロードします。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
各スライドをループして、textFrameコレクションを取得します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
コレクションをループします。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Replaceメソッドを使用してから、テキストを強調表示します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションを保存します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 当社のAPIは、すべての主要なプラットフォームとオペレーティングシステムでサポートされています。以下のコードを実行する前に、システムに次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

-Microsoft Windows、または.NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームと互換性のあるOS
-MicrosoftVisualStudioのような開発環境
-プロジェクトで参照されているAspose.Slidesfor.NETDLL-上の[ダウンロード]ボタンを使用してNuGetからインストールします

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPTファイルを編集する-C＃" offSpacer="" %}}

```cs
using (Presentation pres = new Presentation("pres.ppt")){
    const string toRedact = "bKIM";
    string stub = new string(' ', toRedact.Length);
   //Using Aspose.Slides, one can use highlight text color feature to Redact text.
    foreach (ISlide slide in pres.Slides){
        ITextFrame[] textFrames = SlideUtil.GetAllTextBoxes(slide);
        foreach (ITextFrame textFrame in textFrames){
            textFrame.Text = textFrame.Text.Replace(toRedact, stub);
            textFrame.HighlightText(stub, Color.Black);
        }
    }

    pres.Save("pres-edited.ppt", SaveFormat.Ppt);
}

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Slides for.NETAPIについて" %}}

 Aspose.Slides APIを使用して、Microsoft PowerPointドキュメントの読み取り、書き込み、操作、およびPDF、XPS、HTML、TIFF、ODP、その他のさまざまな形式への変換を行うことができます。新しいファイルを最初から作成し、サポートされている関連する形式で保存できます。 Aspose.Slidesは、プレゼンテーション、スライド、要素を作成、解析、または操作するためのスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアに依存しません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Redaction Live Demos" sectionDescription="Search and replace text in contents, comments or metadata in PPT documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/redaction). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPT files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be redacted instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている編集フォーマット" subTitle="C＃を使用すると、次のようなさまざまな形式を簡単に編集できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/redaction/odp/" name="ODP" description="OpenDocumentプレゼンテーション形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/redaction/pptx/" name="PPTX" description="XMLプレゼンテーション形式を開く" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}