---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: إنشاء مخططات في عروض PPTX التقديمية باستخدام Python
url: /ar/python-net/chart/pptx/
description: أنشئ المخططات وخصّصها في عروض PPTX التقديمية باستخدام Python وAspose.Slides for Python via .NET.
keywords: إنشاء مخطط، إنشاء مخطط مبعثر، إنشاء مخطط دائري، إنشاء مخطط خريطة شجرية، إنشاء مخطط أسهم، إنشاء مخطط صندوقي، إنشاء مدرج تكراري، إنشاء مخطط قمعي، مخطط أشعة الشمس، مخطط متعدد الفئات، عرض تقديمي PowerPoint، Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="إنشاء مخططات في عروض PPTX التقديمية باستخدام Python" h2="أنشئ تطبيقات Python تنشئ مخططات عروض تقديمية قابلة للتخصيص بفئاتك وسلاسل بياناتك وتسمياتك وتنسيقك." related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="إنشاء مخطط دائري في عرض PPTX تقديمي باستخدام Python" variant="code" %}}

يتيح لك [Aspose.Slides for Python via .NET](/slides/ar/python-net/) إنشاء مخطط دائري واستبدال فئاته وسلاسله الافتراضية وتخصيص تسمياته وألوانه. تُعد المخططات الدائرية الأنسب لإظهار مساهمة عدد قليل من الفئات الرقمية في الإجمالي. لمزيد من الخيارات، راجع [تخصيص المخططات الدائرية في العروض التقديمية](https://docs.aspose.com/slides/python-net/pie-chart/).

{{< blocks/products/pf/slides-design-update-10-2026/code title="إنشاء مخطط دائري في عرض PPTX تقديمي باستخدام Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية إنشاء مخطط دائري وتخصيصه في PPTX باستخدام Python" intro="اتبع هذه الخطوات لإضافة مخطط دائري إلى عرض تقديمي بتنسيق PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أنشئ مثيلًا من `Presentation` وانتقل إلى الشريحة المطلوبة من خلال المتغير `slide`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ `add_chart` مع `ChartType.PIE` لإضافة مخطط دائري إلى الشريحة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استخدم `chart_data_workbook` لاستبدال الفئات والسلاسل الافتراضية، ثم اضبط التسميات والألوان و`first_slice_angle`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ `save` مع `SaveFormat.PPTX` لكتابة العرض التقديمي بتنسيق PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="مبني باستخدام Aspose.Slides" title="إنشاء مخططات PPTX عبر الإنترنت" description="تطبيق Aspose.Slides Chart المجاني مبني باستخدام [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ar/python-net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPTX الخاصة بك." button="افتح Aspose.Slides Chart" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف ينشئ Aspose.Slides المخططات قبل أن تكتب الشيفرة.
- أنشئ مخططًا من بيانات Excel أو من جدول.
- نزّله كملف PPTX أو كصورة.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للمخططات" subTitle="باستخدام Python، يمكنك أيضًا إنشاء مخططات بتنسيقات أخرى." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/python-net/chart/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
