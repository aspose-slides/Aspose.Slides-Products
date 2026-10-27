---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python का उपयोग करके PPTX प्रेज़ेंटेशन में चार्ट बनाएँ
url: /hi/python-net/chart/pptx/
description: Python और Aspose.Slides for Python via .NET का उपयोग करके PPTX प्रेज़ेंटेशन में चार्ट बनाएँ और अनुकूलित करें।
keywords: चार्ट बनाएँ, स्कैटर चार्ट बनाएँ, पाई चार्ट बनाएँ, ट्रीमैप चार्ट बनाएँ, स्टॉक चार्ट बनाएँ, बॉक्स और व्हिस्कर चार्ट बनाएँ, हिस्टोग्राम चार्ट बनाएँ, फ़नल चार्ट बनाएँ, सनबर्स्ट चार्ट, मल्टीकैटेगरी चार्ट, PowerPoint प्रेज़ेंटेशन, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python का उपयोग करके PPTX प्रेज़ेंटेशन में चार्ट बनाएँ" h2="ऐसे Python एप्लिकेशन बनाएँ जो आपकी अपनी श्रेणियों, डेटा सीरीज़, लेबल और फ़ॉर्मेटिंग के साथ अनुकूलन योग्य प्रेज़ेंटेशन चार्ट बनाएँ।" related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python के साथ PPTX प्रेज़ेंटेशन में पाई चार्ट बनाएँ" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/hi/python-net/) से आप पाई चार्ट बना सकते हैं, उसकी डिफ़ॉल्ट श्रेणियाँ और सीरीज़ बदल सकते हैं, और उसके लेबल और रंग अनुकूलित कर सकते हैं। पाई चार्ट यह दिखाने के लिए सबसे उपयुक्त हैं कि कुछ संख्यात्मक श्रेणियाँ पूरे में कितना योगदान देती हैं। अधिक विकल्पों के लिए [प्रेज़ेंटेशन में पाई चार्ट अनुकूलित करें](https://docs.aspose.com/slides/python-net/pie-chart/) देखें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python के साथ PPTX प्रेज़ेंटेशन में पाई चार्ट बनाएँ" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python के साथ PPTX में पाई चार्ट कैसे बनाएँ और अनुकूलित करें" intro="PPTX प्रेज़ेंटेशन में पाई चार्ट जोड़ने के लिए इन चरणों का पालन करें।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}एक `Presentation` इंस्टेंस बनाएँ और `slide` वेरिएबल के ज़रिए वांछित स्लाइड तक पहुँचें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}स्लाइड में पाई चार्ट जोड़ने के लिए `ChartType.PIE` के साथ `add_chart` कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}डिफ़ॉल्ट श्रेणियाँ और सीरीज़ बदलने के लिए `chart_data_workbook` का उपयोग करें, फिर लेबल, रंग और `first_slice_angle` कॉन्फ़िगर करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेज़ेंटेशन को PPTX फ़ॉर्मेट में लिखने के लिए `SaveFormat.PPTX` के साथ `save` कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Aspose.Slides से निर्मित" title="PPTX चार्ट ऑनलाइन बनाएँ" description="मुफ़्त Aspose.Slides Chart ऐप [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hi/python-net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPTX फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Chart खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides चार्ट कैसे बनाता है।
- Excel या टेबल डेटा से चार्ट बनाएँ।
- इसे PPTX फ़ाइल या इमेज के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="चार्ट के लिए अन्य समर्थित फ़ॉर्मेट" subTitle="Python के साथ, आप अन्य फ़ॉर्मेट में भी चार्ट बना सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/chart/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
