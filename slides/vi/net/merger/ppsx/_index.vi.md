---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Hợp nhất các tệp PPSX qua .NET
weight: 6100
url: /vi/net/merger/ppsx/ 
description: Mã nguồn C# để kết hợp các tài liệu PPSX trên .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin Platforms.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Hợp nhất các định dạng PPSX trong C#" h2="Hợp nhất tài liệu PPSX nguyên bản và hiệu suất cao bằng cách sử dụng Aspose.Slides phía máy chủ cho các API .NET, mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Open Office, Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cách hợp nhất tệp PPSX bằng C#" %}}

Để hợp nhất tệp PPSX, chúng tôi sẽ sử dụng
 [Aspose.Slides dành cho .NET](https://products.aspose.com/slides/vi/net)
 API là một API hợp nhất và thao tác tài liệu giàu tính năng, mạnh mẽ và dễ sử dụng cho nền tảng C#. Mở
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 quản lý gói, tìm kiếm
 ** Aspose.Slides **
 và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Yêu cầu" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Hợp nhất các tệp PPSX - C#" >}}
```cs
var ps1 = new Presentation("presen1.ppsx");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first PPSX presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Các bước để hợp nhất tệp PPSX trong C#" intro="Việc hợp nhất và nối tài liệu cơ bản với API [Aspose.Slides for .NET](https://products.aspose.com/slides/vi/net) có thể được thực hiện chỉ với vài dòng mã." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tất cả các tệp PPSX với đường dẫn đầy đủ.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tạo một tài liệu làm tệp cơ sở{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức liên quan để nối và hợp nhất từng tệp một.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức Save () và chuyển tên tệp (đường dẫn đầy đủ) và định dạng (PPSX) làm tham số.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Giờ đây, bạn có thể mở và sử dụng tệp PPSX trong Microsoft Office, Adobe PDF hoặc bất kỳ chương trình tương thích nào khác.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="yêu cầu hệ thống" intro="Các API của chúng tôi được hỗ trợ trên tất cả các nền tảng và Hệ điều hành chính. Trước khi thực hiện mã bên dưới, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau trên hệ thống của mình." %}}

- Microsoft Windows hoặc hệ điều hành tương thích với .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin Platforms
- Môi trường phát triển như Microsoft Visual Studio
- Aspose.Slides cho .NET DLL được tham chiếu trong dự án của bạn - Cài đặt từ NuGet bằng cách sử dụng nút Tải xuống ở trên

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Hợp nhất các tệp PDF trực tuyến"
  description="[Cách hợp nhất PDF trong Python](https://products.aspose.com/slides/vi/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSX" readMoreLink="https://docs.fileformat.com/presentation/ppsx/" %}}

Tệp PPSX là bản trình chiếu PowerPoint theo định dạng Open XML, được tạo bằng Microsoft PowerPoint 2007 trở lên. Đây là định dạng kế thừa dựa trên Open XML của định dạng PPS mà PowerPoint 97–2003 sử dụng. Khác với tệp PPTX vốn mặc định mở ở chế độ chỉnh sửa, tệp PPSX mở trực tiếp dưới dạng trình chiếu. Tệp giữ nguyên thứ tự trang chiếu và có thể chứa hình ảnh, âm thanh cùng các phương tiện nhúng khác.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng hợp nhất được hỗ trợ khác" subTitle="Sử dụng C#, Người ta cũng có thể hợp nhất nhiều định dạng tệp khác bao gồm." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/merger/odp/" name="ODP" description="Định dạng bản trình bày OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/merger/otp/" name="OTP" description="Định dạng chuẩn OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/merger/pot/" name="POT" description="Tệp mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/merger/potm/" name="POTM" description="Tệp Mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/merger/potx/" name="POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/merger/pps/" name="PPS" description="Trình chiếu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/merger/ppsm/" name="PPSM" description="Trình chiếu hỗ trợ macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/merger/pptm/" name="PPTM" description="Tệp trình bày hỗ trợ macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/net/merger/pptx/" name="PPTX" description="Định dạng bản trình bày XML mở" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
