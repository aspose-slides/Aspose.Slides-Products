---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Créer des graphiques dans des présentations PPTX avec Python
url: /fr/python-net/chart/pptx/
description: Créez et personnalisez des graphiques dans des présentations PPTX avec Python et Aspose.Slides for Python via .NET.
keywords: créer un graphique, créer un nuage de points, créer un graphique en secteurs, créer un compartimentage, créer un graphique boursier, créer une boîte à moustaches, créer un histogramme, créer un graphique en entonnoir, graphique en rayons de soleil, graphique multicatégorie, présentation PowerPoint, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Créer des graphiques dans des présentations PPTX avec Python" h2="Créez des applications Python qui génèrent des graphiques de présentation personnalisables avec vos propres catégories, séries de données, étiquettes et mise en forme." related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Créer un graphique en secteurs dans une présentation PPTX avec Python" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/fr/python-net/) vous permet de créer un graphique en secteurs, de remplacer ses catégories et séries par défaut, et de personnaliser ses étiquettes et ses couleurs. Les graphiques en secteurs conviennent le mieux pour montrer la part de quelques catégories numériques dans un total. Pour plus d’options, consultez [Personnaliser les graphiques en secteurs dans les présentations](https://docs.aspose.com/slides/python-net/pie-chart/).

{{< blocks/products/pf/slides-design-update-10-2026/code title="Créer un graphique en secteurs dans une présentation PPTX avec Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment créer et personnaliser un graphique en secteurs dans PPTX avec Python" intro="Suivez ces étapes pour ajouter un graphique en secteurs à une présentation PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Créez une instance `Presentation` et accédez à la diapositive souhaitée via une variable `slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez `add_chart` avec `ChartType.PIE` pour ajouter un graphique en secteurs à la diapositive.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utilisez `chart_data_workbook` pour remplacer les catégories et séries par défaut, puis configurez les étiquettes, les couleurs et `first_slice_angle`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez `save` avec `SaveFormat.PPTX` pour écrire la présentation au format PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Conçu avec Aspose.Slides" title="Créer des graphiques PPTX en ligne" description="L'application gratuite Aspose.Slides Chart est conçue avec [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fr/python-net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPTX." button="Ouvrir Aspose.Slides Chart" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Découvrez comment Aspose.Slides crée des graphiques avant d’écrire du code.
- Créez un graphique à partir de données Excel ou d’un tableau.
- Téléchargez-le sous forme de fichier PPTX ou d’image.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour les graphiques" subTitle="Avec Python, vous pouvez aussi créer des graphiques dans d’autres formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/chart/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
