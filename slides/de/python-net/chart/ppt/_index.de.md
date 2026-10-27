---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Diagramme in PPT-Präsentationen mit Python erstellen
url: /de/python-net/chart/ppt/
description: Erstellen und gestalten Sie Diagramme in PPT-Präsentationen mit Python und Aspose.Slides for Python via .NET.
keywords: Diagramm erstellen, Punktdiagramm erstellen, Kreisdiagramm erstellen, Treemap-Diagramm erstellen, Kursdiagramm erstellen, Kastengrafik erstellen, Histogramm erstellen, Trichterdiagramm erstellen, Sunburst-Diagramm, Diagramm mit mehreren Kategorien, PowerPoint-Präsentation, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Diagramme in PPT-Präsentationen mit Python erstellen" h2="Entwickeln Sie Python-Anwendungen, die anpassbare Präsentationsdiagramme mit eigenen Kategorien, Datenreihen, Beschriftungen und Formatierungen erstellen." related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Kreisdiagramm in einer PPT-Präsentation mit Python erstellen" variant="code" %}}

Mit [Aspose.Slides for Python via .NET](/slides/de/python-net/) können Sie ein Kreisdiagramm erstellen, seine Standardkategorien und -reihen ersetzen und seine Beschriftungen und Farben anpassen. Kreisdiagramme eignen sich am besten, um zu zeigen, wie wenige numerische Kategorien zu einem Ganzen beitragen. Weitere Optionen finden Sie unter [Kreisdiagramme in Präsentationen anpassen](https://docs.aspose.com/slides/python-net/pie-chart/).

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kreisdiagramm in einer PPT-Präsentation mit Python erstellen" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So erstellen und gestalten Sie ein Kreisdiagramm in PPT mit Python" intro="Führen Sie diese Schritte aus, um einer PPT-Präsentation ein Kreisdiagramm hinzuzufügen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Erstellen Sie eine `Presentation`-Instanz und greifen Sie über eine Variable `slide` auf die gewünschte Folie zu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie `add_chart` mit `ChartType.PIE` auf, um der Folie ein Kreisdiagramm hinzuzufügen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ersetzen Sie mit `chart_data_workbook` die Standardkategorien und -reihen und konfigurieren Sie anschließend Beschriftungen, Farben und `first_slice_angle`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie `save` mit `SaveFormat.PPT` auf, um die Präsentation im Format PPT zu schreiben.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Entwickelt mit Aspose.Slides" title="PPT-Diagramme online erstellen" description="Die kostenlose App Aspose.Slides Chart basiert auf [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/de/python-net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPT-Dateien leisten kann." button="Aspose.Slides Chart öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Diagramme erstellt, bevor Sie Code schreiben.
- Erstellen Sie ein Diagramm aus Excel- oder Tabellendaten.
- Laden Sie es als PPT-Datei oder als Bild herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für Diagramme" subTitle="Mit Python können Sie auch Diagramme in anderen Formaten erstellen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/chart/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
