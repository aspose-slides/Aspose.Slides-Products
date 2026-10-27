---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python으로 PPTX 프레젠테이션에 차트 만들기
url: /ko/python-net/chart/pptx/
description: Python과 Aspose.Slides for Python via .NET을 사용하여 PPTX 프레젠테이션에 차트를 만들고 사용자 지정합니다.
keywords: 차트 만들기, 분산형 차트 만들기, 원형 차트 만들기, 트리맵 차트 만들기, 주식형 차트 만들기, 상자 수염 차트 만들기, 히스토그램 차트 만들기, 깔때기형 차트 만들기, 선버스트 차트, 다중 범주 차트, PowerPoint 프레젠테이션, Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python으로 PPTX 프레젠테이션에 차트 만들기" h2="고유한 범주, 데이터 계열, 레이블 및 서식으로 사용자 지정 가능한 프레젠테이션 차트를 만드는 Python 애플리케이션을 빌드하세요." related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python으로 PPTX 프레젠테이션에 원형 차트 만들기" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/ko/python-net/)을 사용하면 원형 차트를 만들고, 기본 범주와 계열을 바꾸고, 레이블과 색을 사용자 지정할 수 있습니다. 원형 차트는 적은 수의 숫자 범주가 전체에 얼마나 기여하는지 보여 줄 때 가장 효과적입니다. 더 많은 옵션은 [프레젠테이션에서 원형 차트 사용자 지정](https://docs.aspose.com/slides/python-net/pie-chart/)을 참조하세요.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python으로 PPTX 프레젠테이션에 원형 차트 만들기" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python으로 PPTX에서 원형 차트를 만들고 사용자 지정하는 방법" intro="PPTX 프레젠테이션에 원형 차트를 추가하려면 다음 단계를 따르세요." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 인스턴스를 만들고 `slide` 변수를 통해 원하는 슬라이드에 액세스합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ChartType.PIE`와 함께 `add_chart`를 호출하여 슬라이드에 원형 차트를 추가합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`chart_data_workbook`을 사용하여 기본 범주와 계열을 바꾼 다음 레이블, 색 및 `first_slice_angle`을 구성합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.PPTX`와 함께 `save`를 호출하여 프레젠테이션을 PPTX 형식으로 씁니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Aspose.Slides로 구축" title="온라인에서 PPTX 차트 만들기" description="무료 Aspose.Slides Chart 앱은 위 코드와 동일한 API인 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ko/python-net/)로 구축되었습니다. 앱을 열고 내 PPTX 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Chart 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 차트를 만드는 방식을 확인하세요.
- Excel 또는 표 데이터로 차트를 만듭니다.
- PPTX 파일 또는 이미지로 다운로드합니다.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="차트에 지원되는 기타 형식" subTitle="Python을 사용하면 다른 형식으로도 차트를 만들 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/python-net/chart/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
