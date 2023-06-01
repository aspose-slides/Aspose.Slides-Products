---
title: สร้างแผนภูมิในไฟล์การนำเสนอ PPT โดยใช้ Python
url: /th/python-net/chart/ppt/
keywords: สร้างแผนภูมิ, สร้างแผนภูมิกระจัดกระจาย, สร้างแผนภูมิวงกลม, สร้างแผนภูมิแผนผังต้นไม้, สร้างแผนภูมิหุ้น, สร้างแผนภูมิกล่องและมัสสุ, สร้างแผนภูมิฮิสโทแกรม, สร้างแผนภูมิช่องทาง, แผนภูมิซันเบิร์สต์, แผนภูมิหลายหมวดหมู่, งานนำเสนอ PowerPoint, Python
description: ซอร์สโค้ด Python เพื่อสร้างแผนภูมิในการนำเสนอ PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="เพิ่มแผนภูมิและไดอะแกรม PowerPoint ใน PPT โดยใช้ Python" h2="สร้างแอป Python ของคุณเองเพื่อสร้างแผนภูมิที่ปรับแต่งได้อย่างเต็มที่ในไฟล์งานนำเสนอโดยใช้ API ฝั่งเซิร์ฟเวอร์ เรียนรู้วิธีเพิ่มซีรี่ส์และหมวดหมู่ใหม่ลงในแผนภูมิ" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="เพิ่มแผนภูมิวงกลมในงานนำเสนอ PPT ผ่าน Python" %}}
แผนภูมิวงกลมใช้เพื่อแสดงความสัมพันธ์แบบส่วนต่อส่วนทั้งหมดในข้อมูล โดยเฉพาะอย่างยิ่งเมื่อข้อมูลมีป้ายกำกับหมวดหมู่ที่มีค่าเป็นตัวเลข Aspose.Slides for Python via .NET มี API ที่มีประสิทธิภาพสำหรับการสร้างแผนภูมิวงกลมในงานนำเสนอ PowerPoint คุณสามารถดูข้อมูลเพิ่มเติมเกี่ยวกับการปรับแต่งแผนภูมิวงกลมโดยใช้ Aspose.Slides สำหรับ Python API ได้ใน [ลิงก์](https://docs.aspose.com/slides/python-net/pie-chart/)
{{% blocks/products/pf/agp/code-block title="ตัวอย่างโค้ดต่อไปนี้แสดงวิธีสร้างแผนภูมิวงกลมใน PowerPoint PPT ใน Python" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="วิธีสร้างและปรับแต่งแผนภูมิวงกลมใน PPT ผ่าน Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการเพิ่มแผนภูมิวงกลมไปยังไฟล์ PPT" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ขั้นแรก สร้างอินสแตนซ์ของคลาสการนำเสนอ PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มแผนภูมิวงกลมด้วยข้อมูลเริ่มต้นโดยใช้เมธอด add_chart(...)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
กำหนดค่าคุณสมบัติที่จำเป็นของแผนภูมิวงกลม (ตั้งชื่อแผนภูมิ แก้ไขข้อมูลแผนภูมิ ใช้การจัดรูปแบบกับชุดข้อมูลและหมวดหมู่)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์ในรูปแบบ PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="ออนไลน์ PPT สร้างแผนภูมิ การสาธิตสด" sectionDescription="สร้างแผนภูมิออนไลน์" >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบอื่นๆ ที่รองรับ" subTitle="เมื่อใช้ Python คุณยังสามารถเพิ่มแผนภูมิในรูปแบบต่อไปนี้:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/chart/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}