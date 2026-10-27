---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7100
title: .NET で PPTX グラフを作成
url: /ja/net/chart/pptx/ 
description: Aspose.Slides for .NET を使用して、C# で PPTX プレゼンテーションにグラフを作成します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# で PPTX グラフを作成" h2="サーバー側の Aspose.Slides API を使用して、プレゼンテーション ファイルにグラフを作成する .NET アプリケーションを構築します。"
  apiHomeLink="/slides/net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/net/"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# で PPTX グラフを作成" %}}

[Aspose.Slides for .NET](/slides/ja/net/) を使用して、PPTX プレゼンテーションにグラフを作成します。[NuGet](https://www.nuget.org/packages/Aspose.Slides.NET/) からパッケージをインストールするか、パッケージ マネージャー コンソールで次のコマンドを使用してください。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="コマンド" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX にグラフを作成 – C#" >}}
```cs
using var presentation = new Presentation();

var slide = presentation.Slides[0];
var chart = slide.Shapes.AddChart(ChartType.ScatterWithSmoothLines, 0, 0, 400, 400);
var defaultWorksheetIndex = 0;
var chartDataWorkbook = chart.ChartData.ChartDataWorkbook;

chart.ChartData.Series.Clear();
chart.ChartData.Series.Add(chartDataWorkbook.GetCell(defaultWorksheetIndex, 1, 1, "Series 1"), chart.Type);
chart.ChartData.Series.Add(chartDataWorkbook.GetCell(defaultWorksheetIndex, 1, 3, "Series 2"), chart.Type);

var firstSeries = chart.ChartData.Series[0];
firstSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 2, 1, 1),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 2, 2, 3));
firstSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 3, 1, 2),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 3, 2, 10));
firstSeries.Type = ChartType.ScatterWithStraightLinesAndMarkers;
firstSeries.Marker.Size = 10;
firstSeries.Marker.Symbol = MarkerStyleType.Star;

var secondSeries = chart.ChartData.Series[1];
secondSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 2, 3, 5),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 2, 4, 2));
secondSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 3, 3, 3),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 3, 4, 1));
secondSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 4, 3, 2),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 4, 4, 2));
secondSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 5, 3, 5),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 5, 4, 1));
secondSeries.Marker.Size = 10;
secondSeries.Marker.Symbol = MarkerStyleType.Circle;

presentation.Save("AsposeScatterChart.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# で PPTX ファイルにグラフを作成する方法" intro="Aspose.Slides for .NET を使用すると、数行のコードで PPTX プレゼンテーションにグラフを作成できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` オブジェクトを作成します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`presentation.Slides` から対象のスライドを取得します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`AddChart` メソッドを呼び出して、スライドにグラフを追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`IChartDataWorkbook` を使用して、グラフの系列とデータ ポイントを追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}プレゼンテーションを PPTX ファイルとして保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要件" intro="Aspose.Slides for .NET は主要なプラットフォームとオペレーティング システムをサポートしています。環境が次の前提条件を満たしていることを確認してください。" %}}

- .NET または Mono がインストールされた、サポート対象のオペレーティング システム。
- Microsoft Visual Studio などの開発環境。
- プロジェクトで参照されている Aspose.Slides for .NET。NuGet からインストールするか、上の [ダウンロード] ボタンからダウンロードしてください。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Aspose.Slides で構築" title="PPTX グラフをオンラインで作成" description="無料の Aspose.Slides Chart アプリは、上記のコードと同じ API である [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net/) で構築されています。アプリを開いて、ご自身の PPTX ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Chart を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がグラフを作成するしくみを確認できます。
- Excel またはテーブルのデータからグラフを作成します。
- PPTX ファイルまたは画像としてダウンロードします。
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

拡張子が PPTX のファイルは、Office Open XML プレゼンテーション形式を使用します。PPTX ファイルには、テキスト、グラフ、画像、書式、アニメーションなどのプレゼンテーション コンテンツを含むスライドを格納できます。

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="グラフでサポートされるその他の形式" subTitle="C# を使用すると、他の形式でもグラフを作成できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/net/chart/ppt/" name="PPT" description="PowerPoint 97-2003 プレゼンテーション" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
