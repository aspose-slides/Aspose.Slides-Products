---
title: Python을(를) 사용하여 PPTX 프레젠테이션 파일로 차트 만들기
url: /ko/python-net/chart/pptx/
keywords: 차트 생성, 분산형 차트 생성, 파이 차트 생성, 트리맵 차트 생성, 주식형 차트 생성, 상자 및 위스커 차트 생성, 히스토그램 차트 생성, 깔때기형 차트 생성, 선버스트 차트, 멀티카테고리 차트, PowerPoint 프레젠테이션, Python
description: PPTX Presentation에서 차트를 생성하기 위한 Python 소스 코드.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python을 사용하여 PPTX에 PowerPoint 차트 및 다이어그램 추가" h2="자신만의 Python 앱을 구축하여 서버 측 API를 사용하여 프리젠테이션 파일에 완전 맞춤형 차트를 생성하세요. 차트에 새 계열 및 범주를 추가하는 방법을 알아봅니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python을(를) 통해 PPTX 프레젠테이션에 원형 차트 추가" %}}
원형 차트는 특히 데이터에 숫자 값이 포함된 범주 레이블이 포함된 경우 데이터의 부분-전체 관계를 표시하는 데 사용됩니다. Aspose.Slides for Python via .NET은 PowerPoint 프레젠테이션에서 원형 차트를 만들기 위한 강력한 API를 제공합니다. 이 [링크](https://docs.aspose.com/slides/python-net/pie-chart/)에서 Aspose.Slides for Python API를 사용하여 파이 차트를 사용자 지정하는 방법에 대한 자세한 내용을 확인할 수 있습니다.
{{% blocks/products/pf/agp/code-block title="다음 코드 샘플은 Python의 PowerPoint PPTX에서 원형 차트를 만드는 방법을 보여줍니다." offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Python을(를) 통해 PPTX에서 원형 차트를 만들고 사용자 지정하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="PPTX 파일에 원형 차트를 추가하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
먼저 PPTX 프레젠테이션 클래스의 인스턴스를 만듭니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
add_chart(...) 메서드를 사용하여 기본 데이터로 원형 차트를 추가합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
원형 차트의 필수 속성 설정(차트 제목 설정, 차트 데이터 수정, 계열 및 범주에 서식 적용)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 PPTX 형식으로 저장
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="온라인 PPTX Create Charts 라이브 데모" sectionDescription="온라인 차트 만들기" >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 형식" subTitle="Python을 사용하여 다음 형식으로 차트를 추가할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/chart/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}