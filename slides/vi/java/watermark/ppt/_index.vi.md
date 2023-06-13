---
title: Thêm Hình mờ vào Tệp Bản trình bày PPT bằng Java
url: /vi/java/watermark/ppt/
keywords: Thêm Hình mờ PPT, Thêm Hình mờ Văn bản PPT, Thêm Hình mờ Hình ảnh PPT
description: Mã nguồn Java để thêm Hình mờ vào Bản trình bày PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Thêm Hình mờ vào Bản trình bày PPT bằng Java" h2="Xây dựng các ứng dụng Java của riêng bạn để chèn hình mờ văn bản hoặc hình ảnh vào bản trình bày PPT, PPTX hoặc ODP bằng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Thêm Hình mờ vào Bản trình bày PPT qua Java" %}}
Sử dụng Aspose.Slides for Java, bạn có thể thêm hình mờ vào bản trình bày PPT. Hình mờ là một phần thiết yếu của bất kỳ bài thuyết trình nào. Chúng được sử dụng để bảo vệ nội dung của bài thuyết trình không bị sao chép hoặc sử dụng trái phép. Hình mờ là một hình ảnh hoặc văn bản hiển thị hoặc không nhìn thấy được đặt ở trên cùng của bản trình bày. Nó có thể được sử dụng để xác định chủ sở hữu của bài thuyết trình và để ngăn chặn việc sử dụng trái phép. Hình nền mờ cũng có thể được sử dụng để thêm nét chuyên nghiệp cho bản trình bày và làm cho bản trình bày trông bóng bẩy hơn. 
{{% blocks/products/pf/agp/code-block title="Thêm Hình mờ văn bản vào PPT bằng Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IMasterSlide master = pres.getMasters().get_Item(0);
    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");

    pres.save("watermark.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Thêm hình mờ vào bản trình bày PPT bằng Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("watermark.png")));

    IMasterSlide master = pres.getMasters().get_Item(0);

    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 100, 100);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(image);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    pres.save("watermark2.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách thêm Hình mờ vào PPT qua Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để thêm hình mờ văn bản vào tệp PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải PPT với phiên bản Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chọn bản trình bày chính
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm loại hình bằng phương pháp AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm văn bản hình mờ bằng phương pháp AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả ở định dạng PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng được hỗ trợ khác" subTitle="Sử dụng Java, Bạn cũng có thể thêm Hình mờ vào các định dạng sau:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}