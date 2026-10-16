---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi PPSX sang BMP qua C#
weight: 5400
url: /vi/net/conversion/ppsx-to-bmp/ 
description: Mã mẫu cho chuyển đổi PPSX sang BMP C#. Sử dụng mã ví dụ API cho hàng loạt tệp PPSX sang chuyển đổi BMP trong VB.NET, Asp.NET hoặc bất kỳ ứng dụng dựa trên .NET nào.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi PPSX sang BMP qua C#" h2="Xuất tệp PowerPoint® PPSX sang BMP trên Nền tảng .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cách chuyển đổi PPSX sang BMP bằng C#" %}}

Để chuyển đổi PPSX thành BMP, chúng tôi sẽ sử dụng
 [Aspose.Slides dành cho .NET](https://products.aspose.com/slides/vi/net)
 API là một API chuyển đổi và thao tác tài liệu giàu tính năng, mạnh mẽ và dễ sử dụng cho nền tảng C#. Mở
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 quản lý gói, tìm kiếm
 Aspose.Slides
 và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Lệnh Bảng điều khiển Trình quản lý Gói" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã mẫu này hiển thị Chuyển đổi PPSX sang BMP C#" >}}
```cs
using (var presentation = new Presentation("template.ppsx"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in BMP format
        bitmap.Save(string.Format("Slide_{0}.bmp", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Bmp);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Các bước chuyển đổi PPSX sang BMP qua C#" intro="Các nhà phát triển .NET có thể dễ dàng tải và chuyển đổi các tệp PPSX sang BMP chỉ trong một vài dòng mã." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPSX với một phiên bản của lớp Trình bày{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lặp lại từng Trang chiếu trong Bản trình bày{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tạo hình ảnh tỷ lệ đầy đủ dưới dạng Bitmap với mỗi lần lặp lại{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức Bitmap.Save với phần mở rộng tệp BMP & ImageFormat.Bmp dưới dạng tham số{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="yêu cầu hệ thống" intro="Trước khi chạy mã nguồn mẫu chuyển đổi .NET, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau." %}}

- Microsoft Windows hoặc hệ điều hành tương thích với .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin Platforms.
- Môi trường phát triển như Microsoft Visual Studio.
- Aspose.Slides cho .NET DLL được tham chiếu trong dự án của bạn.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ứng dụng miễn phí để chuyển đổi PPSX thành BMP"
  description="[Hãy thử ứng dụng miễn phí của chúng tôi để chuyển đổi PPT sang BMP](https://products.aspose.app/slides/conversion/ppt-to-bmp)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PPSX thành nhiều định dạng tệp khác, bao gồm một số định dạng được liệt kê dưới đây." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="Định dạng siêu tệp nâng cao" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Định dạng trao đổi đồ họa" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="Hình ảnh JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="Định dạng bản trình bày OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Định dạng chuẩn OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Định dạng tài liệu di động" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Biểu đồ minh họa mạng lưới không dây" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Tệp mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Tệp Mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="Trình chiếu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Trình chiếu hỗ trợ macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Tệp trình bày hỗ trợ macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Định dạng bản trình bày XML mở" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Đồ họa vector có thể mở rộng" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="Định dạng SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Định dạng hình ảnh được gắn thẻ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="Thông số kỹ thuật giấy XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
