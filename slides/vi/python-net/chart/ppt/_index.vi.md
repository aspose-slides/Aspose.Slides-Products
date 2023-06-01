---
title: Tạo Biểu đồ trong Tệp Bản trình bày PPT bằng Python
url: /vi/python-net/chart/ppt/
keywords: Tạo biểu đồ, tạo biểu đồ phân tán, tạo biểu đồ hình tròn, tạo biểu đồ cây, tạo biểu đồ chứng khoán, tạo biểu đồ hộp và râu ria, tạo biểu đồ tần suất, tạo biểu đồ phễu, biểu đồ sunburst, biểu đồ đa danh mục, bản trình bày PowerPoint, Python
description: Mã nguồn Python để tạo biểu đồ trong Bản trình bày PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Thêm Biểu đồ và Sơ đồ PowerPoint vào PPT bằng Python" h2="Xây dựng các ứng dụng Python của riêng bạn để tạo các biểu đồ có thể tùy chỉnh hoàn toàn trong tệp bản trình bày bằng API phía máy chủ. Tìm hiểu cách thêm chuỗi và danh mục mới vào biểu đồ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Thêm Biểu đồ hình tròn vào Bản trình bày PPT qua Python" %}}
Biểu đồ hình tròn được sử dụng để hiển thị mối quan hệ từng phần trong dữ liệu, đặc biệt khi dữ liệu chứa các nhãn phân loại có giá trị số. Aspose.Slides for Python via .NET cung cấp API mạnh mẽ để tạo biểu đồ Hình tròn trong bản trình bày PowerPoint. Bạn có thể tìm thêm thông tin về cách tùy chỉnh biểu đồ hình tròn bằng API Aspose.Slides cho Python trong [liên kết](https://docs.aspose.com/slides/python-net/pie-chart/) này.
{{% blocks/products/pf/agp/code-block title="Mẫu mã sau đây cho biết cách tạo biểu đồ hình tròn trong PowerPoint PPT trong Python." offSpacer="true" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

# Create presentation (or load existing one) 
with slides.Presentation() as presentation:

    # Access first slide
    slide = presentation.slides[0]

    # Add chart with default data
    chart = slide.shapes.add_chart(slides.charts.ChartType.PIE, 100, 100, 400, 400)

    # Set chart title
    chart.chart_title.add_text_frame_for_overriding("Sample Title")
    chart.chart_title.text_frame_for_overriding.text_frame_format.center_text = slides.NullableBool(True)
    chart.chart_title.height = 20
    chart.has_title = True

    # Set first series to show values
    chart.chart_data.series[0].labels.default_data_label_format.show_value = True

    # Set the index of chart data sheet
    defaultWorksheetIndex = 0

    # Get the chart data worksheet
    fact = chart.chart_data.chart_data_workbook

    # Delete default generated series and categories
    chart.chart_data.series.clear()
    chart.chart_data.categories.clear()

    # Add new categories
    chart.chart_data.categories.add(fact.get_cell(0, 1, 0, "First Qtr"))
    chart.chart_data.categories.add(fact.get_cell(0, 2, 0, "2nd Qtr"))
    chart.chart_data.categories.add(fact.get_cell(0, 3, 0, "3rd Qtr"))

    # Add new series
    series = chart.chart_data.series.add(fact.get_cell(0, 0, 1, "Series 1"), chart.type)

    # Populate series data
    series.data_points.add_data_point_for_pie_series(fact.get_cell(defaultWorksheetIndex, 1, 1, 20))
    series.data_points.add_data_point_for_pie_series(fact.get_cell(defaultWorksheetIndex, 2, 1, 50))
    series.data_points.add_data_point_for_pie_series(fact.get_cell(defaultWorksheetIndex, 3, 1, 30))

    # Add new points and set sector color
    chart.chart_data.series_groups[0].is_color_varied = True

    point = series.data_points[0]
    point.format.fill.fill_type = slides.FillType.SOLID
    point.format.fill.solid_fill_color.color = drawing.Color.orange

    # Set sector border
    point.format.line.fill_format.fill_type = slides.FillType.SOLID
    point.format.line.fill_format.solid_fill_color.color = drawing.Color.gray
    point.format.line.width = 3.0


    point1 = series.data_points[1]
    point1.format.fill.fill_type = slides.FillType.SOLID
    point1.format.fill.solid_fill_color.color = drawing.Color.blue_violet

    # Set sector border
    point1.format.line.fill_format.fill_type = slides.FillType.SOLID
    point1.format.line.fill_format.solid_fill_color.color = drawing.Color.blue
    point1.format.line.width = 3.0
    # point1.format.line.style = slides.LineStyle.SINGLE
    # point1.format.line.dash_style = slides.LineDashStyle.LARGE_DASH_DOT

    point2 = series.data_points[2]
    point2.format.fill.fill_type = slides.FillType.SOLID
    point2.format.fill.solid_fill_color.color = drawing.Color.yellow_green

    # Set sector border
    point2.format.line.fill_format.fill_type = slides.FillType.SOLID
    point2.format.line.fill_format.solid_fill_color.color = drawing.Color.red
    point2.format.line.width = 2.0
    # point2.format.line.style = slides.LineStyle.THIN_THIN
    # point2.format.line.dash_style = slides.LineDashStyle.LARGE_DASH_DOT_DOT

    # Create custom labels for each of categories for new series
    lbl1 = series.data_points[0].label

    # lbl.show_category_name = True
    lbl1.data_label_format.show_value = True

    lbl2 = series.data_points[1].label
    lbl2.data_label_format.show_value = True
    lbl2.data_label_format.show_legend_key = True
    lbl2.data_label_format.show_percentage = True

    lbl3 = series.data_points[2].label
    lbl3.data_label_format.show_series_name = True
    lbl3.data_label_format.show_percentage = True

    # Show leader lines for chart
    # series.labels.default_data_label_format.show_leader_lines = True

    # Set rotation angle for pie chart sectors
    chart.chart_data.series_groups[0].first_slice_angle = 180

    # Save presentation
    presentation.save("pie-chart.ppt", slides.export.SaveFormat.PPT)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách tạo và tùy chỉnh Biểu đồ hình tròn trong PPT qua Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để thêm biểu đồ Hình tròn vào tệp PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Đầu tiên, tạo một thể hiện của lớp Trình bày PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm biểu đồ hình tròn với dữ liệu mặc định bằng phương thức add_chart(...)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Định cấu hình các thuộc tính cần thiết của biểu đồ Hình tròn (Đặt tiêu đề biểu đồ, sửa đổi dữ liệu biểu đồ, Áp dụng định dạng cho chuỗi và danh mục)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả ở định dạng PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Trực tuyến PPT Tạo biểu đồ Trình diễn trực tiếp" sectionDescription="Tạo biểu đồ trực tuyến" >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng được hỗ trợ khác" subTitle="Sử dụng Python, Bạn cũng có thể thêm biểu đồ vào các định dạng sau:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-net/chart/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}