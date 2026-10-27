---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Diagramok létrehozása PPT bemutatókban Pythonnal
url: /hu/python-net/chart/ppt/
description: Hozzon létre és szabjon testre diagramokat PPT bemutatókban Pythonnal és az Aspose.Slides for Python via .NET segítségével.
keywords: diagram létrehozása, pontdiagram létrehozása, kördiagram létrehozása, fatérkép-diagram létrehozása, árfolyamdiagram létrehozása, dobozdiagram létrehozása, hisztogram létrehozása, tölcsérdiagram létrehozása, napsugárdiagram, többkategóriás diagram, PowerPoint-bemutató, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Diagramok létrehozása PPT bemutatókban Pythonnal" h2="Készítsen Python-alkalmazásokat, amelyek saját kategóriákkal, adatsorokkal, feliratokkal és formázással rendelkező, testreszabható bemutatódiagramokat hoznak létre." related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Kördiagram létrehozása PPT bemutatóban Pythonnal" variant="code" %}}

Az [Aspose.Slides for Python via .NET](/slides/hu/python-net/) segítségével kördiagramot hozhat létre, lecserélheti az alapértelmezett kategóriáit és adatsorait, és testreszabhatja a feliratait és színeit. A kördiagramok akkor a leghasznosabbak, ha azt kell bemutatni, hogyan járul hozzá néhány numerikus kategória az egészhez. További lehetőségekért lásd: [Kördiagramok testreszabása bemutatókban](https://docs.aspose.com/slides/python-net/pie-chart/).

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kördiagram létrehozása PPT bemutatóban Pythonnal" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Kördiagram létrehozása és testreszabása PPT fájlban Pythonnal" intro="Az alábbi lépésekkel kördiagramot adhat egy PPT bemutatóhoz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hozzon létre egy `Presentation` példányt, és érje el a kívánt diát egy `slide` változón keresztül.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg az `add_chart` metódust a `ChartType.PIE` értékkel, hogy kördiagramot adjon a diához.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}A `chart_data_workbook` segítségével cserélje le az alapértelmezett kategóriákat és adatsorokat, majd állítsa be a feliratokat, a színeket és a `first_slice_angle` értéket.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a `save` metódust a `SaveFormat.PPT` értékkel, hogy a bemutatót PPT formátumban írja ki.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Az Aspose.Slides segítségével készült" title="PPT-diagramok létrehozása online" description="Az ingyenes Aspose.Slides Chart alkalmazás az [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hu/python-net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPT fájljaival." button="Aspose.Slides Chart megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan hoz létre diagramokat az Aspose.Slides, mielőtt kódot írna.
- Hozzon létre diagramot Excel- vagy táblázatadatokból.
- Töltse le PPT fájlként vagy képként.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok diagramokhoz" subTitle="Python használatával más formátumokban is létrehozhat diagramokat." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/chart/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
