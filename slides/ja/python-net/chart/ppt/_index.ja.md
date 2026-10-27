---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python で PPT プレゼンテーションにグラフを作成
url: /ja/python-net/chart/ppt/
description: Python と Aspose.Slides for Python via .NET を使用して、PPT プレゼンテーションにグラフを作成し、カスタマイズします。
keywords: グラフの作成, 散布図の作成, 円グラフの作成, ツリーマップの作成, 株価チャートの作成, 箱ひげ図の作成, ヒストグラムの作成, じょうごグラフの作成, サンバースト図, 複数カテゴリのグラフ, PowerPoint プレゼンテーション, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python で PPT プレゼンテーションにグラフを作成" h2="独自のカテゴリ、データ系列、ラベル、書式でカスタマイズ可能なプレゼンテーション グラフを作成する Python アプリケーションを構築します。" related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python で PPT プレゼンテーションに円グラフを作成" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/ja/python-net/) を使用すると、円グラフを作成し、既定のカテゴリと系列を置き換え、ラベルと色をカスタマイズできます。円グラフは、少数の数値カテゴリが全体にどれだけ寄与しているかを示すのに最適です。その他のオプションについては、[プレゼンテーションの円グラフをカスタマイズする](https://docs.aspose.com/slides/python-net/pie-chart/) を参照してください。

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python で PPT プレゼンテーションに円グラフを作成" >}}
```python
with slides.Presentation() as presentation:
    slide = presentation.slides[0]
    chart = slide.shapes.add_chart(slides.charts.ChartType.PIE, 100, 100, 400, 400)

    chart.has_title = True
    chart.chart_title.add_text_frame_for_overriding("Quarterly Sales")
    chart.chart_title.height = 20

    worksheet_index = 0
    workbook = chart.chart_data.chart_data_workbook
    chart.chart_data.series.clear()
    chart.chart_data.categories.clear()

    categories = ("First Quarter", "Second Quarter", "Third Quarter")
    values = (20, 50, 30)

    for row_index, category in enumerate(categories, start=1):
        category_cell = workbook.get_cell(worksheet_index, row_index, 0, category)
        chart.chart_data.categories.add(category_cell)

    series_name_cell = workbook.get_cell(worksheet_index, 0, 1, "Sales")
    series = chart.chart_data.series.add(series_name_cell, chart.type)

    for row_index, value in enumerate(values, start=1):
        value_cell = workbook.get_cell(worksheet_index, row_index, 1, value)
        series.data_points.add_data_point_for_pie_series(value_cell)

    series.labels.default_data_label_format.show_percentage = True
    series.parent_series_group.is_color_varied = True
    series.parent_series_group.first_slice_angle = 180

    fill_colors = (drawing.Color.orange, drawing.Color.blue_violet, drawing.Color.yellow_green)

    for data_point_index, fill_color in enumerate(fill_colors):
        data_point = series.data_points[data_point_index]
        data_point.format.fill.fill_type = slides.FillType.SOLID
        data_point.format.fill.solid_fill_color.color = fill_color

    presentation.save("pie-chart.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python で PPT に円グラフを作成してカスタマイズする方法" intro="PPT プレゼンテーションに円グラフを追加するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` インスタンスを作成し、`slide` 変数を通じて目的のスライドにアクセスします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ChartType.PIE` を指定して `add_chart` を呼び出し、スライドに円グラフを追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`chart_data_workbook` を使用して既定のカテゴリと系列を置き換え、ラベル、色、`first_slice_angle` を設定します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.PPT` を指定して `save` を呼び出し、プレゼンテーションを PPT 形式で書き込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Aspose.Slides で構築" title="PPT グラフをオンラインで作成" description="無料の Aspose.Slides Chart アプリは、上記のコードと同じ API である [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ja/python-net/) で構築されています。アプリを開いて、ご自身の PPT ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Chart を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がグラフを作成するしくみを確認できます。
- Excel またはテーブルのデータからグラフを作成します。
- PPT ファイルまたは画像としてダウンロードします。
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="グラフでサポートされるその他の形式" subTitle="Python を使用すると、他の形式でもグラフを作成できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/chart/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
