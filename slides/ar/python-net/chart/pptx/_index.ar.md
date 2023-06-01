---
title: إنشاء مخطط في PPTX ملفات العروض التقديمية باستخدام Python
url: /ar/python-net/chart/pptx/
keywords: إنشاء مخطط ، وإنشاء مخطط مبعثر ، وإنشاء مخطط دائري ، وإنشاء مخطط هيكلي ، وإنشاء مخطط أسهم ، وإنشاء مخطط مربع وشعير ، وإنشاء مخطط مدرج تكراري ، وإنشاء مخطط قمعي ، ومخطط أمة الله ، ومخطط متعدد الفئات ، وعرض تقديمي لـ PowerPoint ، Python
description: كود مصدر Python لإنشاء مخطط في العرض التقديمي PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="أضف مخطط ومخطط PowerPoint إلى PPTX باستخدام Python" h2="أنشئ تطبيقات Python الخاصة بك لإنشاء مخططات قابلة للتخصيص بالكامل في ملفات العروض التقديمية باستخدام واجهات برمجة التطبيقات من جانب الخادم. تعرف على كيفية إضافة سلاسل وفئات جديدة إلى المخطط." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="إضافة مخطط دائري إلى العرض التقديمي PPTX عبر Python" %}}
تُستخدم المخططات الدائرية لإظهار علاقة جزء بالكل في البيانات ، خاصةً عندما تحتوي البيانات على تسميات فئوية بقيم رقمية. يوفر Aspose.Slides for Python via .NET واجهة برمجة تطبيقات قوية لإنشاء مخططات دائرية في عروض PowerPoint التقديمية. يمكنك العثور على مزيد من المعلومات حول تخصيص المخططات الدائرية باستخدام Aspose.Slides for Python API في هذا [الرابط](https://docs.aspose.com/slides/python-net/pie-chart/).
{{% blocks/products/pf/agp/code-block title="يوضح نموذج التعليمات البرمجية التالي كيفية إنشاء مخطط دائري في PowerPoint PPTX في Python." offSpacer="true" %}}

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
    presentation.save("pie-chart.pptx", slides.export.SaveFormat.PPTX)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="كيفية إنشاء مخطط دائري وتخصيصه في PPTX عبر Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="هذه هي الخطوات لإضافة مخطط دائري إلى ملفات PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
أولاً ، قم بإنشاء مثيل لفئة العرض التقديمي PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
أضف مخططًا دائريًا بالبيانات الافتراضية باستخدام طريقة add_chart (...).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تكوين الخصائص الضرورية للمخطط الدائري (تعيين عنوان المخطط ، وتعديل بيانات المخطط ، وتطبيق التنسيق على السلاسل والفئات)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
احفظ النتيجة بتنسيق PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="PPTX عبر الإنترنت يمكنك إنشاء عروض توضيحية مباشرة للمخططات" sectionDescription="إنشاء الرسوم البيانية على الإنترنت" >}}

{{< blocks/products/pf/agp/other-supported-section title="التنسيقات الأخرى المدعومة" subTitle="باستخدام Python ، يمكنك أيضًا إضافة مخططات إلى التنسيقات التالية:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/python-net/chart/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}