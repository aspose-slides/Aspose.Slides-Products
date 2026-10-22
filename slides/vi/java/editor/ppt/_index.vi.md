---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chỉnh sửa PPT trong Java
url: /vi/java/editor/ppt/
keywords: Chỉnh sửa PPT, Chỉnh sửa PowerPoint, PPT, PowerPoint, API Java, Thư viện Java
description: Chỉnh sửa PPT trong Java. Sử dụng API thư viện Java để chỉnh sửa bản trình bày PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chỉnh sửa PPT trong Java" h2="Thư viện Java tốc độ cao và đa nền tảng để chỉnh sửa PPT bằng mã Java" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chỉnh sửa PPT trong Java" variant="code" %}}

Sử dụng [**Aspose.Slides for Java**](https://products.aspose.com/slides/vi/java/), bạn có thể thêm một dòng văn bản mới vào tài liệu PPT chỉ bằng một vài dòng mã.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã Java để chỉnh sửa PPT" >}}
```java

Presentation pres = new Presentation("pres.ppt");
try {
    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chỉnh sửa PPT bằng Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/vi/java/) là một thư viện Java mạnh mẽ được sử dụng để thao tác và chỉnh sửa bản trình bày. Bạn có thể chỉnh sửa bản trình bày PPT bằng cách thêm một dòng văn bản mới vào đó.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chỉnh sửa PPT trong Java" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt **Aspose.Slides cho Java**. Xem [**Cài đặt**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm thư viện làm tài liệu tham khảo trong dự án của bạn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tạo một thể hiện của lớp Trình bày.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải bản trình bày PPT mà bạn muốn chỉnh sửa.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm một dòng văn bản mới.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu tệp PowerPoint đã thay đổi.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Chỉnh sửa các tệp khác" subTitle="Bạn cũng có thể chỉnh sửa tệp ở các định dạng khác" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/java/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
