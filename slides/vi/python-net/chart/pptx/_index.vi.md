---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tạo biểu đồ trong bản trình bày PPTX bằng Python
url: /vi/python-net/chart/pptx/
description: Tạo và tùy chỉnh biểu đồ trong bản trình bày PPTX bằng Python và Aspose.Slides for Python via .NET.
keywords: tạo biểu đồ, tạo biểu đồ phân tán, tạo biểu đồ hình tròn, tạo biểu đồ dạng cây, tạo biểu đồ chứng khoán, tạo biểu đồ hộp và râu, tạo biểu đồ tần suất, tạo biểu đồ hình phễu, biểu đồ hình tia nắng, biểu đồ nhiều danh mục, bản trình bày PowerPoint, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tạo biểu đồ trong bản trình bày PPTX bằng Python" h2="Xây dựng ứng dụng Python tạo biểu đồ trình bày có thể tùy chỉnh với danh mục, chuỗi dữ liệu, nhãn và định dạng của riêng bạn." related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tạo biểu đồ hình tròn trong bản trình bày PPTX bằng Python" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/vi/python-net/) cho phép bạn tạo biểu đồ hình tròn, thay thế danh mục và chuỗi dữ liệu mặc định, đồng thời tùy chỉnh nhãn và màu sắc. Biểu đồ hình tròn phù hợp nhất để cho thấy một vài danh mục số đóng góp vào tổng thể như thế nào. Để biết thêm tùy chọn, xem [Tùy chỉnh biểu đồ hình tròn trong bản trình bày](https://docs.aspose.com/slides/python-net/pie-chart/).

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tạo biểu đồ hình tròn trong bản trình bày PPTX bằng Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách tạo và tùy chỉnh biểu đồ hình tròn trong PPTX bằng Python" intro="Làm theo các bước sau để thêm biểu đồ hình tròn vào bản trình bày PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tạo một thể hiện `Presentation` và truy cập trang chiếu mong muốn qua biến `slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi `add_chart` với `ChartType.PIE` để thêm biểu đồ hình tròn vào trang chiếu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dùng `chart_data_workbook` để thay thế danh mục và chuỗi dữ liệu mặc định, sau đó cấu hình nhãn, màu sắc và `first_slice_angle`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi `save` với `SaveFormat.PPTX` để ghi bản trình bày ở định dạng PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Được xây dựng bằng Aspose.Slides" title="Tạo biểu đồ PPTX trực tuyến" description="Ứng dụng Aspose.Slides Chart miễn phí được xây dựng bằng [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/vi/python-net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPTX của riêng bạn." button="Mở Aspose.Slides Chart" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides tạo biểu đồ trước khi bạn viết mã.
- Tạo biểu đồ từ dữ liệu Excel hoặc bảng.
- Tải xuống dưới dạng tệp PPTX hoặc hình ảnh.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác được hỗ trợ cho biểu đồ" subTitle="Với Python, bạn cũng có thể tạo biểu đồ ở các định dạng khác." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/chart/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
