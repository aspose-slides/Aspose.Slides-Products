---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Thêm hình mờ vào tệp bản trình bày PPTX bằng Java
url: /vi/java/watermark/pptx/
description: Thêm hình mờ văn bản và hình ảnh vào bản trình bày PPTX trong Java bằng Aspose.Slides for Java.
keywords: thêm hình mờ vào PPTX, thêm hình mờ văn bản vào PPTX, thêm hình mờ hình ảnh vào PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Thêm hình mờ vào bản trình bày PPTX bằng Java" h2="Xây dựng ứng dụng Java chèn hình mờ văn bản hoặc hình ảnh vào tệp bản trình bày bằng API phía máy chủ." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Thêm hình mờ vào bản trình bày PPTX qua Java" variant="code" %}}

Với [Aspose.Slides for Java](/slides/vi/java/), bạn có thể thêm hình mờ văn bản và hình ảnh vào bản trình bày PPTX. Thêm hình dạng hình mờ vào trang chiếu cái để hình mờ xuất hiện trên các trang chiếu dùng trang chiếu cái đó.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Thêm hình mờ văn bản vào PPTX bằng Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Thêm hình mờ hình ảnh vào bản trình bày PPTX bằng Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách thêm hình mờ vào PPTX bằng Java" intro="Làm theo các bước sau để thêm hình mờ văn bản hoặc hình ảnh vào tệp PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp `PPTX` bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chọn một trang chiếu cái bằng phương thức `getMasters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức `addAutoShape` để thêm hình dạng hình mờ.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức `addTextFrame` để thêm văn bản hình mờ hoặc dùng `addImage` cho hình mờ hình ảnh.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu bản trình bày có hình mờ ở định dạng PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Được xây dựng bằng Aspose.Slides" title="Thêm hình mờ vào tệp PPTX trực tuyến" description="Ứng dụng Aspose.Slides Watermark miễn phí được xây dựng bằng [Aspose.Slides for Java](https://products.aspose.com/slides/vi/java/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPTX của riêng bạn." button="Mở Aspose.Slides Watermark" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem Aspose.Slides thêm hình mờ như thế nào trước khi viết mã.
- Thêm hình mờ văn bản hoặc hình ảnh vào tệp PPTX của bạn.
- Tải xuống tệp có hình mờ.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác hỗ trợ hình mờ" subTitle="Với Java, bạn cũng có thể thêm hình mờ vào các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
