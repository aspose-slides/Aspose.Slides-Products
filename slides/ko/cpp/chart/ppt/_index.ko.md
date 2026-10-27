---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7490
title: C++로 PPT 차트 만들기
url: /ko/cpp/chart/ppt/ 
description: Windows 및 Linux에서 PPT 프레젠테이션에 차트를 만드는 C++ 예제 코드입니다.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++로 PPT 프레젠테이션에 차트 만들기" h2="Microsoft PowerPoint 없이 서버 측 Aspose.Slides for C++ API를 사용하여 PPT 프레젠테이션에 차트를 만드세요."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++로 PPT 차트 만들기" %}}

[Aspose.Slides for C++](/slides/ko/cpp/)를 사용하여 PPT 프레젠테이션에 차트를 만드세요. [NuGet](https://www.nuget.org/packages/Aspose.Slides.Cpp/)에서 패키지를 설치하거나 패키지 관리자 콘솔에서 다음 명령을 사용하세요.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="명령" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT에 차트 만들기 – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

// Add a chart with default data.
auto chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0, 0, 500, 500);

// Set the index of the chart data sheet.
int defaultWorksheetIndex = 0;

// Get the chart data workbook.
auto chartDataWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();

// Set the chart title.
chart->get_ChartTitle()->AddTextFrameForOverriding(u"Sample Title");
chart->get_ChartTitle()->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chart->get_ChartTitle()->set_Height(20);
chart->set_HasTitle(true);

// Delete the default generated series and categories.
chart->get_ChartData()->get_Series()->Clear();
chart->get_ChartData()->get_Categories()->Clear();

// Add series.
chart->get_ChartData()->get_Series()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 0, 1, ObjectExt::Box(String(u"Series 1"))), chart->get_Type());
chart->get_ChartData()->get_Series()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 0, 2, ObjectExt::Box(String(u"Series 2"))), chart->get_Type());

// Add categories.
chart->get_ChartData()->get_Categories()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 1, 0, ObjectExt::Box(String(u"Category 1"))));
chart->get_ChartData()->get_Categories()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 2, 0, ObjectExt::Box(String(u"Category 2"))));
chart->get_ChartData()->get_Categories()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 3, 0, ObjectExt::Box(String(u"Category 3"))));

// Take the first chart series.
auto series = chart->get_ChartData()->get_Series()->idx_get(0);

// Populate series data.
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 1, 1, ObjectExt::Box(20)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 2, 1, ObjectExt::Box(50)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 3, 1, ObjectExt::Box(30)));

// Set the fill color for the series.
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Blue());

// Take the second chart series.
series = chart->get_ChartData()->get_Series()->idx_get(1);

// Populate series data.
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 1, 2, ObjectExt::Box(30)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 2, 2, ObjectExt::Box(10)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 3, 2, ObjectExt::Box(60)));

// Set the fill color for the series.
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Orange());

// Show the category name for the first label.
auto dataLabel = series->get_DataPoints()->idx_get(0)->get_Label();
dataLabel->get_DataLabelFormat()->set_ShowCategoryName(true);

dataLabel = series->get_DataPoints()->idx_get(1)->get_Label();
dataLabel->get_DataLabelFormat()->set_ShowSeriesName(true);

// Show the value for the third label.
dataLabel = series->get_DataPoints()->idx_get(2)->get_Label();
dataLabel->get_DataLabelFormat()->set_ShowValue(true);
dataLabel->get_DataLabelFormat()->set_ShowSeriesName(true);
dataLabel->get_DataLabelFormat()->set_Separator(u"/");

// Save the PPT file.
presentation->Save(u"column_chart.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++로 PPT 파일에 차트를 만드는 방법" intro="Aspose.Slides for C++를 사용하면 몇 줄의 코드로 PPT 프레젠테이션에 차트를 만들 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` 개체를 만듭니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}첫 번째 슬라이드에 액세스합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}기본 데이터가 있는 차트를 추가합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}차트 데이터 시트의 인덱스를 설정합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}차트 데이터 통합 문서를 가져옵니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}차트 제목을 설정합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}기본으로 생성된 계열과 범주를 삭제합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}계열과 범주를 추가합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}첫 번째 차트 계열을 가져와 데이터를 채웁니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}계열의 채우기 색을 설정합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}두 번째 계열의 데이터 레이블에 범주 이름, 계열 이름 및 값을 표시합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT 파일을 저장합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="시스템 요구 사항" intro="Aspose.Slides for C++는 주요 플랫폼과 운영 체제를 지원합니다. 환경이 다음 필수 조건을 충족하는지 확인하세요." %}}

-  지원되는 C++ 런타임이 있는 Microsoft Windows, Linux, macOS 또는 기타 호환 OS.
-  프로젝트에서 참조하는 Aspose.Slides for C++ 라이브러리.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Aspose.Slides로 구축" title="온라인에서 PPT 차트 만들기" description="무료 Aspose.Slides Chart 앱은 위 코드와 동일한 API인 [Aspose.Slides for C++](https://products.aspose.com/slides/ko/cpp/)로 구축되었습니다. 앱을 열고 내 PPT 파일로 API가 무엇을 할 수 있는지 확인해 보세요." button="Aspose.Slides Chart 열기" note="[모든 무료 앱](https://products.aspose.app/slides/family)" >}}
- 브라우저에서 실행되며 설치가 필요 없습니다.
- 코드를 작성하기 전에 Aspose.Slides가 차트를 만드는 방식을 확인하세요.
- Excel 또는 표 데이터로 차트를 만듭니다.
- PPT 파일 또는 이미지로 다운로드합니다.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

PPT 파일에는 슬라이드 쇼용 슬라이드 모음이 들어 있습니다. Microsoft PowerPoint 97-2003의 이진 파일 형식을 사용합니다. PPT 파일에는 텍스트, 글머리 기호, 이미지, 멀티미디어 및 기타 포함된 OLE 개체가 들어 있을 수 있습니다. Microsoft는 PowerPoint 2007에서 최신 PPTX 형식을 도입했습니다. PPTX는 Office Open XML을 기반으로 하며 이전 이진 형식과 다릅니다. OpenOffice Impress와 Apple Keynote 같은 다른 애플리케이션에서도 PPT 파일을 만들 수 있습니다.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="차트에 지원되는 기타 형식" subTitle="C++를 사용하면 다른 형식으로도 차트를 만들 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ko/cpp/chart/pptx/" name="PPTX" description="Open XML 프레젠테이션 형식" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
