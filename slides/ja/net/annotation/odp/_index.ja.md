---
title: .NET を使用して ODP アノテーションを削除する
weight: 4380
url: /ja/net/annotation/odp/ 
description: .NET Framework、.NET Core、Windows Azure、Mono、または Xamarin プラットフォームで ODP 形式の注釈を削除する C# ソース コード。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C# で ODP からコメントとコメント作成者を削除する" h2="サーバー側 API を使用してドキュメント ファイル内のコメントと作成者を操作する独自の .NET アプリを構築します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="C# を使用して ODP からコメントを削除する" %}}
ODP ファイルから注釈を削除するには、[Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net) API を使用します。これは、機能が豊富で強力で使いやすい API です。 C# プラットフォーム用のドキュメント操作 API。
{{% blocks/products/pf/agp/code-block title="ODP から注釈を削除する - C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.odp"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="C# を使用して ODP からコメントを削除する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for .NET** をインストールします。 [**インストール**](https://docs.aspose.com/slides/net/installation/) を参照してください。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーション クラスのインスタンスを使用して ODP をロードする
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ロードされた ODP のすべての作成者を反復する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
著者のすべてのコメントを削除する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
最後にすべての作成者を削除します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="サポートされているその他の注釈形式" subTitle="C# を使用すると、次のような他の形式に簡単に注釈を付けることができます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}