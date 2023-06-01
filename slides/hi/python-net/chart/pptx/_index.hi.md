---
title: Python का उपयोग करके PPTX प्रस्तुतिकरण फ़ाइलों में चार्ट बनाएं
url: /hi/python-net/chart/pptx/
keywords: चार्ट बनाएं, बिखरा हुआ चार्ट बनाएं, पाई चार्ट बनाएं, ट्रीमैप चार्ट बनाएं, स्टॉक चार्ट बनाएं, बॉक्स और व्हिस्कर चार्ट बनाएं, हिस्टोग्राम चार्ट बनाएं, फ़नल चार्ट बनाएं, सनबर्स्ट चार्ट, बहुश्रेणी चार्ट, पॉवरपॉइंट प्रस्तुति, {उत्पाद_लैंग}
description: PPTX प्रस्तुतिकरण में चार्ट बनाने के लिए Python स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="{Product_lang} का उपयोग करके PPTX में PowerPoint चार्ट और आरेख जोड़ें" h2="सर्वर-साइड API का उपयोग करके प्रस्तुतिकरण फ़ाइलों में पूरी तरह से अनुकूलन योग्य चार्ट बनाने के लिए अपने स्वयं के Python एप्लिकेशन बनाएं. चार्ट में नई शृंखला और श्रेणियां जोड़ना सीखें।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python द्वारा PPTX प्रस्तुतिकरण में पाई चार्ट जोड़ें" %}}
पाई चार्ट का उपयोग डेटा में आंशिक-से-संबंध दिखाने के लिए किया जाता है, खासकर जब डेटा में संख्यात्मक मानों के साथ श्रेणीबद्ध लेबल होते हैं। Aspose.Slides for Python via .NET PowerPoint प्रस्तुतियों में पाई चार्ट बनाने के लिए एक शक्तिशाली API प्रदान करता है। आप इस [लिंक](https://docs.aspose.com/slides/python-net/pie-chart/) में Aspose.Slides for Python API का उपयोग करके पाई चार्ट को कस्टमाइज़ करने के बारे में अधिक जानकारी प्राप्त कर सकते हैं।
{{% blocks/products/pf/agp/code-block title="निम्न कोड नमूना दिखाता है कि PowerPoint PPTX में Python में पाई चार्ट कैसे बनाया जाता है." offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Python के माध्यम से PPTX में पाई चार्ट कैसे बनाएं और कस्टमाइज़ करें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="पाई चार्ट को PPTX फ़ाइलों में जोड़ने के लिए ये चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
सबसे पहले, PPTX प्रस्तुति वर्ग का एक उदाहरण बनाएं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add_chart(...) पद्धति का उपयोग करके डिफ़ॉल्ट डेटा के साथ पाई चार्ट जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पाई चार्ट के आवश्यक गुणों को कॉन्फ़िगर करें (चार्ट शीर्षक सेट करें, चार्ट डेटा संशोधित करें, श्रृंखला और श्रेणियों के लिए स्वरूपण लागू करें)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम PPTX प्रारूप में सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="ऑनलाइन PPTX चार्ट लाइव डेमो बनाएं" sectionDescription="ऑनलाइन चार्ट बनाएं" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित प्रारूप" subTitle="{Product_lang} का इस्तेमाल करके, आप नीचे दिए गए फ़ॉर्मैट में चार्ट भी जोड़ सकते हैं:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/chart/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}