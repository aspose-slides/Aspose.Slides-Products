---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Buat Diagram dalam Presentasi PPT Menggunakan Python
url: /id/python-net/chart/ppt/
description: Buat dan sesuaikan diagram dalam presentasi PPT menggunakan Python dan Aspose.Slides for Python via .NET.
keywords: buat diagram, buat diagram sebar, buat diagram lingkaran, buat diagram treemap, buat diagram saham, buat diagram kotak dan garis, buat histogram, buat diagram corong, diagram sunburst, diagram multikategori, presentasi PowerPoint, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Buat Diagram dalam Presentasi PPT Menggunakan Python" h2="Bangun aplikasi Python yang membuat diagram presentasi yang dapat disesuaikan dengan kategori, seri data, label, dan pemformatan Anda sendiri." related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Buat Diagram Lingkaran dalam Presentasi PPT dengan Python" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/id/python-net/) memungkinkan Anda membuat diagram lingkaran, mengganti kategori dan seri default-nya, serta menyesuaikan label dan warnanya. Diagram lingkaran paling cocok untuk menunjukkan kontribusi sejumlah kecil kategori numerik terhadap keseluruhan. Untuk opsi lainnya, lihat [Menyesuaikan Diagram Lingkaran dalam Presentasi](https://docs.aspose.com/slides/python-net/pie-chart/).

{{< blocks/products/pf/slides-design-update-10-2026/code title="Buat Diagram Lingkaran dalam Presentasi PPT dengan Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Membuat dan Menyesuaikan Diagram Lingkaran di PPT dengan Python" intro="Ikuti langkah-langkah ini untuk menambahkan diagram lingkaran ke presentasi PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buat instans `Presentation` dan akses slide yang diinginkan melalui variabel `slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil `add_chart` dengan `ChartType.PIE` untuk menambahkan diagram lingkaran ke slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gunakan `chart_data_workbook` untuk mengganti kategori dan seri default, lalu konfigurasikan label, warna, dan `first_slice_angle`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil `save` dengan `SaveFormat.PPT` untuk menulis presentasi dalam format PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Dibuat dengan Aspose.Slides" title="Buat Diagram PPT Secara Online" description="Aplikasi Aspose.Slides Chart gratis dibuat dengan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/id/python-net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPT Anda sendiri." button="Buka Aspose.Slides Chart" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides membuat diagram sebelum Anda menulis kode.
- Buat diagram dari data Excel atau tabel.
- Unduh sebagai file PPT atau gambar.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Diagram" subTitle="Dengan Python, Anda juga dapat membuat diagram dalam format lain." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/chart/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
