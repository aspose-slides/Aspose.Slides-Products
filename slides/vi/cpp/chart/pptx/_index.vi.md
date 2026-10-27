---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 5370
title: Tạo biểu đồ PPTX bằng C++
url: /vi/cpp/chart/pptx/ 
description: Mã ví dụ C++ để tạo biểu đồ trong bản trình bày PPTX trên Windows và Linux.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tạo biểu đồ trong bản trình bày PPTX bằng C++" h2="Tạo biểu đồ trong bản trình bày PPTX bằng API phía máy chủ của Aspose.Slides for C++ mà không cần Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tạo biểu đồ PPTX bằng C++" %}}

Dùng [Aspose.Slides for C++](/slides/vi/cpp/) để tạo biểu đồ trong bản trình bày PPTX. Cài đặt gói từ [NuGet](https://www.nuget.org/packages/Aspose.Slides.Cpp/) hoặc dùng lệnh sau trong Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Lệnh" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tạo biểu đồ trong PPTX – C++" >}}
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

// Save the PPTX file.
presentation->Save(u"column_chart.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách tạo biểu đồ trong tệp PPTX bằng C++" intro="Tạo biểu đồ trong bản trình bày PPTX với Aspose.Slides for C++ chỉ bằng vài dòng mã." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tạo một đối tượng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Truy cập trang chiếu đầu tiên.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm biểu đồ với dữ liệu mặc định.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Đặt chỉ mục của trang dữ liệu biểu đồ.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lấy sổ làm việc dữ liệu biểu đồ.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Đặt tiêu đề biểu đồ.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Xóa các chuỗi dữ liệu và danh mục được tạo mặc định.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm chuỗi dữ liệu và danh mục.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lấy chuỗi đầu tiên của biểu đồ và điền dữ liệu cho chuỗi.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Đặt màu tô cho chuỗi.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hiển thị tên danh mục, tên chuỗi và giá trị trong nhãn dữ liệu của chuỗi thứ hai.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu tệp PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Yêu cầu hệ thống" intro="Aspose.Slides for C++ hỗ trợ các nền tảng và hệ điều hành chính. Hãy đảm bảo môi trường của bạn đáp ứng các điều kiện tiên quyết sau." %}}

-  Microsoft Windows, Linux, macOS hoặc hệ điều hành tương thích khác có môi trường chạy C++ được hỗ trợ.
-  Thư viện Aspose.Slides for C++ được tham chiếu trong dự án của bạn.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Được xây dựng bằng Aspose.Slides" title="Tạo biểu đồ PPTX trực tuyến" description="Ứng dụng Aspose.Slides Chart miễn phí được xây dựng bằng [Aspose.Slides for C++](https://products.aspose.com/slides/vi/cpp/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPTX của riêng bạn." button="Mở Aspose.Slides Chart" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides tạo biểu đồ trước khi bạn viết mã.
- Tạo biểu đồ từ dữ liệu Excel hoặc bảng.
- Tải xuống dưới dạng tệp PPTX hoặc hình ảnh.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

Tệp PPTX là tệp bản trình bày được tạo bằng Microsoft PowerPoint và các ứng dụng trình bày khác. Khác với định dạng nhị phân PPT cũ hơn, PPTX dựa trên Office Open XML. Bản trình bày gồm các trang chiếu có thể chứa văn bản, hình ảnh, định dạng, hiệu ứng động và phương tiện khác. Các trang chiếu được trình chiếu cho khán giả với thiết lập trình bày tùy chỉnh.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác được hỗ trợ cho biểu đồ" subTitle="Với C++, bạn cũng có thể tạo biểu đồ ở các định dạng khác." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/chart/ppt/" name="PPT" description="Bản trình bày PowerPoint 97-2003" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
