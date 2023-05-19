---
title: Tìm kiếm Văn bản trong Tệp Bản trình bày ODP bằng Java
url: /vi/java/search/odp/
keywords: tìm kiếm từ trong ODP, tìm kiếm và thay thế văn bản trong ODP, tìm kiếm văn bản ODP Bản trình bày
description: Mã nguồn Java để tìm kiếm văn bản trong Bản trình bày ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Tìm kiếm văn bản ODP bằng Java" h2="Xây dựng ứng dụng Java của riêng bạn để tìm kiếm và thay thế văn bản trong tệp bản trình bày bằng API phía máy chủ. Tìm hiểu cách tìm tất cả các lối vào của một từ hoặc cụm từ nhất định trong tài liệu thuyết trình. Tìm kiếm văn bản bằng cách khớp dữ liệu chính xác và khớp cụm từ thông dụng." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Tìm kiếm và Thay thế Văn bản Bản trình bày ODP qua Java" %}}
Có thể thực hiện tìm kiếm tài liệu cơ bản và thay thế văn bản trong nội dung, nhận xét, ghi chú trang trình bày hoặc siêu dữ liệu bằng API Aspose.Slides for Java chỉ với vài dòng mã. Sử dụng phép so khớp biểu thức chính quy, kiểu khớp để tìm kiếm văn bản trong bản trình bày. Tìm kiếm văn bản trong tiêu đề, nội dung, chân trang hoặc tiêu đề.
{{% blocks/products/pf/agp/code-block title="Tìm kiếm văn bản ODP Bản trình bày bằng Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách tìm kiếm văn bản ở ODP qua Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để tìm kiếm tệp văn bản ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải ODP với phiên bản Trình bày.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sử dụng phương thức [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) để tìm và thay thế văn bản.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả ở định dạng ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Trực tuyến ODP Tìm kiếm Trình diễn trực tiếp" sectionDescription="Tìm kiếm và thay thế văn bản trong nội dung, nhận xét hoặc siêu dữ liệu trong tài liệu ODP ngay bây giờ." >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng tìm kiếm được hỗ trợ khác" subTitle="Sử dụng Java, Bạn cũng có thể tìm kiếm văn bản ở các định dạng sau:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}