---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Crear gráficos en presentaciones PPTX con Python
url: /es/python-net/chart/pptx/
description: Cree y personalice gráficos en presentaciones PPTX con Python y Aspose.Slides for Python via .NET.
keywords: crear gráfico, crear gráfico de dispersión, crear gráfico circular, crear gráfico de rectángulos, crear gráfico de cotizaciones, crear diagrama de caja y bigotes, crear histograma, crear gráfico de embudo, gráfico de proyección solar, gráfico multicategoría, presentación de PowerPoint, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Crear gráficos en presentaciones PPTX con Python" h2="Cree aplicaciones Python que generen gráficos de presentación personalizables con sus propias categorías, series de datos, etiquetas y formato." related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Crear un gráfico circular en una presentación PPTX con Python" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/es/python-net/) le permite crear un gráfico circular, reemplazar sus categorías y series predeterminadas, y personalizar sus etiquetas y colores. Los gráficos circulares son ideales para mostrar cómo unas pocas categorías numéricas contribuyen a un total. Para más opciones, consulte [Personalizar gráficos circulares en presentaciones](https://docs.aspose.com/slides/python-net/pie-chart/).

{{< blocks/products/pf/slides-design-update-10-2026/code title="Crear un gráfico circular en una presentación PPTX con Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo crear y personalizar un gráfico circular en PPTX con Python" intro="Siga estos pasos para agregar un gráfico circular a una presentación PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cree una instancia de `Presentation` y acceda a la diapositiva deseada mediante una variable `slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame a `add_chart` con `ChartType.PIE` para agregar un gráfico circular a la diapositiva.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use `chart_data_workbook` para reemplazar las categorías y series predeterminadas y, después, configure las etiquetas, los colores y `first_slice_angle`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame a `save` con `SaveFormat.PPTX` para escribir la presentación en formato PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Creado con Aspose.Slides" title="Crear gráficos PPTX en línea" description="La aplicación gratuita Aspose.Slides Chart está creada con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/es/python-net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPTX." button="Abrir Aspose.Slides Chart" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides crea gráficos antes de escribir código.
- Cree un gráfico a partir de datos de Excel o de una tabla.
- Descárguelo como archivo PPTX o como imagen.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles para gráficos" subTitle="Con Python, también puede crear gráficos en otros formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/chart/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
