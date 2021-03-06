---
title: Bảo vệ và khóa tài liệu ODP qua Java
weight: 2650
url: /vi/java/protect/odp/ 
description: Mã mẫu Java để khóa tệp ODP bằng mật khẩu trên Môi trường thời gian chạy Java cho Ứng dụng JSP / JSF và Ứng dụng máy tính để bàn.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Mã hóa tệp ODP qua Java" h2="Các bản trình bày PowerPoint được bảo vệ bằng mật khẩu bao gồm định dạng ODP sử dụng Thư viện .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java/" installationsDocsLink="https://docs.aspose.com/slides/java/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java/" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Cách bảo mật tệp ODP bằng Java" %}}

 Để bảo vệ tệp ODP, chúng tôi sẽ sử dụng
 [Aspose.Slides dành cho Java](https://products.aspose.com/slides/vi/java)
 API là một API mã hóa giàu tính năng, mạnh mẽ và dễ sử dụng cho nền tảng Java. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp từ
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 và cài đặt nó trong dự án dựa trên Maven của bạn bằng cách thêm các cấu hình sau vào pom.xml.

{{% blocks/products/pf/agp/code-block title="Aspose.Slides" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Kho" offSpacer="true" %}}

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


{{< blocks/products/pf/agp/feature-section-col title="Các bước bảo vệ tệp ODP qua Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bảo vệ tài liệu bằng cách sử dụng API Aspose.Slides có thể được thực hiện chỉ với vài dòng mã." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Khởi tạo một đối tượng Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Đặt phương thức Mật khẩu getProtectionManager (). Encode (.)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu bản trình bày được bảo vệ ở định dạng ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides cho Java hỗ trợ trên tất cả các nền tảng và Hệ điều hành chính. Vui lòng đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với Môi trường thời gian chạy Java cho Ứng dụng JSP / JSF và Ứng dụng máy tính để bàn.
- Nhận phiên bản mới nhất của Aspose.Slides cho Java trực tiếp từ
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Sự phụ thuộc" offSpacer="" %}}

```cs

 //Instantiate a Presentation object that represents a ODP file

Presentation pres = new Presentation();

//Setting Password

pres.getProtectionManager().encrypt("pass");

//Save your presentation to a ODP file

pres.save(dataDir + "protected.odp", com.aspose.slides.SaveFormat.Odp);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Giới thiệu về Aspose.Slides cho Java API" %}}

 API Aspose.Slides có thể được sử dụng để đọc, viết, thao tác và chuyển đổi tài liệu Microsoft PowerPoint sang PDF, XPS, HTML, TIFF, ODP và nhiều định dạng khác. Người ta có thể tạo các tệp mới từ đầu và lưu chúng ở các định dạng được hỗ trợ có liên quan. Aspose.Slides là một API độc lập để tạo, phân tích cú pháp hoặc thao tác với các bản trình bày, trang trình bày và các phần tử và nó không phụ thuộc vào bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Protect ODP" sectionDescription="Check our live demos to [encrypt ODP files](https://products.aspose.app/slides/protect/odp) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload ODP file and hit the \"Unlock\" button" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant ODP file from the link" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice).

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các tài liệu bảo vệ được hỗ trợ khác" subTitle="Sử dụng Java, người ta có thể bảo vệ các tệp khác bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/protect/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/protect/pptx/" name="PPTX" description="Định dạng bản trình bày XML mở" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}