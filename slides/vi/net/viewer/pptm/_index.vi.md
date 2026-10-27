---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Xem PPTM bằng C#
keywords: Xem PPTM, Mở PPTM, Trình xem PPTM, PPTM, PowerPoint, API C#, Thư viện .NET
weight: 4190
url: /vi/net/viewer/pptm/ 
description: Xem tệp PPTM bằng C#. Dùng Aspose.Slides for .NET để mở tệp bản trình bày và lưu dưới dạng HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Xem PPTM bằng C#" h2="API C# để mở tệp PPTM và lưu dưới dạng HTML đáp ứng."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Xem PPTM với Aspose.Slides" %}}

Để xem tệp PPTM, hãy dùng [Aspose.Slides for .NET](https://products.aspose.com/slides/vi/net/), một API mạnh mẽ, nhiều tính năng và dễ sử dụng cho C#. Mở trình quản lý gói [NuGet](https://www.nuget.org/packages/aspose.slides.net), tìm **Aspose.Slides** và cài đặt. Bạn cũng có thể chạy lệnh sau trong Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Lệnh Package Manager Console" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Với [**Aspose.Slides for .NET**](/slides/vi/net/), bạn có thể tải tệp PPTM và lưu dưới dạng HTML đáp ứng chỉ với vài dòng mã.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã C# để xem PPTM" >}}
```cs
using var presentation = new Presentation("presentation.pptm");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách xem PPTM bằng C#" intro="Aspose.Slides giúp nhà phát triển xem tệp PPTM chỉ với vài dòng mã." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt **Aspose.Slides for .NET**. Xem [**Cài đặt**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm thư viện làm tham chiếu trong dự án của bạn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp `PPTM` bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tạo đối tượng `ResponsiveHtmlController` để xuất HTML đáp ứng.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tạo đối tượng `HtmlOptions` và đặt thuộc tính `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu tệp PPTM dưới dạng HTML bằng `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Yêu cầu hệ thống" intro="Aspose.Slides for .NET hỗ trợ mọi hệ điều hành phổ biến. Hãy đảm bảo bạn đáp ứng các điều kiện tiên quyết sau." %}}

- Microsoft Windows hoặc hệ điều hành tương thích với .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin
- Môi trường phát triển như Microsoft Visual Studio
- Tham chiếu tới Aspose.Slides for .NET trong dự án của bạn

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Được xây dựng bằng Aspose.Slides" title="Xem tệp PPTM trực tuyến" description="Ứng dụng Aspose.Slides Viewer miễn phí được xây dựng bằng [Aspose.Slides for .NET](https://products.aspose.com/slides/vi/net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPTM của riêng bạn." button="Mở Aspose.Slides Viewer" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem Aspose.Slides hiển thị tệp của bạn như thế nào trước khi viết mã.
- Tải lên tệp PPTM và xem các trang chiếu ngay lập tức.
- Hoạt động trên máy tính và thiết bị di động, không cần PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTM" readMoreLink="https://docs.fileformat.com/presentation/pptm/" %}}

Các tệp có phần mở rộng `.PPTM` là tệp bản trình bày hỗ trợ macro, được giới thiệu cùng Microsoft PowerPoint 2007. Chúng tương tự tệp PPTX, nhưng tệp PPTM có thể lưu mã macro VBA, còn tệp PPTX thì không. Tệp PPTM có thể được mở và chỉnh sửa trong Microsoft PowerPoint. Định dạng liên quan PPSM mặc định mở ở dạng xem Trình chiếu nhưng cũng có thể được mở trong PowerPoint để chỉnh sửa. Giống như tệp PPTX, tệp PPTM có thể chứa văn bản, hình ảnh, video, biểu đồ và nội dung trình bày khác.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Xem các tệp khác" subTitle="Bạn cũng có thể mở và xem bản trình bày ở các định dạng khác." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/viewer/odp/" name="ODP" description="Bản trình bày OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/viewer/otp/" name="OTP" description="Mẫu bản trình bày OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/viewer/pot/" name="POT" description="Mẫu PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/viewer/potm/" name="POTM" description="Mẫu PowerPoint hỗ trợ macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/viewer/potx/" name="POTX" description="Mẫu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/viewer/pps/" name="PPS" description="Bản trình chiếu PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/viewer/ppsm/" name="PPSM" description="Bản trình chiếu PowerPoint hỗ trợ macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/viewer/ppsx/" name="PPSX" description="Bản trình chiếu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/viewer/ppt/" name="PPT" description="Bản trình bày PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/viewer/pptx/" name="PPTX" description="Bản trình bày PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
