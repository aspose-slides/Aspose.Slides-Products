---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET で ODP プレゼンテーション ファイルを墨消し
url: /ja/net/redaction/odp/
description: ODP プレゼンテーション内のテキストを検索して置換する C# ソース コード。
keywords: ODP の墨消し、ODP のテキスト検索と置換、ODP プレゼンテーションの更新
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# で ODP ファイルを墨消し" h2="サーバー側 API でプレゼンテーション内のテキストを検索して置換する .NET アプリを構築します。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# で ODP プレゼンテーションを墨消し" variant="code" %}}

[Aspose.Slides for .NET](/slides/ja/net/) を使用すると、ODP プレゼンテーション内のテキストを検索して置換できます。`Presentation.ReplaceText` と `TextSearchOptions` で検索を制御し、変更したプレゼンテーションを保存します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# で ODP プレゼンテーションを墨消し" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# で ODP プレゼンテーションを墨消しする方法" intro="ODP プレゼンテーション内のテキストを置換するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` で ODP ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) と `TextSearchOptions` を使用して、目的のテキストを置換します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}変更したプレゼンテーションを `SaveFormat.Odp` で保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Aspose.Slides で構築" title="ODP ファイルをオンラインで墨消し" description="無料の Aspose.Slides Redaction アプリは、上記のコードと同じ API である [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net/) で構築されています。アプリを開いて、ご自身の ODP ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Redaction を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がテキストを検索して置換するしくみを確認できます。
- ODP ファイル内のテキストを、正規表現も使って検索して置換できます。
- 墨消ししたファイルをダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="墨消しに対応するその他の形式" subTitle="C# では、次の形式も墨消しできます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
