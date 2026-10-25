---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 460
title: Trích xuất văn bản từ bản trình bày ODP bằng C++
url: /vi/cpp/parser/odp/ 
description: Trích xuất văn bản từ bản trình bày ODP trong C++. Dùng Aspose.Slides for C++ để phân tích trang chiếu, khung văn bản, đoạn văn và phần văn bản.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Phân tích bản trình bày ODP trong C++" h2="Dùng Aspose.Slides for C++ để trích xuất văn bản từ trang chiếu mà không cần Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Phân tích tệp ODP bằng C++" %}}

Dùng Aspose.Slides for C++ để phân tích tệp bản trình bày ODP và trích xuất văn bản từ trang chiếu. API cung cấp văn bản trang chiếu qua `SlideUtil::GetAllTextBoxes`, `ITextFrame`, `IParagraph` và `IPortion`, vì vậy bạn có thể đọc nội dung văn bản mà không cần tự động hóa Microsoft PowerPoint. Cài đặt gói [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) từ NuGet hoặc dùng lệnh bên dưới trong Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Lệnh" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Phân tích tệp ODP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách phân tích tệp ODP trong C++" intro="Trích xuất văn bản từ tệp ODP bằng Aspose.Slides for C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp ODP bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lấy các đối tượng `ITextFrame` từ trang chiếu đầu tiên bằng `SlideUtil::GetAllTextBoxes`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Duyệt qua các đối tượng `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Duyệt qua các đối tượng `IParagraph` trong mỗi `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Duyệt qua các đối tượng `IPortion` trong mỗi `IParagraph`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Đọc văn bản bằng `get_Text`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Yêu cầu hệ thống" intro="Aspose.Slides for C++ hỗ trợ các nền tảng máy tính và máy chủ chính. Hãy đảm bảo dự án của bạn đáp ứng các điều kiện tiên quyết sau." %}}

-  Microsoft Windows, Linux, macOS hoặc hệ điều hành tương thích khác có môi trường chạy C++ được hỗ trợ.
-  Thư viện Aspose.Slides for C++ được tham chiếu trong dự án của bạn.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Được xây dựng bằng Aspose.Slides" title="Trích xuất văn bản và hình ảnh trực tuyến" description="Ứng dụng Aspose.Slides Parser miễn phí được xây dựng bằng [Aspose.Slides for C++](https://products.aspose.com/slides/vi/cpp/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp ODP của riêng bạn." button="Mở Aspose.Slides Parser" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem Aspose.Slides đọc tệp của bạn như thế nào trước khi viết mã.
- Tải lên tệp ODP và nhận văn bản cùng hình ảnh của tệp.
- Tải xuống tất cả dưới dạng một tệp ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

An ODP file is an OpenDocument presentation file used by applications such as OpenOffice Impress and LibreOffice Impress. It stores slides, text, images, formatting, animations, and other presentation content in an open XML-based package.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng phân tích khác được hỗ trợ" subTitle="Với C++, bạn cũng có thể phân tích các định dạng bản trình bày khác." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/parser/ppt/" name="PPT" description="Bản trình bày PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/parser/pptx/" name="PPTX" description="Bản trình bày PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
