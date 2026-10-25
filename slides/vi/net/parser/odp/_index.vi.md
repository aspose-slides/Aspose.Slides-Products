---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3070
title: Trích xuất văn bản từ tệp ODP bằng .NET
url: /vi/net/parser/odp/ 
description: Mã nguồn C# để trích xuất văn bản từ tệp ODP bằng .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Phân tích tệp ODP bằng C#" h2="Trích xuất văn bản và kiểm tra định dạng văn bản trong tệp ODP bằng API .NET phía máy chủ."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Phân tích tệp ODP bằng C#" %}}

Dùng [Aspose.Slides for .NET](/slides/vi/net/) để trích xuất văn bản từ bản trình bày ODP. Cài đặt gói từ [NuGet](https://www.nuget.org/packages/aspose.slides.net) hoặc chạy lệnh sau trong Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Lệnh" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Phân tích tệp ODP – C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách phân tích tệp ODP trong C#" intro="Phân tích tài liệu cơ bản bằng API [Aspose.Slides for .NET](/slides/vi/net/) chỉ cần vài dòng mã." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp ODP bằng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lấy các khung văn bản bằng `SlideUtil.GetAllTextFrames`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Duyệt qua các khung văn bản, đoạn văn và phần văn bản.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Đọc các thuộc tính `Text`, `FontHeight` và `LatinFont.FontName` khi cần.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Yêu cầu hệ thống" intro="Cần có môi trường chạy .NET được hỗ trợ và tham chiếu gói Aspose.Slides for .NET. Bạn có thể dùng Visual Studio hoặc môi trường phát triển C# tương thích khác." %}}

- Môi trường tương thích với .NET Framework, .NET, Mono hoặc Xamarin
- Môi trường phát triển C# như Visual Studio
- Aspose.Slides for .NET được cài đặt từ NuGet

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Được xây dựng bằng Aspose.Slides" title="Trích xuất văn bản và hình ảnh trực tuyến" description="Ứng dụng Aspose.Slides Parser miễn phí được xây dựng bằng [Aspose.Slides for .NET](https://products.aspose.com/slides/vi/net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp ODP của riêng bạn." button="Mở Aspose.Slides Parser" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem Aspose.Slides đọc tệp của bạn như thế nào trước khi viết mã.
- Tải lên tệp ODP và nhận văn bản cùng hình ảnh của tệp.
- Tải xuống tất cả dưới dạng một tệp ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

ODP files use the OpenDocument Presentation format. A presentation contains slides with text, images, formatting, animations, and other media. Applications that support the OpenDocument format, such as OpenOffice and StarOffice, can open ODP files.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng phân tích khác được hỗ trợ" subTitle="Với C#, bạn cũng có thể phân tích các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/parser/ppt/" name="PPT" description="Bản trình bày PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/parser/pptx/" name="PPTX" description="Bản trình bày PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
