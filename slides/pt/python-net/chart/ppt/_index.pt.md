---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Criar gráficos em apresentações PPT com Python
url: /pt/python-net/chart/ppt/
description: Crie e personalize gráficos em apresentações PPT usando Python e o Aspose.Slides for Python via .NET.
keywords: criar gráfico, criar gráfico de dispersão, criar gráfico de pizza, criar gráfico de mapa de árvore, criar gráfico de ações, criar gráfico de caixa estreita, criar histograma, criar gráfico de funil, gráfico de explosão solar, gráfico multicategoria, apresentação do PowerPoint, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Criar gráficos em apresentações PPT com Python" h2="Crie aplicativos Python que geram gráficos de apresentação personalizáveis com suas próprias categorias, séries de dados, rótulos e formatação." related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Criar um gráfico de pizza em uma apresentação PPT com Python" variant="code" %}}

O [Aspose.Slides for Python via .NET](/slides/pt/python-net/) permite criar um gráfico de pizza, substituir suas categorias e séries padrão e personalizar seus rótulos e cores. Gráficos de pizza funcionam melhor para mostrar como poucas categorias numéricas contribuem para um total. Para mais opções, consulte [Personalizar gráficos de pizza em apresentações](https://docs.aspose.com/slides/python-net/pie-chart/).

{{< blocks/products/pf/slides-design-update-10-2026/code title="Criar um gráfico de pizza em uma apresentação PPT com Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como criar e personalizar um gráfico de pizza em PPT com Python" intro="Siga estas etapas para adicionar um gráfico de pizza a uma apresentação PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crie uma instância de `Presentation` e acesse o slide desejado por meio de uma variável `slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame `add_chart` com `ChartType.PIE` para adicionar um gráfico de pizza ao slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use `chart_data_workbook` para substituir as categorias e séries padrão e, em seguida, configure os rótulos, as cores e `first_slice_angle`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame `save` com `SaveFormat.PPT` para gravar a apresentação no formato PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Criado com Aspose.Slides" title="Criar gráficos PPT online" description="O aplicativo gratuito Aspose.Slides Chart é criado com [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pt/python-net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPT." button="Abrir Aspose.Slides Chart" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides cria gráficos antes de escrever código.
- Crie um gráfico a partir de dados do Excel ou de uma tabela.
- Baixe-o como arquivo PPT ou como imagem.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis para gráficos" subTitle="Com Python, você também pode criar gráficos em outros formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/python-net/chart/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
