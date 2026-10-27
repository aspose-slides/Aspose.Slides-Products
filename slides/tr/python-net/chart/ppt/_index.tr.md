---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python kullanarak PPT sunumlarında grafik oluşturma
url: /tr/python-net/chart/ppt/
description: Python ve Aspose.Slides for Python via .NET ile PPT sunumlarında grafikler oluşturun ve özelleştirin.
keywords: grafik oluşturma, dağılım grafiği oluşturma, pasta grafiği oluşturma, ağaç haritası grafiği oluşturma, hisse senedi grafiği oluşturma, kutu ve bıyık grafiği oluşturma, histogram oluşturma, huni grafiği oluşturma, güneş patlaması grafiği, çok kategorili grafik, PowerPoint sunusu, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python kullanarak PPT sunumlarında grafik oluşturma" h2="Kendi kategorileriniz, veri serileriniz, etiketleriniz ve biçimlendirmenizle özelleştirilebilir sunu grafikleri oluşturan Python uygulamaları geliştirin." related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python ile PPT sunumunda pasta grafiği oluşturma" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/tr/python-net/) ile bir pasta grafiği oluşturabilir, varsayılan kategorilerini ve serilerini değiştirebilir, etiketlerini ve renklerini özelleştirebilirsiniz. Pasta grafikleri, az sayıda sayısal kategorinin bir bütüne katkısını göstermek için en uygun seçenektir. Daha fazla seçenek için [Sunumlarda pasta grafiklerini özelleştirme](https://docs.aspose.com/slides/python-net/pie-chart/) makalesine bakın.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python ile PPT sunumunda pasta grafiği oluşturma" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python ile PPT dosyasında pasta grafiği nasıl oluşturulur ve özelleştirilir" intro="Bir PPT sunumuna pasta grafiği eklemek için bu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Bir `Presentation` örneği oluşturun ve istediğiniz slayta bir `slide` değişkeniyle erişin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Slayta pasta grafiği eklemek için `add_chart` yöntemini `ChartType.PIE` ile çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Varsayılan kategorileri ve serileri değiştirmek için `chart_data_workbook` kullanın, ardından etiketleri, renkleri ve `first_slice_angle` değerini yapılandırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sunumu PPT biçiminde yazmak için `save` yöntemini `SaveFormat.PPT` ile çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Aspose.Slides ile geliştirildi" title="PPT grafiklerini çevrimiçi oluşturma" description="Ücretsiz Aspose.Slides Chart uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/tr/python-net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPT dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Chart uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın grafikleri nasıl oluşturduğunu görün.
- Excel veya tablo verilerinden grafik oluşturun.
- Sonucu PPT dosyası ya da resim olarak indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Grafikler için desteklenen diğer biçimler" subTitle="Python ile diğer biçimlerde de grafik oluşturabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/chart/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
