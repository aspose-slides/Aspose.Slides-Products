---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 在 PPT 簡報中建立圖表
url: /zh-hant/python-net/chart/ppt/
description: 使用 Python 與 Aspose.Slides for Python via .NET 在 PPT 簡報中建立並自訂圖表。
keywords: 建立圖表, 建立散佈圖, 建立圓形圖, 建立矩形式樹狀結構圖, 建立股票圖, 建立盒鬚圖, 建立長條分佈圖, 建立漏斗圖, 放射環狀圖, 多類別圖表, PowerPoint 簡報, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 在 PPT 簡報中建立圖表" h2="建置 Python 應用程式，使用您自己的類別、資料數列、標籤與格式設定建立可自訂的簡報圖表。" related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 在 PPT 簡報中建立圓形圖" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/zh-hant/python-net/) 可讓您建立圓形圖、取代其預設類別與數列，並自訂標籤與色彩。圓形圖最適合呈現少數數值類別在整體中所佔的比例。如需更多選項，請參閱[在簡報中自訂圓形圖](https://docs.aspose.com/slides/python-net/pie-chart/)。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Python 在 PPT 簡報中建立圓形圖" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 在 PPT 中建立並自訂圓形圖" intro="依照下列步驟將圓形圖新增至 PPT 簡報。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}建立 `Presentation` 執行個體，並透過 `slide` 變數存取所需的投影片。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `ChartType.PIE` 呼叫 `add_chart`，將圓形圖新增至投影片。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `chart_data_workbook` 取代預設類別與數列，然後設定標籤、色彩與 `first_slice_angle`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.PPT` 呼叫 `save`，以 PPT 格式寫入簡報。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="以 Aspose.Slides 建置" title="線上建立 PPT 圖表" description="免費的 Aspose.Slides Chart 應用程式以 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh-hant/python-net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPT 檔案。" button="開啟 Aspose.Slides Chart" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先了解 Aspose.Slides 如何建立圖表。
- 根據 Excel 或表格資料建立圖表。
- 將其下載為 PPT 檔案或影像。
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="圖表支援的其他格式" subTitle="使用 Python，您也可以在其他格式中建立圖表。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/chart/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
