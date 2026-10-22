---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chỉnh sửa tệp PPS qua .NET
url: /vi/net/editor/pps/ 
description: Mã nguồn C# để chỉnh sửa tài liệu PPS trên Nền tảng .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chỉnh sửa Định dạng PPS trong C#" h2="Chỉnh sửa tài liệu PPS nguyên bản và hiệu suất cao bằng cách sử dụng Aspose.Slides phía máy chủ cho các API .NET mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cách chỉnh sửa tệp PPS bằng C#" %}}

Để chỉnh sửa tệp PPS, chúng tôi sẽ sử dụng API <a href="https://products.aspose.com/slides/vi/net"> Aspose.Slides dành cho .NET </a>, đây là một API mạnh mẽ, giàu tính năng và API dễ sử dụng cho nền tảng C# cho bất kỳ trình soạn thảo nào. Mở trình quản lý gói <a href="https://www.nuget.org/packages/aspose.slides.net"> NuGet </a>, tìm kiếm <b> Aspose.Slides </b> và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Yêu cầu" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Chỉnh sửa tệp PPS - C#" >}}
```cs
using var presentation = new Presentation("document.pps");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.pps", SaveFormat.Pps);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Các bước chỉnh sửa tệp PPS trong C#" intro="Chỉnh sửa tài liệu cơ bản với [Aspose.Slides dành cho .NET](https://products.aspose.com/slides/vi/net) Các API có thể được thực hiện chỉ với vài dòng mã." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPS bằng đối tượng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Truy cập trang chiếu và hình dạng đích thông qua các biến.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cập nhật văn bản thông qua `TextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu bản trình bày đã chỉnh sửa bằng `SaveFormat.Pps`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="yêu cầu hệ thống" intro="Các API của chúng tôi được hỗ trợ trên tất cả các nền tảng và Hệ điều hành chính. Trước khi thực hiện mã bên dưới, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau trên hệ thống của mình." %}}

- Microsoft Windows hoặc hệ điều hành tương thích với .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin Platforms
- Môi trường phát triển như Microsoft Visual Studio
- Aspose.Slides cho .NET DLL được tham chiếu trong dự án của bạn - Cài đặt từ NuGet bằng cách sử dụng nút Tải xuống ở trên

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPS" readMoreLink="https://docs.fileformat.com/presentation/pps/" %}}

PPS, PowerPoint Slide Show, files are created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003. The more latest version of this file format is PPSX which is based on Office OpenXML standards. PPS files can still be read by latest versions of Microsoft PowerPoint, but newly created files can only be saved in PPSX file format. When a PPS file is shared with another user and opened, it starts as Powerpoint show unlike PPT file which opens in editable mode.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
