---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tworzenie wykresów w prezentacjach PPTX za pomocą Pythona
url: /pl/python-net/chart/pptx/
description: Twórz i dostosowuj wykresy w prezentacjach PPTX za pomocą Pythona i Aspose.Slides for Python via .NET.
keywords: tworzenie wykresu, tworzenie wykresu punktowego, tworzenie wykresu kołowego, tworzenie wykresu mapy drzewa, tworzenie wykresu giełdowego, tworzenie wykresu pudełkowego, tworzenie histogramu, tworzenie wykresu lejkowego, wykres pierścieniowy wielopoziomowy, wykres wielokategorialny, prezentacja PowerPoint, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tworzenie wykresów w prezentacjach PPTX za pomocą Pythona" h2="Twórz aplikacje w Pythonie, które tworzą konfigurowalne wykresy prezentacji z własnymi kategoriami, seriami danych, etykietami i formatowaniem." related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tworzenie wykresu kołowego w prezentacji PPTX za pomocą Pythona" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/pl/python-net/) pozwala utworzyć wykres kołowy, zastąpić jego domyślne kategorie i serie oraz dostosować etykiety i kolory. Wykresy kołowe najlepiej sprawdzają się, gdy trzeba pokazać, jak kilka kategorii liczbowych składa się na całość. Więcej opcji znajdziesz w artykule [Dostosowywanie wykresów kołowych w prezentacjach](https://docs.aspose.com/slides/python-net/pie-chart/).

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tworzenie wykresu kołowego w prezentacji PPTX za pomocą Pythona" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak utworzyć i dostosować wykres kołowy w PPTX za pomocą Pythona" intro="Wykonaj poniższe kroki, aby dodać wykres kołowy do prezentacji PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utwórz wystąpienie `Presentation` i uzyskaj dostęp do wybranego slajdu za pomocą zmiennej `slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj `add_chart` z `ChartType.PIE`, aby dodać wykres kołowy do slajdu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Użyj `chart_data_workbook`, aby zastąpić domyślne kategorie i serie, a następnie skonfiguruj etykiety, kolory i `first_slice_angle`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj `save` z `SaveFormat.PPTX`, aby zapisać prezentację w formacie PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Zbudowano z Aspose.Slides" title="Tworzenie wykresów PPTX online" description="Bezpłatna aplikacja Aspose.Slides Chart została zbudowana z użyciem [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pl/python-net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPTX." button="Otwórz Aspose.Slides Chart" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides tworzy wykresy, zanim napiszesz kod.
- Utwórz wykres z danych Excel lub z tabeli.
- Pobierz go jako plik PPTX lub jako obraz.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty wykresów" subTitle="Za pomocą Pythona możesz także tworzyć wykresy w innych formatach." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/chart/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
