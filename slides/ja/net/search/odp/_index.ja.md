---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET で ODP プレゼンテーション ファイル内のテキストを検索
url: /ja/net/search/odp/
description: ODP プレゼンテーション内のテキストを検索する C# ソース コード。
keywords: ODP 内のテキスト検索、ODP 内のテキストの検出、ODP プレゼンテーションのテキスト検索
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# で ODP ファイル内のテキストを検索" h2="サーバー側 API でプレゼンテーション内のテキストを見つける .NET アプリを構築します。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# で ODP プレゼンテーション内のテキストを検索" variant="code" %}}

[Aspose.Slides for .NET](/slides/ja/net/) を使用すると、ODP プレゼンテーション内のテキストを検索できます。`SlideUtil.GetAllTextBoxes` でスライドのテキスト フレームを取得し、その `Text` 値に目的の語句が含まれているかを確認します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# で ODP プレゼンテーション内のテキストを検索" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# で ODP プレゼンテーション内のテキストを検索する方法" intro="ODP プレゼンテーション内のテキストを検索するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` で ODP ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation.Slides` から目的のスライドを取得し、変数に代入します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/) でそのテキスト フレームを取得します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}各フレームの `Text` 値に目的の語句が含まれているかを確認します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides で構築" title="ODP ファイル内のテキストをオンラインで検索" description="無料の Aspose.Slides Search アプリは、上記のコードと同じ API である [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net/) で構築されています。アプリを開いて、ご自身の ODP ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Search を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がテキストを見つけるしくみを確認できます。
- ODP ファイル内をプレーン テキストまたは正規表現で検索できます。
- 検索結果をテキスト ファイルとしてダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="検索に対応するその他の形式" subTitle="C# では、次の形式でもテキストを検索できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
