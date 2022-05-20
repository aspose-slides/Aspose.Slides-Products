---
title: Tài liệu PPT Watermark qua Java
weight: 6020
url: /vi/java/watermark/ppt/ 
description: Mã mẫu Java để thêm hoặc xóa hình mờ vào tệp PPT trên Môi trường thời gian chạy Java cho Ứng dụng JSP / JSF và Ứng dụng máy tính để bàn.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Thêm hình mờ văn bản vào PPT qua Java" h2="Xây dựng các ứng dụng Java của riêng bạn để đánh dấu các tệp PPT bằng cách sử dụng các API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Cách tạo hình mờ tệp PPT bằng Java" %}}

 Để làm mờ tệp PPT, chúng tôi sẽ sử dụng
 [Aspose.Slides dành cho Java](https://products.aspose.com/slides/vi/java)
 API là một API watermarking giàu tính năng, mạnh mẽ và dễ sử dụng cho nền tảng Java. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp từ
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


{{< blocks/products/pf/agp/feature-section-col title="Các bước để thêm hình mờ vào PPT qua Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải tệp PPT bằng lớp Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lặp qua tất cả các trang trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm văn bản bằng addTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Đặt tất cả các tùy chọn có liên quan như màu sắc, fillType và hơn thế nữa
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu tài liệu
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides cho Java hỗ trợ trên tất cả các nền tảng và Hệ điều hành chính. Vui lòng đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Thêm hình mờ vào PPT - Java" offSpacer="" %}}

```cs

Presentation pres = new Presentation("TestPres.ppt");

for(ISlide slide:pres.getSlides()){
    IAutoShape ashp = slide.getShapes()
                    .addAutoShape(ShapeType.Rectangle,50, 50, 500, 500);
    ashp.addTextFrame("Watermark Text");

    ashp.getTextFrame().getParagraphs().get_Item(0).getPortions()
                        .get_Item(0).getPortionFormat().getFillFormat()
                        .setFillType(FillType.Solid);
    ashp.getTextFrame().getParagraphs().get_Item(0).getPortions()
                        .get_Item(0).getPortionFormat().getFillFormat()
                        .getSolidFillColor().setColor(Color.GRAY);
    ashp.getTextFrame().getParagraphs().get_Item(0).getPortions()
                        .get_Item(0).getPortionFormat().setFontHeight(25);

    // Change the line color of the rectangle to White
    ashp.getShapeStyle().getLineColor().setColor(Color.WHITE);
    ashp.getShapeStyle().setLineStyleIndex(LineStyle.ThinThin);

    // Remove any fill formatting in the shape
    ashp.getFillFormat().setFillType(FillType.NoFill);

    ashp.setRotation(-45);

    ashp.getAutoShapeLock().setSelectLocked(true);
    ashp.getAutoShapeLock().setSizeLocked(true);
    ashp.getAutoShapeLock().setTextLocked(true);
    ashp.getAutoShapeLock().setPositionLocked(true);
    ashp.getAutoShapeLock().setGroupingLocked(true);
}
  
pres.save(path + "SavedWatermark.ppt", SaveFormat.Ppt);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Giới thiệu về Aspose.Slides cho Java API" %}}

 API Aspose.Slides có thể được sử dụng để đọc, viết, thao tác và chuyển đổi tài liệu Microsoft PowerPoint sang PDF, XPS, HTML, TIFF, ODP và nhiều định dạng khác. Người ta có thể tạo các tệp mới từ đầu và lưu chúng ở các định dạng được hỗ trợ có liên quan. Aspose.Slides là một API độc lập để tạo, phân tích cú pháp hoặc thao tác với các bản trình bày, trang trình bày và các phần tử và nó không phụ thuộc vào bất kỳ phần mềm nào như Microsoft hoặc OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Watermark PPT via Online App" sectionDescription="Add watermark to PPT documents by visiting our [Live Demos website](https://products.aspose.app/slides/watermark). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPT file, set your watermark and hit \"Add\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng đánh dấu nước được hỗ trợ khác" subTitle="Sử dụng Java, người ta có thể dễ dàng đánh dấu các định dạng khác nhau bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/watermark/pptx/" name="PPTX" description="Định dạng bản trình bày XML mở" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}