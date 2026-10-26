---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python で ODP プレゼンテーション内のテキストを検索
url: /ja/python-net/search/odp/
description: Python と Aspose.Slides で ODP プレゼンテーション内のテキストを検索します。
keywords: ODP 内のテキスト検索、ODP 内の単語の検出、Python による ODP プレゼンテーションの検索
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python で ODP プレゼンテーション内のテキストを検索" h2="Aspose.Slides で OpenDocument プレゼンテーション内のテキストを見つける Python アプリケーションを構築します。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python による ODP プレゼンテーション内のテキスト検索" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/ja/python-net/) では、[`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) を使用して、各スライドで指定した文字列を含むテキスト フレームを見つけられます。

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP プレゼンテーション内のテキストを検索 – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python で ODP 内のテキストを検索する方法" intro="ODP プレゼンテーション内のテキストを検索するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` で ODP ファイルを開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}スライドを順に処理し、それぞれに対して [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) を呼び出します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}一致した各テキスト フレームの `text` プロパティを読み取ります。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides で構築" title="ODP ファイル内のテキストをオンラインで検索" description="無料の Aspose.Slides Search アプリは、上記のコードと同じ API である [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ja/python-net/) で構築されています。アプリを開いて、ご自身の ODP ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Search を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がテキストを見つけるしくみを確認できます。
- ODP ファイル内をプレーン テキストまたは正規表現で検索できます。
- 検索結果をテキスト ファイルとしてダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="検索に対応するその他の形式" subTitle="Python を使用して、サポートされているその他のプレゼンテーション形式でもテキストを検索できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
