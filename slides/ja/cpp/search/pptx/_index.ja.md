---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ で PPTX プレゼンテーション内のテキストを検索
url: /ja/cpp/search/pptx/
description: C++ で PPTX プレゼンテーション内のテキストを検索します。Aspose.Slides for C++ を使用して、プレゼンテーション ファイル内のテキストを見つけます。
keywords: PPTX 内の単語検索、PPTX 内のテキストの検出、PPTX プレゼンテーションのテキスト検索
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ で PPTX 内のテキストを検索" h2="Aspose.Slides for C++ を使用すると、Microsoft PowerPoint なしでプレゼンテーション ファイル内のテキストを見つけられます。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ による PPTX プレゼンテーション内のテキスト検索" variant="code" %}}

Aspose.Slides for C++ では、PPTX プレゼンテーション内のテキストを検索できます。`SlideUtil::GetAllTextBoxes` でスライドのテキスト フレームを収集し、そのテキストに目的の語句が含まれているかを確認します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ を使用した PPTX プレゼンテーション内のテキスト検索" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ で PPTX 内のテキストを検索する方法" intro="PPTX プレゼンテーション内のテキストを検索するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで PPTX ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation::get_Slides` で目的のスライドを取得し、[`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/) でそのテキスト フレームを取得します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}各フレームのテキストに目的の語句が含まれているかを確認します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides で構築" title="PPTX ファイル内のテキストをオンラインで検索" description="無料の Aspose.Slides Search アプリは、上記のコードと同じ API である [Aspose.Slides for C++](https://products.aspose.com/slides/ja/cpp/) で構築されています。アプリを開いて、ご自身の PPTX ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Search を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がテキストを見つけるしくみを確認できます。
- PPTX ファイル内をプレーン テキストまたは正規表現で検索できます。
- 検索結果をテキスト ファイルとしてダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="検索に対応するその他の形式" subTitle="C++ では、次の形式でもテキストを検索できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
