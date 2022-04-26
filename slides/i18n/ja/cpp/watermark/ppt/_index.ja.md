---
title: C++による透かしPPTドキュメント
weight: 3820
url: /ja/cpp/watermark/ppt/ 
description: Windows 32ビット、Windows 64ビット、およびLinux64ビット用のC++ランタイム環境でPPTファイルに透かしを追加または削除するC++サンプルコード。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C++を介してPPTにテキスト透かしを追加する" h2="サーバー側APIを使用してPPTファイルに透かしを入れる独自のC++アプリを作成します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++を使用してPPTファイルに透かしを入れる方法" %}}

 PPTファイルに透かしを入れるために、
 [Aspose.Slides for C ++]（https://products.aspose.com/slides/cpp）
 機能が豊富で強力で使いやすいC++プラットフォーム用のドキュメント透かしAPIであるAPI。最新バージョンを直接ダウンロードできます。開くだけです。
 [NuGet]（https://www.nuget.org/packages/aspose.slides）
 パッケージマネージャー、検索
 ** Aspose.Slides.Cpp **
 とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="指示" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="C++を介して透かしをPPTに追加する手順" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="自分の環境で次のワークフローを試すには、[aspose.slides.dll]（https://downloads.aspose.com/slides/cpp）が必要です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentationクラスのインスタンスを使用してPPTファイルをロードする
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
最初のスライドを取得
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
長方形タイプのオートシェイプを追加します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
TextFrameを長方形に追加します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
テキストフレームの段落オブジェクトを作成します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
段落の部分オブジェクトを作成する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
set \ _Text（）を使用して透かしを追加します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ドキュメントを保存
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for C ++は、すべての主要なプラットフォームとオペレーティングシステムでサポートされています。次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPTに透かしを追加-C++" offSpacer="" %}}

```cs

// Load the desired PPT File
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"templatePath.ppt");

// Access first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150, 75, 150, 50);

ashp->get_FillFormat()->set_FillType(FillType::NoFill);

// Add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");

// Accessing the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();

// Create the Paragraph object for text frame
SharedPtr<IParagraph> paragraph = txtFrame->get_Paragraphs()->idx_get(0);

// Create Portion object for paragraph
SharedPtr<IPortion> portion = paragraph->get_Portions()->idx_get(0);
portion->set_Text(u"Watermark Text Watermark Text Watermark Text");

//Adding another shape
SharedPtr<IAutoShape>  ashape2 = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 200, 365, 400, 150);

//Reorder shape
slide->get_Shapes()->Reorder(2, ashape2);

// Save PPT to Disk
pres->Save(u"outPath.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Slides for C++APIについて" %}}

 Aspose.Slides APIを使用して、Microsoft PowerPointドキュメントの読み取り、書き込み、操作、およびPDF、XPS、HTML、TIFF、ODP、その他のさまざまな形式への変換を行うことができます。新しいファイルを最初から作成し、サポートされている関連する形式で保存できます。 Aspose.Slidesは、プレゼンテーション、スライド、要素を作成、解析、または操作するためのスタンドアロンAPIであり、MicrosoftやOpenOfficeなどのソフトウェアに依存しません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Watermark PPT via Online App" sectionDescription="Add watermark to PPT documents by visiting our [Live Demos website](https://products.aspose.app/slides/watermark). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPT file, set your watermark and hit \"Add\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている透かし形式" subTitle="C ++を使用すると、を含むさまざまな形式に簡単に透かしを入れることができます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/watermark/pptx/" name="PPTX" description="XMLプレゼンテーション形式を開く" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}