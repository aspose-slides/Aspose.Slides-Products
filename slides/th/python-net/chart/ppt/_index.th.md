---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: สร้างแผนภูมิในงานนำเสนอ PPT ด้วย Python
url: /th/python-net/chart/ppt/
description: สร้างและปรับแต่งแผนภูมิในงานนำเสนอ PPT ด้วย Python และ Aspose.Slides for Python via .NET
keywords: สร้างแผนภูมิ, สร้างแผนภูมิกระจาย, สร้างแผนภูมิวงกลม, สร้างแผนภูมิทรีแมป, สร้างแผนภูมิหุ้น, สร้างแผนภูมิกล่องและหนวด, สร้างฮิสโทแกรม, สร้างแผนภูมิกรวย, แผนภูมิซันเบิร์สต์, แผนภูมิหลายหมวดหมู่, งานนำเสนอ PowerPoint, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="สร้างแผนภูมิในงานนำเสนอ PPT ด้วย Python" h2="สร้างแอปพลิเคชัน Python ที่สร้างแผนภูมิงานนำเสนอที่ปรับแต่งได้ด้วยหมวดหมู่ ชุดข้อมูล ป้ายชื่อ และการจัดรูปแบบของคุณเอง" related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="สร้างแผนภูมิวงกลมในงานนำเสนอ PPT ด้วย Python" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/th/python-net/) ช่วยให้คุณสร้างแผนภูมิวงกลม แทนที่หมวดหมู่และชุดข้อมูลเริ่มต้น และปรับแต่งป้ายชื่อและสีได้ แผนภูมิวงกลมเหมาะที่สุดสำหรับแสดงว่าหมวดหมู่ตัวเลขจำนวนไม่มากมีส่วนในภาพรวมอย่างไร ดูตัวเลือกเพิ่มเติมได้ที่ [ปรับแต่งแผนภูมิวงกลมในงานนำเสนอ](https://docs.aspose.com/slides/python-net/pie-chart/)

{{< blocks/products/pf/slides-design-update-10-2026/code title="สร้างแผนภูมิวงกลมในงานนำเสนอ PPT ด้วย Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีสร้างและปรับแต่งแผนภูมิวงกลมใน PPT ด้วย Python" intro="ทำตามขั้นตอนเหล่านี้เพื่อเพิ่มแผนภูมิวงกลมลงในงานนำเสนอ PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างอินสแตนซ์ `Presentation` และเข้าถึงสไลด์ที่ต้องการผ่านตัวแปร `slide`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียก `add_chart` ด้วย `ChartType.PIE` เพื่อเพิ่มแผนภูมิวงกลมลงในสไลด์{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ใช้ `chart_data_workbook` เพื่อแทนที่หมวดหมู่และชุดข้อมูลเริ่มต้น จากนั้นกำหนดค่าป้ายชื่อ สี และ `first_slice_angle`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียก `save` ด้วย `SaveFormat.PPT` เพื่อเขียนงานนำเสนอในรูปแบบ PPT{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="สร้างด้วย Aspose.Slides" title="สร้างแผนภูมิ PPT ออนไลน์" description="แอป Aspose.Slides Chart ฟรีนี้สร้างด้วย [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/th/python-net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPT ของคุณเอง" button="เปิด Aspose.Slides Chart" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides สร้างแผนภูมิอย่างไรก่อนเขียนโค้ด
- สร้างแผนภูมิจากข้อมูล Excel หรือข้อมูลในตาราง
- ดาวน์โหลดเป็นไฟล์ PPT หรือรูปภาพ
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับสำหรับแผนภูมิ" subTitle="ด้วย Python คุณยังสร้างแผนภูมิในรูปแบบอื่นได้ด้วย" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/chart/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
