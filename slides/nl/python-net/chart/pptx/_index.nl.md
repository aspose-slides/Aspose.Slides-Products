---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Grafieken maken in PPTX-presentaties met Python
url: /nl/python-net/chart/pptx/
description: Maak en pas grafieken aan in PPTX-presentaties met Python en Aspose.Slides for Python via .NET.
keywords: grafiek maken, spreidingsgrafiek maken, cirkelgrafiek maken, treemapgrafiek maken, koersgrafiek maken, box-and-whiskergrafiek maken, histogram maken, trechtergrafiek maken, zonnestraalgrafiek, grafiek met meerdere categorieën, PowerPoint-presentatie, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Grafieken maken in PPTX-presentaties met Python" h2="Bouw Python-toepassingen die aanpasbare presentatiegrafieken maken met uw eigen categorieën, gegevensreeksen, labels en opmaak." related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Een cirkelgrafiek maken in een PPTX-presentatie met Python" variant="code" %}}

Met [Aspose.Slides for Python via .NET](/slides/nl/python-net/) kunt u een cirkelgrafiek maken, de standaardcategorieën en -reeksen vervangen en de labels en kleuren aanpassen. Cirkelgrafieken zijn het meest geschikt om te laten zien hoe een klein aantal numerieke categorieën bijdraagt aan een geheel. Zie [Cirkelgrafieken in presentaties aanpassen](https://docs.aspose.com/slides/python-net/pie-chart/) voor meer opties.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Een cirkelgrafiek maken in een PPTX-presentatie met Python" >}}
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

    presentation.save("pie-chart.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Een cirkelgrafiek maken en aanpassen in PPTX met Python" intro="Volg deze stappen om een cirkelgrafiek aan een PPTX-presentatie toe te voegen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Maak een `Presentation`-instantie en open de gewenste dia via een variabele `slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep `add_chart` aan met `ChartType.PIE` om een cirkelgrafiek aan de dia toe te voegen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gebruik `chart_data_workbook` om de standaardcategorieën en -reeksen te vervangen en configureer daarna de labels, kleuren en `first_slice_angle`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep `save` aan met `SaveFormat.PPTX` om de presentatie in PPTX-formaat te schrijven.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Gebouwd met Aspose.Slides" title="PPTX-grafieken online maken" description="De gratis app Aspose.Slides Chart is gebouwd met [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/nl/python-net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPTX-bestanden." button="Aspose.Slides Chart openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides grafieken maakt voordat u code schrijft.
- Maak een grafiek van Excel- of tabelgegevens.
- Download deze als PPTX-bestand of als afbeelding.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor grafieken" subTitle="Met Python kunt u ook grafieken maken in andere formaten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/chart/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
