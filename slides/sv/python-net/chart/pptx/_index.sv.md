---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Skapa diagram i PPTX-presentationer med Python
url: /sv/python-net/chart/pptx/
description: Skapa och anpassa diagram i PPTX-presentationer med Python och Aspose.Slides for Python via .NET.
keywords: skapa diagram, skapa punktdiagram, skapa cirkeldiagram, skapa treemap-diagram, skapa börsdiagram, skapa låddiagram, skapa histogram, skapa trattdiagram, solstrålediagram, diagram med flera kategorier, PowerPoint-presentation, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Skapa diagram i PPTX-presentationer med Python" h2="Bygg Python-program som skapar anpassningsbara presentationsdiagram med egna kategorier, dataserier, etiketter och formatering." related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Skapa ett cirkeldiagram i en PPTX-presentation med Python" variant="code" %}}

Med [Aspose.Slides for Python via .NET](/slides/sv/python-net/) kan du skapa ett cirkeldiagram, ersätta dess standardkategorier och -serier och anpassa etiketter och färger. Cirkeldiagram passar bäst för att visa hur ett fåtal numeriska kategorier bidrar till en helhet. Fler alternativ finns i [Anpassa cirkeldiagram i presentationer](https://docs.aspose.com/slides/python-net/pie-chart/).

{{< blocks/products/pf/slides-design-update-10-2026/code title="Skapa ett cirkeldiagram i en PPTX-presentation med Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så skapar och anpassar du ett cirkeldiagram i PPTX med Python" intro="Följ de här stegen för att lägga till ett cirkeldiagram i en PPTX-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skapa en `Presentation`-instans och kom åt önskad bild via en variabel `slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa `add_chart` med `ChartType.PIE` för att lägga till ett cirkeldiagram i bilden.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Använd `chart_data_workbook` för att ersätta standardkategorierna och -serierna och konfigurera sedan etiketter, färger och `first_slice_angle`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa `save` med `SaveFormat.PPTX` för att skriva presentationen i PPTX-format.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Byggd med Aspose.Slides" title="Skapa PPTX-diagram online" description="Den kostnadsfria appen Aspose.Slides Chart är byggd med [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/sv/python-net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPTX-filer." button="Öppna Aspose.Slides Chart" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides skapar diagram innan du skriver kod.
- Skapa ett diagram från Excel- eller tabelldata.
- Ladda ned det som en PPTX-fil eller en bild.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för diagram" subTitle="Med Python kan du även skapa diagram i andra format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/python-net/chart/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
