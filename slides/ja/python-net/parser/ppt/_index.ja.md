---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python で PPT ファイルからテキストを抽出
url: /ja/python-net/parser/ppt/
description: Python で PPT プレゼンテーションからテキストとテキスト書式の詳細を抽出します。
keywords: Python で PPT を解析, PPT パーサー Python, Python で PPT からデータを抽出, Python で PPT からテキストを抽出
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python で PPT プレゼンテーションからテキストを抽出" h2="Aspose.Slides を使用して PowerPoint プレゼンテーションからテキストと書式の詳細を抽出する Python アプリケーションを構築します。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python で PPT プレゼンテーションからテキストを抽出する例" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/ja/python-net/) は、`SlideUtil` の静的メソッド [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) を提供します。このメソッドはプレゼンテーション全体の `TextFrame` オブジェクトを返し、マスター スライドのテキストも含めることができます。次の例では、PPT プレゼンテーションからテキストと関連するフォントの詳細を抽出します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT プレゼンテーションからのテキスト抽出 - Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.ppt") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python で PPT からテキストを抽出する方法" intro="次の手順に従って、PPT ファイルからテキストを抽出します。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` で PPT ファイルを開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil.get_all_text_frames` を呼び出し、マスター スライドを含めるかどうかを指定します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}返された `TextFrame` オブジェクトを順に処理します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}各テキスト フレームの `paragraphs` コレクションを順に処理します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}各段落の `portions` コレクションを順に処理します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}現在の部分の `text` と書式プロパティを読み取ります。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides で構築" title="テキストと画像をオンラインで抽出" description="無料の Aspose.Slides Parser アプリは、上記のコードと同じ API である [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ja/python-net/) で構築されています。アプリを開いて、ご自身の PPT ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Parser を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がファイルをどう読み取るかを確認できます。
- PPT ファイルをアップロードして、テキストと画像を取得できます。
- すべてを 1 つの ZIP アーカイブでダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他の解析可能な形式" subTitle="Python では、サポートされている他のプレゼンテーション形式からもテキストを抽出できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
