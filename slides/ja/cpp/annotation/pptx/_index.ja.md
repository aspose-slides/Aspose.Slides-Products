---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: C++ で PPTX の注釈を削除
url: /ja/cpp/annotation/pptx/ 
description: PPTX プレゼンテーションから注釈を削除する C++ ソース コード。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ で PPTX からコメントとコメント作成者を削除" h2="サーバー側 API を使用して、プレゼンテーション ファイル内のコメントと作成者を操作する C++ アプリを構築します。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ で PPTX からコメントを削除" variant="code" %}}

[Aspose.Slides for C++](/slides/ja/cpp/) を使用して、PPTX プレゼンテーションからコメントとコメント作成者を削除します。以下の例では、`get_CommentAuthors` から取得した各作成者のコメントをクリアしてから、コメント作成者コレクションをクリアします。

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX から注釈を削除 – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.pptx");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ で PPTX からコメントを削除する方法" intro="PPTX プレゼンテーションからコメントとコメント作成者を削除するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aspose.Slides for C++ をインストールします。[インストール](https://docs.aspose.com/slides/cpp/installation/) を参照してください。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで PPTX ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`get_CommentAuthors` から取得したコメント作成者を反復処理します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`get_Comments()->Clear()` で各作成者のコメントをクリアします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}コメント作成者コレクションをクリアします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat::Pptx` で更新したプレゼンテーションを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides で構築" title="PPTX のコメントをオンラインで削除" description="無料の Aspose.Slides Annotation アプリは、上記のコードと同じ API である [Aspose.Slides for C++](https://products.aspose.com/slides/ja/cpp/) で構築されています。アプリを開いて、ご自身の PPTX ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Annotation を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がコメントを削除するしくみを確認できます。
- PPTX ファイルからすべてのコメントを削除します。
- クリーンアップしたファイルをダウンロードします。
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="注釈でサポートされるその他の形式" subTitle="C++ を使用すると、他の形式からも注釈を削除できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
