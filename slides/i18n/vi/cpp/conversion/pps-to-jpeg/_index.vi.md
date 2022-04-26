---
title: Chuyển đổi PPS sang JPEG thông qua ứng dụng C ++
weight: 8730
url: /vi/cpp/conversion/pps-to-jpeg/ 
description: Mã chuyển đổi C ++ mẫu cho tài liệu PPS sang định dạng JPEG. Sử dụng mã ví dụ để chuyển đổi hàng loạt PPS sang JPEG trong bất kỳ Ứng dụng C ++ nào.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển đổi PPS sang JPEG thông qua C ++" h2="Chuyển đổi PPS sang JPEG hiệu suất cao bằng thư viện C ++ mà không cần cài đặt Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách chuyển đổi PPS sang JPEG bằng C ++" %}}

 Để chuyển đổi PPS sang JPEG, chúng tôi sẽ sử dụng
 [Aspose.Slides dành cho C ++](https://products.aspose.com/slides/cpp)
 API là một API chuyển đổi và thao tác tài liệu giàu tính năng, mạnh mẽ và dễ sử dụng cho nền tảng C ++. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp, chỉ cần mở
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 quản lý gói, tìm kiếm
 Aspose.Slides.Cpp
 và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{% blocks/products/pf/agp/code-block title="Yêu cầu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các bước chuyển đổi PPS sang JPEG thông qua C ++" %}}

{{% blocks/products/pf/agp/text %}}

 Các nhà phát triển C ++ có thể dễ dàng chuyển đổi tệp PPS sang JPEG chỉ trong một vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp PPS bằng Aspose.Slides cho Đối tượng trình bày C ++.
1. Chọn trang chiếu đầu tiên.
1. Đặt kích thước mong muốn.
1. Nhận hình thu nhỏ với kích thước mong muốn.
1. Gọi phương thức Save () có tham số đầu ra JPEG.
1. Mở tệp JPEG trong chương trình tương thích.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Trước khi chạy mã ví dụ chuyển đổi C ++, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với C ++ Runtime Environment dành cho Windows 32 bit, Windows 64 bit và Linux 64 bit.
- Aspose.Slides cho C ++ DLL được tham chiếu trong dự án của bạn.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã nguồn chuyển đổi PPS sang JPEG C ++" offSpacer="" %}}

```cs
// Load the PPS
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.pps");

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

bitmap->Save(u"output.jpeg", ImageFormat::get_Jpeg());
	
//Iterate through each slide via index and convert

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="pps-to-jpeg"
        sectionTitle="Ứng dụng miễn phí để chuyển đổi PPS thành JPEG" 
        sectionDescription="[Hãy thử ứng dụng miễn phí của chúng tôi để chuyển đổi PPT sang JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PPS thành nhiều định dạng tệp khác, bao gồm một số định dạng được liệt kê bên dưới." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-bmp/" name="PPS TO BMP" description="Hình ảnh bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-emf/" name="PPS TO EMF" description="Định dạng siêu tệp nâng cao" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-gif/" name="PPS TO GIF" description="Định dạng trao đổi đồ họa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-html/" name="PPS TO HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-odp/" name="PPS TO ODP" description="Định dạng bản trình bày OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-otp/" name="PPS TO OTP" description="Định dạng chuẩn OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-pdf/" name="PPS TO PDF" description="Định dạng tài liệu di động" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-png/" name="PPS TO PNG" description="Biểu đồ minh họa mạng lưới không dây" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-pot/" name="PPS TO POT" description="Tệp mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-potm/" name="PPS TO POTM" description="Tệp Mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-potx/" name="PPS TO POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Trình chiếu hỗ trợ macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="Trình chiếu PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-pptm/" name="PPS TO PPTM" description="Tệp trình bày hỗ trợ macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Định dạng bản trình bày XML mở" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-svg/" name="PPS TO SVG" description="Đồ họa vector có thể mở rộng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Định dạng hình ảnh được gắn thẻ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-xml/" name="PPS TO XML" description="Ngôn ngữ đánh dấu có thể mở rộng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pps-to-xps/" name="PPS TO XPS" description="Thông số kỹ thuật giấy XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}