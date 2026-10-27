---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Python で PPT からコメントを削除
url: /ja/python-net/annotation/ppt/ 
description: Aspose.Slides for Python via .NET を使用して、Python で PPT プレゼンテーションからコメントとコメント作成者を削除します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python で PPT からコメントとコメント作成者を削除" h2="Aspose.Slides for Python via .NET を使用して、プレゼンテーションのコメントと関連する作成者を削除します。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python で PPT からコメントを削除" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/ja/python-net/) を使用すると、PPT プレゼンテーションに保存されているコメントとコメント作成者にアクセスできます。`Presentation` でファイルを読み込み、各作成者の `comments` コレクションと `comment_authors` をクリアして、結果を PPT 形式で保存します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python で PPT からコメントを削除" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python で PPT からコメントを削除する方法" intro="PPT プレゼンテーションからすべてのコメントとコメント作成者を削除するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/) をインストールします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` で PPT ファイルを開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`comment_authors` を反復処理し、各作成者の `comments` コレクションをクリアします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`comment_authors` コレクションをクリアします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.PPT` を指定して `save` を呼び出し、更新した PPT プレゼンテーションを書き込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides で構築" title="PPT のコメントをオンラインで削除" description="無料の Aspose.Slides Annotation アプリは、上記のコードと同じ API である [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ja/python-net/) で構築されています。アプリを開いて、ご自身の PPT ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Annotation を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がコメントを削除するしくみを確認できます。
- PPT ファイルからすべてのコメントを削除します。
- クリーンアップしたファイルをダウンロードします。
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="注釈でサポートされるその他の形式" subTitle="Python を使用すると、他の形式からも注釈を削除できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
