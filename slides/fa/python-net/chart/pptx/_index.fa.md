---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ایجاد نمودار در ارائه‌های PPTX با Python
url: /fa/python-net/chart/pptx/
description: با Python و Aspose.Slides for Python via .NET در ارائه‌های PPTX نمودار ایجاد و سفارشی کنید.
keywords: ایجاد نمودار، ایجاد نمودار پراکندگی، ایجاد نمودار دایره‌ای، ایجاد نمودار نقشه درختی، ایجاد نمودار سهام، ایجاد نمودار جعبه‌ای، ایجاد هیستوگرام، ایجاد نمودار قیفی، نمودار آفتابی، نمودار چنددسته‌ای، ارائه PowerPoint، Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ایجاد نمودار در ارائه‌های PPTX با Python" h2="برنامه‌های Python بسازید که نمودارهای ارائه قابل‌سفارشی‌سازی را با دسته‌ها، سری‌های داده، برچسب‌ها و قالب‌بندی دلخواه شما ایجاد می‌کنند." related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ایجاد نمودار دایره‌ای در ارائه PPTX با Python" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/fa/python-net/) به شما امکان می‌دهد نمودار دایره‌ای ایجاد کنید، دسته‌ها و سری‌های پیش‌فرض آن را جایگزین کنید و برچسب‌ها و رنگ‌های آن را سفارشی کنید. نمودارهای دایره‌ای برای نشان دادن سهم تعداد کمی دسته عددی از یک کل مناسب‌ترند. برای گزینه‌های بیشتر، [سفارشی‌سازی نمودارهای دایره‌ای در ارائه‌ها](https://docs.aspose.com/slides/python-net/pie-chart/) را ببینید.

{{< blocks/products/pf/slides-design-update-10-2026/code title="ایجاد نمودار دایره‌ای در ارائه PPTX با Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="چگونه با Python در PPTX نمودار دایره‌ای ایجاد و سفارشی کنیم" intro="برای افزودن نمودار دایره‌ای به یک ارائه PPTX این مراحل را دنبال کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک نمونه `Presentation` ایجاد کنید و از طریق متغیر `slide` به اسلاید موردنظر دسترسی پیدا کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`add_chart` را با `ChartType.PIE` فراخوانی کنید تا نمودار دایره‌ای به اسلاید اضافه شود.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}از `chart_data_workbook` برای جایگزینی دسته‌ها و سری‌های پیش‌فرض استفاده کنید، سپس برچسب‌ها، رنگ‌ها و `first_slice_angle` را پیکربندی کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`save` را با `SaveFormat.PPTX` فراخوانی کنید تا ارائه در قالب PPTX نوشته شود.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="ساخته شده با Aspose.Slides" title="ایجاد آنلاین نمودارهای PPTX" description="برنامه رایگان Aspose.Slides Chart با [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fa/python-net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPTX شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Chart" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه نمودار ایجاد می‌کند.
- از داده‌های Excel یا جدول نمودار بسازید.
- آن را به‌صورت فایل PPTX یا تصویر دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های پشتیبانی‌شده برای نمودار" subTitle="با Python می‌توانید در قالب‌های دیگر نیز نمودار ایجاد کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/python-net/chart/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
