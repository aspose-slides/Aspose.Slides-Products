---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 在 PPT 演示文稿中创建图表
url: /zh/python-net/chart/ppt/
description: 使用 Python 和 Aspose.Slides for Python via .NET 在 PPT 演示文稿中创建并自定义图表。
keywords: 创建图表, 创建散点图, 创建饼图, 创建树状图, 创建股价图, 创建箱形图, 创建直方图, 创建漏斗图, 旭日图, 多类别图表, PowerPoint 演示文稿, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 在 PPT 演示文稿中创建图表" h2="构建 Python 应用程序，使用您自己的类别、数据系列、标签和格式创建可自定义的演示文稿图表。" related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 在 PPT 演示文稿中创建饼图" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/zh/python-net/) 可让您创建饼图、替换其默认类别和系列，并自定义标签和颜色。饼图最适合展示少量数值类别在整体中所占的比例。有关更多选项，请参阅[在演示文稿中自定义饼图](https://docs.aspose.com/slides/python-net/pie-chart/)。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Python 在 PPT 演示文稿中创建饼图" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 在 PPT 中创建并自定义饼图" intro="按照以下步骤向 PPT 演示文稿添加饼图。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}创建 `Presentation` 实例，并通过 `slide` 变量访问所需的幻灯片。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `ChartType.PIE` 调用 `add_chart`，向幻灯片添加饼图。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `chart_data_workbook` 替换默认类别和系列，然后配置标签、颜色和 `first_slice_angle`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.PPT` 调用 `save`，以 PPT 格式写入演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="基于 Aspose.Slides 构建" title="在线创建 PPT 图表" description="免费的 Aspose.Slides Chart 应用基于 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh/python-net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPT 文件。" button="打开 Aspose.Slides Chart" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先了解 Aspose.Slides 如何创建图表。
- 根据 Excel 或表格数据创建图表。
- 将其下载为 PPT 文件或图像。
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="图表支持的其他格式" subTitle="使用 Python，您还可以在其他格式中创建图表。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/chart/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
