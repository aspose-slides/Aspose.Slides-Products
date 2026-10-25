---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Xem hoặc chỉnh sửa siêu dữ liệu tệp PPSM bằng Java
url: /vi/java/metadata/ppsm/
description: Xem và chỉnh sửa siêu dữ liệu PPSM trong Java. Dùng Aspose.Slides for Java để cập nhật thuộc tính tích hợp và tùy chỉnh của bản trình bày.
keywords: chỉnh sửa siêu dữ liệu PPSM, xem siêu dữ liệu PPSM, chỉnh sửa thuộc tính PPSM, xem thuộc tính PPSM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chỉnh sửa thuộc tính PPSM bằng Java" h2="Xây dựng ứng dụng Java sửa đổi thuộc tính tích hợp và tùy chỉnh trong tệp bản trình bày bằng API phía máy chủ." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sửa đổi thuộc tính PPSM bằng Java" variant="code" %}}

Với [Aspose.Slides for Java](/slides/vi/java/), nhà phát triển có thể truy cập và sửa đổi thuộc tính tích hợp và tùy chỉnh của bản trình bày. Dùng phương thức `getDocumentProperties` của đối tượng `Presentation` để truy cập đối tượng `IDocumentProperties` của tệp bản trình bày.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Sửa đổi thuộc tính tích hợp của PPSM – Java" >}}
```java
Presentation presentation = new Presentation("Presentation.ppsm");
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.setAuthor("Aspose.Slides for Java");
    documentProperties.setTitle("Modifying Presentation Properties");
    documentProperties.setSubject("Aspose Subject");
    documentProperties.setComments("Aspose Description");
    documentProperties.setManager("Aspose Manager");

    presentation.save("DocProps.ppsm", SaveFormat.Ppsm);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Thêm thuộc tính tùy chỉnh vào PPSM – Java" >}}
```java
Presentation presentation = new Presentation();
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.set_Item("New Custom", 12);
    documentProperties.set_Item("My Name", "Aspose Metadata Editor");
    documentProperties.set_Item("Custom", 124);

    String customPropertyName = documentProperties.getCustomPropertyName(2);
    documentProperties.removeCustomProperty(customPropertyName);

    presentation.save("CustomDemo.ppsm", SaveFormat.Ppsm);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách xem hoặc chỉnh sửa siêu dữ liệu PPSM trong Java" intro="Làm theo các bước sau để xem hoặc chỉnh sửa siêu dữ liệu PPSM." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp `PPSM` bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức `getDocumentProperties` để lấy đối tượng `IDocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Đọc hoặc cập nhật các thuộc tính tích hợp như `Author`, `Title`, `Subject` và `Comments`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Truy cập và sửa đổi thuộc tính tùy chỉnh bằng `set_Item`, `getCustomPropertyName` và `removeCustomProperty`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Được xây dựng bằng Aspose.Slides" title="Xem và chỉnh sửa siêu dữ liệu PPSM trực tuyến" description="Ứng dụng Aspose.Slides Metadata miễn phí được xây dựng bằng [Aspose.Slides for Java](https://products.aspose.com/slides/vi/java/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPSM của riêng bạn." button="Mở Aspose.Slides Metadata" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem Aspose.Slides đọc và ghi thuộc tính như thế nào trước khi viết mã.
- Xem và chỉnh sửa thuộc tính tích hợp và tùy chỉnh của tệp PPSM.
- Lưu và tải xuống tệp đã cập nhật.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng siêu dữ liệu khác được hỗ trợ" subTitle="Với Java, bạn cũng có thể quản lý siêu dữ liệu của các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
