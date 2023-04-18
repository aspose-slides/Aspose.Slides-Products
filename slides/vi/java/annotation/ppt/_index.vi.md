---
title: Xóa chú thích PPT bằng Java
weight: 3630
url: /vi/java/annotation/ppt/ 
description: Mã mẫu Java để xóa chú thích định dạng PPT trên Môi trường thời gian chạy Java cho Ứng dụng JSP/JSF và Ứng dụng máy tính để bàn.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Xóa Nhận xét và Tác giả Nhận xét khỏi PPT trong Java" h2="Xây dựng ứng dụng Java của riêng bạn để thao tác nhận xét và tác giả trong tệp tài liệu bằng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="Xóa Nhận xét khỏi PPT qua Java" %}}
Để xóa chú thích khỏi tệp PPT, chúng tôi sẽ sử dụng API [Aspose.Slides for Java](https://products.aspose.com/slides/vi/java/) API có nhiều tính năng, mạnh mẽ và dễ sử dụng API thao tác tài liệu cho nền tảng Java.
{{% blocks/products/pf/agp/code-block title="Xóa chú thích khỏi PPT - Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.ppt");
try {
    // Deletes all comments from the presentation
    for (ICommentAuthor author : presentation.getCommentAuthors())
    {
        author.getComments().clear();
    }

    // Deletes all authors
    presentation.getCommentAuthors().clear();

    presentation.save("example_out.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Cách xóa Nhận xét khỏi PPT qua Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt **Aspose.Slides cho Java**. Xem [**Cài đặt**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải PPT với một thể hiện của lớp Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lặp lại tất cả các Tác giả của PPT đã tải
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Xóa tất cả Nhận xét của một tác giả
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Xóa tất cả Tác giả ở cuối
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng chú thích được hỗ trợ khác" subTitle="Sử dụng Java, người ta có thể dễ dàng chú thích các định dạng khác bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}