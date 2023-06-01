---
title: ایجاد نمودار در فایل‌های ارائه PPT با استفاده از Python
url: /fa/python-net/chart/ppt/
keywords: ایجاد نمودار، ایجاد نمودار پراکنده، ایجاد نمودار دایره ای، ایجاد نمودار نقشه درختی، ایجاد نمودار سهام، ایجاد نمودار جعبه و سبیل، ایجاد نمودار هیستوگرام، ایجاد نمودار قیف، نمودار آفتاب انفجار، نمودار چند دسته، ارائه پاورپوینت، Python
description: کد منبع Python برای ایجاد نمودار در ارائه PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="با استفاده از Python نمودار و نمودار پاورپوینت را به PPT اضافه کنید" h2="برای ایجاد نمودارهای کاملاً قابل تنظیم در فایل های ارائه با استفاده از API های سمت سرور، برنامه های Python خود را بسازید. با نحوه افزودن سری ها و دسته بندی های جدید به نمودار آشنا شوید." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="اضافه کردن نمودار دایره ای به ارائه PPT از طریق Python" %}}
نمودارهای دایره ای برای نشان دادن رابطه جزء به کل در داده ها استفاده می شود، به خصوص زمانی که داده ها دارای برچسب های طبقه بندی با مقادیر عددی هستند. Aspose.Slides for Python via .NET یک API قدرتمند برای ایجاد نمودارهای پای در ارائه‌های پاورپوینت ارائه می‌کند. می توانید اطلاعات بیشتری درباره سفارشی کردن نمودارهای دایره ای با استفاده از Aspose.Slides for Python API در این [پیوند](https://docs.aspose.com/slides/python-net/pie-chart/) بیابید.
{{% blocks/products/pf/agp/code-block title="نمونه کد زیر نحوه ایجاد نمودار دایره ای در پاورپوینت PPT در Python را نشان می دهد." offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="نحوه ایجاد و سفارشی کردن نمودار پای در PPT از طریق Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="این مراحل برای افزودن نمودار پای به فایل‌های PPT است." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ابتدا یک نمونه از کلاس Presentation PPT ایجاد کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
با استفاده از روش add_chart(...) یک نمودار دایره ای با داده های پیش فرض اضافه کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
پیکربندی ویژگی های لازم نمودار دایره ای (تنظیم عنوان نمودار، تغییر داده های نمودار، اعمال قالب بندی برای سری ها و دسته ها)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
نتیجه را در قالب PPT ذخیره کنید
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="آنلاین PPT نمایش‌های نمایشی زنده نمودارها را ایجاد کنید" sectionDescription="نمودارها را به صورت آنلاین ایجاد کنید" >}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های پشتیبانی شده" subTitle="با استفاده از Python، می‌توانید نمودارها را نیز به قالب‌های زیر اضافه کنید:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/python-net/chart/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}