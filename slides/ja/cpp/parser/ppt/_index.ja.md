---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 2780
title: C++ で PPT プレゼンテーションからテキストを抽出
url: /ja/cpp/parser/ppt/ 
description: C++ で PPT プレゼンテーションからテキストを抽出します。Aspose.Slides for C++ を使用して、スライド、テキスト フレーム、段落、テキスト部分を解析します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ で PPT プレゼンテーションを解析" h2="Aspose.Slides for C++ を使用すると、Microsoft PowerPoint なしでプレゼンテーション スライドからテキストを抽出できます。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ で PPT ファイルを解析" %}}

Aspose.Slides for C++ を使用して PPT プレゼンテーション ファイルを解析し、スライドからテキストを抽出します。この API は `SlideUtil::GetAllTextBoxes`、`ITextFrame`、`IParagraph`、`IPortion` を通じてスライドのテキストを提供するため、Microsoft PowerPoint を自動化せずにテキストを読み取れます。NuGet から [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) パッケージをインストールするか、パッケージ マネージャー コンソールで次のコマンドを使用します。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="コマンド" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT ファイルの解析 - C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ で PPT ファイルを解析する方法" intro="Aspose.Slides for C++ で PPT ファイルからテキストを抽出します。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで PPT ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil::GetAllTextBoxes` で最初のスライドの `ITextFrame` オブジェクトを取得します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ITextFrame` オブジェクトを順に処理します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}各 `ITextFrame` 内の `IParagraph` オブジェクトを順に処理します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}各 `IParagraph` 内の `IPortion` オブジェクトを順に処理します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`get_Text` でテキストを読み取ります。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要件" intro="Aspose.Slides for C++ は主要なデスクトップおよびサーバー プラットフォームをサポートしています。プロジェクトが次の前提条件を満たしていることを確認してください。" %}}

-  サポートされている C++ ランタイムを備えた Microsoft Windows、Linux、macOS、またはその他の互換 OS。
-  プロジェクトで参照されている Aspose.Slides for C++ ライブラリ。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides で構築" title="テキストと画像をオンラインで抽出" description="無料の Aspose.Slides Parser アプリは、上記のコードと同じ API である [Aspose.Slides for C++](https://products.aspose.com/slides/ja/cpp/) で構築されています。アプリを開いて、ご自身の PPT ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Parser を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がファイルをどう読み取るかを確認できます。
- PPT ファイルをアップロードして、テキストと画像を取得できます。
- すべてを 1 つの ZIP アーカイブでダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

PPT ファイルは、Microsoft PowerPoint 97-2003 のプレゼンテーション ファイルです。スライド、テキスト、画像、マルチメディア、埋め込みオブジェクトを、Open XML 形式の PPTX 以前に使われていた PowerPoint のバイナリ ファイル形式で格納します。

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他の解析可能な形式" subTitle="C++ では他のプレゼンテーション形式も解析できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/parser/odp/" name="ODP" description="OpenDocument プレゼンテーション" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/parser/pptx/" name="PPTX" description="PowerPoint Open XML プレゼンテーション" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
