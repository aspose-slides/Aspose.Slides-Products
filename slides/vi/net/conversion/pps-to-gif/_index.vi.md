---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi PPS sang GIF qua C#
weight: 4000
url: /vi/net/conversion/pps-to-gif/ 
description: Mã mẫu để chuyển đổi PPS sang GIF C#. Sử dụng mã ví dụ API để chuyển đổi hàng loạt tệp PPS sang GIF trong VB.NET, Asp.NET hoặc bất kỳ ứng dụng dựa trên .NET nào.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi PPS sang GIF qua C#" h2="Xuất tệp PowerPoint® PPS sang GIF trên Nền tảng .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cách chuyển đổi PPS sang GIF bằng C#" %}}

Để chuyển đổi PPS thành GIF, chúng tôi sẽ sử dụng
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã mẫu này hiển thị Chuyển đổi PPS sang GIF C#" >}}
```cs
using (var presentation = new Presentation("template.pps"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in GIF format
        bitmap.Save(string.Format("Slide_{0}.gif", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Gif);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Các bước chuyển đổi PPS sang GIF qua C#" intro="Các nhà phát triển .NET có thể dễ dàng tải và chuyển đổi các tệp PPS sang GIF chỉ trong một vài dòng mã." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPS với một phiên bản của lớp Trình bày{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lặp lại từng Trang chiếu trong Bản trình bày{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tạo hình ảnh tỷ lệ đầy đủ dưới dạng Bitmap với mỗi lần lặp lại{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức Bitmap.Save với phần mở rộng tệp GIF & ImageFormat.Gif dưới dạng tham số{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="yêu cầu hệ thống" intro="Trước khi chạy mã nguồn mẫu chuyển đổi .NET, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau." %}}

- Microsoft Windows hoặc hệ điều hành tương thích với .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin Platforms.
- Môi trường phát triển như Microsoft Visual Studio.
- Aspose.Slides cho .NET DLL được tham chiếu trong dự án của bạn.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Được xây dựng bằng Aspose.Slides" title="Chuyển đổi PPS sang GIF trực tuyến" description="Ứng dụng Aspose.Slides Conversion miễn phí được xây dựng bằng [Aspose.Slides for .NET](https://products.aspose.com/slides/vi/net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPS của riêng bạn." button="Mở Aspose.Slides Conversion" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" upload="Thả hoặc tải lên tệp của bạn" saveAs="Lưu dưới dạng" convert="Chuyển đổi" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides chuyển đổi tệp trước khi bạn viết mã.
- Tải lên các tệp PPS và lưu chúng dưới dạng GIF.
- Tải xuống kết quả hoặc chuyển đổi thêm tệp.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PPS thành nhiều định dạng tệp khác, bao gồm một số định dạng được liệt kê bên dưới." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-bmp/" name="PPS TO BMP" description="Hình ảnh bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-emf/" name="PPS TO EMF" description="Định dạng siêu tệp nâng cao" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-html/" name="PPS TO HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-jpeg/" name="PPS TO JPEG" description="Hình ảnh JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-odp/" name="PPS TO ODP" description="Định dạng bản trình bày OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-otp/" name="PPS TO OTP" description="Định dạng chuẩn OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-pdf/" name="PPS TO PDF" description="Định dạng tài liệu di động" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-png/" name="PPS TO PNG" description="Biểu đồ minh họa mạng lưới không dây" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-pot/" name="PPS TO POT" description="Tệp mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-potm/" name="PPS TO POTM" description="Tệp Mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-potx/" name="PPS TO POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Trình chiếu hỗ trợ macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="Trình chiếu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-pptm/" name="PPS TO PPTM" description="Tệp trình bày hỗ trợ macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Định dạng bản trình bày XML mở" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-svg/" name="PPS TO SVG" description="Đồ họa vector có thể mở rộng" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-swf/" name="PPS TO SWF" description="Định dạng SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Định dạng hình ảnh được gắn thẻ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/conversion/pps-to-xps/" name="PPS TO XPS" description="Thông số kỹ thuật giấy XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
