---
title: Chuyển đổi PPSM sang PPSX qua Java
weight: 6680
url: /vi/java/conversion/ppsm-to-ppsx/ 
description: Mã chuyển đổi Java mẫu cho định dạng PPSM sang tệp PPSX. Sử dụng mã ví dụ này để xuất bản trình bày PowerPoint & OpenOffice sang PPSX trong bất kỳ Ứng dụng dựa trên Java trên Web hoặc Máy tính để bàn nào.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển đổi PPSM sang PPSX qua Java" h2="Chuyển đổi PPSM sang PPSX Java để chuyển đổi một hoặc nhiều trang sang PPSX bằng cách sử dụng thư viện Java tại chỗ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Cách chuyển đổi PPSM sang PPSX bằng Java" %}}

 Để hiển thị PPSM thành PPSX, chúng tôi sẽ sử dụng
 [Aspose.Slides dành cho Java](https://products.aspose.com/slides/java)
 API là một API chuyển đổi giàu tính năng, mạnh mẽ và dễ sử dụng cho nền tảng Java. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp từ
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 và cài đặt nó trong dự án dựa trên Maven của bạn bằng cách thêm các cấu hình sau vào pom.xml.

{{% blocks/products/pf/agp/code-block title="Kho" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Sự phụ thuộc" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-slides</artifactId>
<version>version of aspose-slides API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các bước chuyển đổi PPSM sang PPSX qua Java" %}}

{{% blocks/products/pf/agp/text %}}

 Các nhà phát triển Java có thể dễ dàng chuyển đổi tệp PPSM sang PPSX chỉ trong một vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp PPSM với một phiên bản của lớp Trình bày
1. Gọi phương thức Presentation.save trong khi chỉ định đường dẫn tệp đầu ra & SaveFormat
1. Tệp PPSX sẽ được lưu theo đường dẫn được chỉ định

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Trước khi chạy mã mẫu chuyển đổi Java, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với Môi trường thời gian chạy Java cho Ứng dụng JSP / JSF và Ứng dụng máy tính để bàn.
- Tải phiên bản mới nhất của Aspose.Slides cho Java trực tiếp từ Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã nguồn chuyển đổi PPSM sang PPSX Java" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("template.ppsm");
// save the presentation as PPSX
presentation.save("output.ppsx", SaveFormat.Ppsx);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="ppsm-to-ppsx"
        sectionTitle="Ứng dụng miễn phí để chuyển đổi PPSM thành PPSX" 
        sectionDescription="[Hãy thử ứng dụng Collage miễn phí của chúng tôi](https://products.aspose.app/slides/collage/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PPSM thành nhiều định dạng tệp khác, bao gồm một số định dạng được liệt kê dưới đây." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Hình ảnh bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Định dạng trao đổi đồ họa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-jpeg/" name="PPSM TO JPEG" description="Hình ảnh JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="Định dạng bản trình bày OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="Định dạng chuẩn OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Định dạng tài liệu di động" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-png/" name="PPSM TO PNG" description="Biểu đồ minh họa mạng lưới không dây" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Tệp mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Tệp Mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="Trình chiếu PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Tệp trình bày hỗ trợ macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Định dạng bản trình bày XML mở" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Đồ họa vector có thể mở rộng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="Định dạng SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Định dạng hình ảnh được gắn thẻ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="Thông số kỹ thuật giấy XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}