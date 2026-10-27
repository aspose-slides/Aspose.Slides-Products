---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Создание диаграмм в презентациях PPT на Python
url: /ru/python-net/chart/ppt/
description: Создавайте и настраивайте диаграммы в презентациях PPT с помощью Python и Aspose.Slides for Python via .NET.
keywords: создание диаграммы, создание точечной диаграммы, создание круговой диаграммы, создание диаграммы дерева, создание биржевой диаграммы, создание диаграммы ящик с усами, создание гистограммы, создание воронкообразной диаграммы, диаграмма солнечные лучи, многоуровневая диаграмма, презентация PowerPoint, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Создание диаграмм в презентациях PPT на Python" h2="Создавайте приложения на Python, которые строят настраиваемые диаграммы презентаций с собственными категориями, рядами данных, подписями и форматированием." related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Создание круговой диаграммы в презентации PPT на Python" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/ru/python-net/) позволяет создать круговую диаграмму, заменить её категории и ряды по умолчанию, а также настроить подписи и цвета. Круговые диаграммы лучше всего подходят, чтобы показать вклад небольшого числа числовых категорий в целое. Дополнительные возможности описаны в статье [Настройка круговых диаграмм в презентациях](https://docs.aspose.com/slides/python-net/pie-chart/).

{{< blocks/products/pf/slides-design-update-10-2026/code title="Создание круговой диаграммы в презентации PPT на Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как создать и настроить круговую диаграмму в PPT на Python" intro="Выполните следующие шаги, чтобы добавить круговую диаграмму в презентацию PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Создайте экземпляр `Presentation` и получите нужный слайд через переменную `slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите `add_chart` с `ChartType.PIE`, чтобы добавить круговую диаграмму на слайд.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}С помощью `chart_data_workbook` замените категории и ряды по умолчанию, а затем настройте подписи, цвета и `first_slice_angle`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите `save` с `SaveFormat.PPT`, чтобы записать презентацию в формате PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Создано на основе Aspose.Slides" title="Создание диаграмм PPT онлайн" description="Бесплатное приложение Aspose.Slides Chart создано на основе [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ru/python-net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPT." button="Открыть Aspose.Slides Chart" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides создаёт диаграммы, ещё до написания кода.
- Постройте диаграмму по данным Excel или таблицы.
- Скачайте её в виде файла PPT или изображения.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для диаграмм" subTitle="С помощью Python можно также создавать диаграммы в других форматах." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/chart/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
