---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Creare grafici in presentazioni PPT con Python
url: /it/python-net/chart/ppt/
description: Crea e personalizza grafici in presentazioni PPT con Python e Aspose.Slides for Python via .NET.
keywords: creare grafico, creare grafico a dispersione, creare grafico a torta, creare grafico treemap, creare grafico azionario, creare grafico box and whisker, creare istogramma, creare grafico a imbuto, grafico sunburst, grafico multicategoria, presentazione PowerPoint, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Creare grafici in presentazioni PPT con Python" h2="Sviluppa applicazioni Python che creano grafici di presentazione personalizzabili con categorie, serie di dati, etichette e formattazione personalizzate." related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Creare un grafico a torta in una presentazione PPT con Python" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/it/python-net/) consente di creare un grafico a torta, sostituirne le categorie e le serie predefinite e personalizzarne etichette e colori. I grafici a torta sono ideali per mostrare come poche categorie numeriche contribuiscono a un totale. Per altre opzioni, vedi [Personalizzare i grafici a torta nelle presentazioni](https://docs.aspose.com/slides/python-net/pie-chart/).

{{< blocks/products/pf/slides-design-update-10-2026/code title="Creare un grafico a torta in una presentazione PPT con Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come creare e personalizzare un grafico a torta in PPT con Python" intro="Segui questi passaggi per aggiungere un grafico a torta a una presentazione PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crea un’istanza di `Presentation` e accedi alla diapositiva desiderata tramite una variabile `slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama `add_chart` con `ChartType.PIE` per aggiungere un grafico a torta alla diapositiva.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Usa `chart_data_workbook` per sostituire le categorie e le serie predefinite, quindi configura etichette, colori e `first_slice_angle`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama `save` con `SaveFormat.PPT` per scrivere la presentazione in formato PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Realizzato con Aspose.Slides" title="Creare grafici PPT online" description="L'app gratuita Aspose.Slides Chart è realizzata con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/it/python-net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPT." button="Apri Aspose.Slides Chart" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides crea i grafici prima di scrivere codice.
- Crea un grafico da dati Excel o da una tabella.
- Scaricalo come file PPT o come immagine.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per i grafici" subTitle="Con Python, puoi creare grafici anche in altri formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/chart/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
