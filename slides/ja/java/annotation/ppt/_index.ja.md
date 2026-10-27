---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3630
title: Java で PPT の注釈を削除
url: /ja/java/annotation/ppt/ 
description: Aspose.Slides for Java を使用して、Java で PPT プレゼンテーションからコメントとコメント作成者を削除します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java で PPT からコメントとコメント作成者を削除" h2="Aspose.Slides for Java を使用して、プレゼンテーション ファイルからコメントとコメント作成者を削除します。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java で PPT からコメントを削除" variant="code" %}}

Aspose.Slides for Java を使用すると、PPT プレゼンテーションからコメントとコメント作成者を削除できます。`Presentation` クラスでファイルを読み込み、`getCommentAuthors` から取得した `ICommentAuthor` オブジェクトを反復処理してコメントをクリアし、更新したプレゼンテーションを保存します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT から注釈を削除 – Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java で PPT からコメントを削除する方法" intro="PPT プレゼンテーションからコメントとコメント作成者を削除するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aspose.Slides for Java をインストールします。[インストール](https://docs.aspose.com/slides/java/installation/) を参照してください。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで PPT ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`getCommentAuthors` から取得した `ICommentAuthor` オブジェクトを反復処理します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`getComments().clear()` で各作成者のコメントをクリアします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}コメント作成者コレクションをクリアし、更新した PPT ファイルを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides で構築" title="PPT のコメントをオンラインで削除" description="無料の Aspose.Slides Annotation アプリは、上記のコードと同じ API である [Aspose.Slides for Java](https://products.aspose.com/slides/ja/java/) で構築されています。アプリを開いて、ご自身の PPT ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Annotation を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がコメントを削除するしくみを確認できます。
- PPT ファイルからすべてのコメントを削除します。
- クリーンアップしたファイルをダウンロードします。
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="注釈でサポートされるその他の形式" subTitle="Java を使用すると、他の形式からも注釈を削除できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
