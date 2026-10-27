---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1790
title: Xóa chú thích ODP bằng Java
url: /vi/java/annotation/odp/ 
description: Xóa nhận xét và tác giả nhận xét khỏi bản trình bày ODP trong Java với Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Xóa nhận xét và tác giả nhận xét khỏi ODP bằng Java" h2="Dùng Aspose.Slides for Java để xóa nhận xét và tác giả nhận xét khỏi tệp bản trình bày." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Xóa nhận xét khỏi ODP qua Java" variant="code" %}}

Aspose.Slides for Java cho phép bạn xóa nhận xét và tác giả nhận xét khỏi bản trình bày ODP. Tải tệp bằng lớp `Presentation`, duyệt qua các đối tượng `ICommentAuthor` từ `getCommentAuthors`, xóa nhận xét của họ và lưu bản trình bày đã cập nhật.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Xóa chú thích khỏi ODP – Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách xóa nhận xét khỏi ODP qua Java" intro="Làm theo các bước sau để xóa nhận xét và tác giả nhận xét khỏi bản trình bày ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt Aspose.Slides for Java. Xem [Cài đặt](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp ODP bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Duyệt qua các đối tượng `ICommentAuthor` từ `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Xóa nhận xét của từng tác giả bằng `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Xóa sạch tập hợp tác giả nhận xét và lưu tệp ODP đã cập nhật.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Được xây dựng bằng Aspose.Slides" title="Xóa nhận xét ODP trực tuyến" description="Ứng dụng Aspose.Slides Annotation miễn phí được xây dựng bằng [Aspose.Slides for Java](https://products.aspose.com/slides/vi/java/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp ODP của riêng bạn." button="Mở Aspose.Slides Annotation" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides xóa nhận xét trước khi bạn viết mã.
- Xóa tất cả nhận xét khỏi tệp ODP của bạn.
- Tải xuống tệp đã được làm sạch.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác được hỗ trợ cho chú thích" subTitle="Với Java, bạn cũng có thể xóa chú thích khỏi các định dạng khác." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
