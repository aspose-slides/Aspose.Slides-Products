---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi PPT sang PNG qua C#
weight: 8810
url: /vi/net/conversion/ppt-to-png/ 
description: Mã mẫu để chuyển đổi PPT sang PNG C#. Sử dụng mã ví dụ API để chuyển đổi hàng loạt tệp PPT sang PNG trong VB.NET, Asp.NET hoặc bất kỳ ứng dụng dựa trên .NET nào.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi PPT sang PNG qua C#" h2="Xuất tệp PowerPoint® PPT sang PNG trên Nền tảng .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cách chuyển đổi PPT sang PNG bằng C#" %}}

Để chuyển đổi PPT sang PNG, chúng tôi sẽ sử dụng
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã mẫu này hiển thị Chuyển đổi PPT sang PNG C#" >}}
```cs
using (var presentation = new Presentation("template.ppt"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in PNG format
        bitmap.Save(string.Format("Slide_{0}.png", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Png);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Các bước chuyển đổi PPT sang PNG qua C#" intro="Các nhà phát triển .NET có thể dễ dàng tải và chuyển đổi các tệp PPT sang PNG chỉ trong một vài dòng mã." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPT với một phiên bản của lớp Trình bày{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lặp lại từng Trang chiếu trong Bản trình bày{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tạo hình ảnh tỷ lệ đầy đủ dưới dạng Bitmap với mỗi lần lặp lại{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức Bitmap.Save với phần mở rộng tệp PNG & ImageFormat.Png dưới dạng tham số{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="yêu cầu hệ thống" intro="Trước khi chạy mã nguồn mẫu chuyển đổi .NET, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau." %}}

- Microsoft Windows hoặc hệ điều hành tương thích với .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin Platforms.
- Môi trường phát triển như Microsoft Visual Studio.
- Aspose.Slides cho .NET DLL được tham chiếu trong dự án của bạn.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="ppt-to-png"
  title="Ứng dụng miễn phí để chuyển đổi PPT thành PNG"
  description="[Hãy thử ứng dụng miễn phí của chúng tôi để chuyển đổi PPT sang PNG](https://products.aspose.app/slides/conversion/ppt-to-png)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PPT thành nhiều định dạng tệp khác, bao gồm một số định dạng được liệt kê dưới đây." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Hình ảnh bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-emf/" name="PPT TO EMF" description="Định dạng siêu tệp nâng cao" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-gif/" name="PPT TO GIF" description="Định dạng trao đổi đồ họa" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-html/" name="PPT TO HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" description="Hình ảnh JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-odp/" name="PPT TO ODP" description="Định dạng bản trình bày OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-otp/" name="PPT TO OTP" description="Định dạng chuẩn OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-pdf/" name="PPT TO PDF" description="Định dạng tài liệu di động" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-pot/" name="PPT TO POT" description="Tệp mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-potm/" name="PPT TO POTM" description="Tệp Mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-potx/" name="PPT TO POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-pps/" name="PPT TO PPS" description="Trình chiếu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Trình chiếu hỗ trợ macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="Trình chiếu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Tệp trình bày hỗ trợ macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Định dạng bản trình bày XML mở" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-svg/" name="PPT TO SVG" description="Đồ họa vector có thể mở rộng" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-swf/" name="PPT TO SWF" description="Định dạng SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Định dạng hình ảnh được gắn thẻ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/ppt-to-xps/" name="PPT TO XPS" description="Thông số kỹ thuật giấy XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
