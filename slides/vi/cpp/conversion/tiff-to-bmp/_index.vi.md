---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi TIFF sang BMP thông qua ứng dụng C ++
weight: 8780
url: /vi/cpp/conversion/tiff-to-bmp/ 
description: Mã chuyển đổi C ++ mẫu cho tài liệu TIFF sang định dạng BMP. Sử dụng mã ví dụ để chuyển đổi hàng loạt TIFF sang BMP trong bất kỳ Ứng dụng C ++ nào.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi TIFF sang BMP qua C ++" h2="Chuyển đổi TIFF sang BMP hiệu suất cao bằng thư viện C ++ mà không cần cài đặt Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cách chuyển TIFF sang BMP bằng C ++" %}}

Để chuyển đổi TIFF thành BMP, chúng tôi sẽ sử dụng
 [Aspose.Slides dành cho C ++](https://products.aspose.com/slides/vi/cpp/)
 API là một API chuyển đổi và thao tác tài liệu giàu tính năng, mạnh mẽ và dễ sử dụng cho nền tảng C ++. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp, chỉ cần mở
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 quản lý gói, tìm kiếm
 Aspose.Slides.Cpp
 và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Yêu cầu" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã nguồn chuyển đổi TIFF sang BMP C ++" >}}
```cs
// Load the TIFF
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.tiff");

// Access the first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// User defined dimension
int desiredX = 1200;
int desiredY = 800;

// Getting scaled value  of X and Y
float ScaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float ScaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

// Create a custom scale image
auto bitmap = slide->GetThumbnail(ScaleX, ScaleY);

bitmap->Save(u"output.bmp", ImageFormat::get_Bmp());
	
//Iterate through each slide via index and convert

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Các bước chuyển đổi TIFF sang BMP qua C ++" intro="Các nhà phát triển C ++ có thể dễ dàng chuyển đổi tệp TIFF sang BMP chỉ trong một vài dòng mã." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp TIFF bằng Aspose.Slides cho Đối tượng trình bày C ++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chọn trang chiếu đầu tiên.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Đặt kích thước mong muốn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nhận hình thu nhỏ với kích thước mong muốn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức Save () có tham số đầu ra BMP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp BMP trong chương trình tương thích.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="yêu cầu hệ thống" intro="Trước khi chạy mã ví dụ chuyển đổi C ++, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau." %}}

- Microsoft Windows hoặc hệ điều hành tương thích với C ++ Runtime Environment dành cho Windows 32 bit, Windows 64 bit và Linux 64 bit.
- Aspose.Slides cho C ++ DLL được tham chiếu trong dự án của bạn.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ứng dụng miễn phí để chuyển đổi TIFF thành BMP"
  description="[Hãy thử ứng dụng Text To Gif miễn phí của chúng tôi](https://products.aspose.app/slides/text-to-gif/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi TIFF thành nhiều định dạng tệp khác, bao gồm một số định dạng được liệt kê bên dưới." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-emf/" name="TIFF TO EMF" description="Định dạng siêu tệp nâng cao" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-gif/" name="TIFF TO GIF" description="Định dạng trao đổi đồ họa" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-html/" name="TIFF TO HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-jpeg/" name="TIFF TO JPEG" description="Hình ảnh JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-odp/" name="TIFF TO ODP" description="Định dạng bản trình bày OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-otp/" name="TIFF TO OTP" description="Định dạng chuẩn OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-pdf/" name="TIFF TO PDF" description="Định dạng tài liệu di động" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-png/" name="TIFF TO PNG" description="Biểu đồ minh họa mạng lưới không dây" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-pot/" name="TIFF TO POT" description="Tệp mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-potm/" name="TIFF TO POTM" description="Tệp Mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-potx/" name="TIFF TO POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-pps/" name="TIFF TO PPS" description="Trình chiếu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-ppsm/" name="TIFF TO PPSM" description="Trình chiếu hỗ trợ macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-ppsx/" name="TIFF TO PPSX" description="Trình chiếu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-ppt/" name="TIFF TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-pptm/" name="TIFF TO PPTM" description="Tệp trình bày hỗ trợ macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-pptx/" name="TIFF TO PPTX" description="Định dạng bản trình bày XML mở" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-svg/" name="TIFF TO SVG" description="Đồ họa vector có thể mở rộng" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-xml/" name="TIFF TO XML" description="Ngôn ngữ đánh dấu có thể mở rộng" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/conversion/tiff-to-xps/" name="TIFF TO XPS" description="Thông số kỹ thuật giấy XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
