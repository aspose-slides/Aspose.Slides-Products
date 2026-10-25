---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3070
title: .NET で ODP ファイルからテキストを抽出
url: /ja/net/parser/odp/ 
description: .NET で ODP ファイルからテキストを抽出する C# ソース コード。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# で ODP ファイルを解析" h2="サーバー側の .NET API を使用して、ODP ファイルからテキストを抽出し、テキストの書式を確認します。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# で ODP ファイルを解析" %}}

[Aspose.Slides for .NET](/slides/ja/net/) を使用して、ODP プレゼンテーションからテキストを抽出します。[NuGet](https://www.nuget.org/packages/aspose.slides.net) からパッケージをインストールするか、パッケージ マネージャー コンソールで次のコマンドを実行します。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="コマンド" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP ファイルの解析 - C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# で ODP ファイルを解析する方法" intro="[Aspose.Slides for .NET](/slides/ja/net/) API を使用した基本的なドキュメント解析は、わずか数行のコードで実行できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` で ODP ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil.GetAllTextFrames` でテキスト フレームを取得します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}テキスト フレーム、段落、テキスト部分を順に処理します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}必要に応じて `Text`、`FontHeight`、`LatinFont.FontName` プロパティを読み取ります。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要件" intro="サポートされている .NET ランタイムと Aspose.Slides for .NET パッケージへの参照が必要です。Visual Studio または互換性のある他の C# 開発環境を使用できます。" %}}

- .NET Framework、.NET、Mono、または Xamarin 互換の環境
- Visual Studio などの C# 開発環境
- NuGet からインストールした Aspose.Slides for .NET

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides で構築" title="テキストと画像をオンラインで抽出" description="無料の Aspose.Slides Parser アプリは、上記のコードと同じ API である [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net/) で構築されています。アプリを開いて、ご自身の ODP ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Parser を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がファイルをどう読み取るかを確認できます。
- ODP ファイルをアップロードして、テキストと画像を取得できます。
- すべてを 1 つの ZIP アーカイブでダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

ODP files use the OpenDocument Presentation format. A presentation contains slides with text, images, formatting, animations, and other media. Applications that support the OpenDocument format, such as OpenOffice and StarOffice, can open ODP files.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他の解析可能な形式" subTitle="C# では次の形式も解析できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/net/parser/ppt/" name="PPT" description="PowerPoint 97-2003 プレゼンテーション" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/net/parser/pptx/" name="PPTX" description="PowerPoint Open XML プレゼンテーション" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
