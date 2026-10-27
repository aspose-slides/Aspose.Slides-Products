---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Vytváření grafů v prezentacích PPT pomocí Pythonu
url: /cs/python-net/chart/ppt/
description: Vytvářejte a přizpůsobujte grafy v prezentacích PPT pomocí Pythonu a Aspose.Slides for Python via .NET.
keywords: vytvoření grafu, vytvoření bodového grafu, vytvoření výsečového grafu, vytvoření stromové mapy, vytvoření burzovního grafu, vytvoření krabicového grafu, vytvoření histogramu, vytvoření trychtýřového grafu, paprskový graf, graf s více kategoriemi, prezentace PowerPoint, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Vytváření grafů v prezentacích PPT pomocí Pythonu" h2="Vytvářejte aplikace v Pythonu, které vytvářejí přizpůsobitelné grafy prezentací s vlastními kategoriemi, datovými řadami, popisky a formátováním." related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Vytvoření výsečového grafu v prezentaci PPT pomocí Pythonu" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/cs/python-net/) umožňuje vytvořit výsečový graf, nahradit jeho výchozí kategorie a řady a přizpůsobit popisky a barvy. Výsečové grafy se nejlépe hodí k zobrazení toho, jak malý počet číselných kategorií tvoří celek. Další možnosti najdete v článku [Přizpůsobení výsečových grafů v prezentacích](https://docs.aspose.com/slides/python-net/pie-chart/).

{{< blocks/products/pf/slides-design-update-10-2026/code title="Vytvoření výsečového grafu v prezentaci PPT pomocí Pythonu" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak vytvořit a přizpůsobit výsečový graf v PPT pomocí Pythonu" intro="Podle těchto kroků přidáte výsečový graf do prezentace PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vytvořte instanci `Presentation` a získejte požadovaný snímek pomocí proměnné `slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte `add_chart` s `ChartType.PIE` a přidejte na snímek výsečový graf.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pomocí `chart_data_workbook` nahraďte výchozí kategorie a řady a poté nakonfigurujte popisky, barvy a `first_slice_angle`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte `save` se `SaveFormat.PPT` a zapište prezentaci ve formátu PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Vytvořeno pomocí Aspose.Slides" title="Vytváření grafů PPT online" description="Bezplatná aplikace Aspose.Slides Chart je vytvořena pomocí [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/cs/python-net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPT." button="Otevřít Aspose.Slides Chart" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides vytváří grafy, ještě než napíšete kód.
- Vytvořte graf z dat v Excelu nebo z tabulky.
- Stáhněte jej jako soubor PPT nebo jako obrázek.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro grafy" subTitle="Pomocí Pythonu můžete vytvářet grafy i v dalších formátech." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/chart/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
