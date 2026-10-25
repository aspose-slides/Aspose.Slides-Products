---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 5200
title: Trích xuất văn bản từ tài liệu ODP bằng Java
url: /vi/java/parser/odp/ 
description: Trích xuất văn bản từ tệp ODP trong Java bằng Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Phân tích tệp ODP trong Java" h2="Trích xuất văn bản và nội dung bản trình bày từ tài liệu ODP bằng API phía máy chủ của Aspose.Slides for Java."
  apiHomeLink="/slides/java/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Phân tích tệp ODP bằng Java" %}}

Dùng [Aspose.Slides for Java](/slides/vi/java/) để phân tích bản trình bày ODP và trích xuất văn bản từ trang chiếu. Thêm thư viện vào dự án Maven bằng cấu hình kho lưu trữ và phụ thuộc bên dưới trong tệp `pom.xml`.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Kho lưu trữ" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Phụ thuộc" >}}
```xml
<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Phân tích tệp ODP – Java" >}}
```java
Presentation presentation = new Presentation("demo.odp");
try {
    ISlide slide = presentation.getSlides().get_Item(0);
    ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

    for (ITextFrame textFrame : slideTextFrames) {
        for (IParagraph paragraph : textFrame.getParagraphs()) {
            for (IPortion portion : paragraph.getPortions()) {
                System.out.print(portion.getText());
                System.out.print(portion.getPortionFormat().getFontHeight());
                System.out.print(portion.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách phân tích tệp ODP trong Java" intro="Trích xuất văn bản từ bản trình bày ODP bằng Aspose.Slides for Java chỉ với vài dòng mã." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp `ODP` bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức `SlideUtil.getAllTextBoxes` để lấy các khung văn bản từ trang chiếu đầu tiên.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Duyệt qua từng đối tượng `ITextFrame`, `IParagraph` và `IPortion`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Đọc văn bản, cỡ phông chữ và tên phông chữ từ mỗi đối tượng `IPortion`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Yêu cầu hệ thống" intro="Aspose.Slides for Java hỗ trợ các nền tảng và hệ điều hành chính. Hãy đảm bảo môi trường của bạn đáp ứng các điều kiện tiên quyết sau." %}}

- Microsoft Windows hoặc hệ điều hành tương thích có Java Runtime Environment cho ứng dụng JSP/JSF và ứng dụng máy tính.
- Phiên bản mới nhất của Aspose.Slides for Java từ [Maven](https://releases.aspose.com/java/repo/).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Được xây dựng bằng Aspose.Slides" title="Trích xuất văn bản và hình ảnh trực tuyến" description="Ứng dụng Aspose.Slides Parser miễn phí được xây dựng bằng [Aspose.Slides for Java](https://products.aspose.com/slides/vi/java/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp ODP của riêng bạn." button="Mở Aspose.Slides Parser" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem Aspose.Slides đọc tệp của bạn như thế nào trước khi viết mã.
- Tải lên tệp ODP và nhận văn bản cùng hình ảnh của tệp.
- Tải xuống tất cả dưới dạng một tệp ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

Files with the ODP extension use the OpenDocument Presentation format. An ODP file stores slides that can contain text, images, formatting, animations, and other presentation content.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng phân tích khác được hỗ trợ" subTitle="Với Java, bạn cũng có thể phân tích các định dạng bản trình bày khác." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/parser/ppt/" name="PPT" description="Bản trình bày PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/parser/pptx/" name="PPTX" description="Bản trình bày PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
