---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: .NET で ODP の注釈を削除
url: /ja/net/annotation/odp/ 
description: C# で ODP プレゼンテーションからコメントとコメント作成者を削除します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# で ODP からコメントとコメント作成者を削除" h2="サーバー側 API を使用して、プレゼンテーション ファイル内のコメントと作成者を操作する .NET アプリケーションを構築します。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# で ODP からコメントを削除" variant="code" %}}

[Aspose.Slides for .NET](/slides/ja/net/) を使用して、ODP プレゼンテーション ファイルからコメントとコメント作成者を削除します。以下の例では、各作成者の `Comments` コレクションをクリアしてから、プレゼンテーションの `CommentAuthors` コレクションをクリアします。

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP から注釈を削除 – C#" >}}
```cs
using var presentation = new Presentation("example.odp");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# で ODP からコメントを削除する方法" intro="ODP プレゼンテーションからコメントとコメント作成者を削除するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aspose.Slides for .NET をインストールします。[インストール](https://docs.aspose.com/slides/net/installation/) を参照してください。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで ODP ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`CommentAuthors` コレクションを反復処理します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}各コメント作成者の `Comments` コレクションをクリアします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`CommentAuthors` コレクションをクリアします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Odp` で更新したプレゼンテーションを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides で構築" title="ODP のコメントをオンラインで削除" description="無料の Aspose.Slides Annotation アプリは、上記のコードと同じ API である [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net/) で構築されています。アプリを開いて、ご自身の ODP ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Annotation を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がコメントを削除するしくみを確認できます。
- ODP ファイルからすべてのコメントを削除します。
- クリーンアップしたファイルをダウンロードします。
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="注釈でサポートされるその他の形式" subTitle="C# を使用すると、他の形式からも注釈を削除できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/net/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
