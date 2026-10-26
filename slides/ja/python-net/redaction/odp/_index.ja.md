---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python で ODP プレゼンテーションのテキストを墨消し
url: /ja/python-net/redaction/odp/
description: Python で ODP プレゼンテーション内の機密テキストを検索して置換します。
keywords: ODP の墨消し、ODP のテキスト検索と置換、ODP プレゼンテーションの更新
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python で ODP プレゼンテーションのテキストを墨消し" h2="Aspose.Slides で、プレゼンテーション内の機密テキストを検索して置換する Python アプリケーションを構築します。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python による ODP プレゼンテーションのテキストの墨消し" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/ja/python-net/) を使用すると、ODP プレゼンテーション全体の機密テキストを置換できます。`Presentation.replace_text` と `TextSearchOptions` で検索を制御し、変更したプレゼンテーションを保存します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP プレゼンテーションのテキストを墨消し – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.odp") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python で ODP プレゼンテーションのテキストを墨消しする方法" intro="ODP プレゼンテーション内の機密テキストを置換するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` で ODP ファイルを開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) と `TextSearchOptions` を使用して、目的のテキストを置換します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}変更したプレゼンテーションを `SaveFormat.ODP` で保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Aspose.Slides で構築" title="ODP ファイルをオンラインで墨消し" description="無料の Aspose.Slides Redaction アプリは、上記のコードと同じ API である [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ja/python-net/) で構築されています。アプリを開いて、ご自身の ODP ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Redaction を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がテキストを検索して置換するしくみを確認できます。
- ODP ファイル内のテキストを、正規表現も使って検索して置換できます。
- 墨消ししたファイルをダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="墨消しに対応するその他の形式" subTitle="Python を使用して、サポートされているその他のプレゼンテーション形式でもテキストを墨消しできます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
