---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Mở khóa tệp bản trình bày ODP bằng Java
url: /vi/java/unlock/odp/
description: Gỡ mật khẩu và bảo vệ chống ghi khỏi bản trình bày ODP trong Java bằng Aspose.Slides for Java.
keywords: Gỡ bảo vệ chống ghi ODP, giải mã ODP, mở khóa bản trình bày ODP, bỏ bảo vệ ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Mở khóa ODP bằng Java" h2="Xây dựng ứng dụng Java gỡ mật khẩu và bảo vệ chống ghi khỏi tệp bản trình bày bằng API phía máy chủ." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Gỡ bảo vệ khỏi bản trình bày ODP bằng Java" variant="code" %}}

Với [Aspose.Slides for Java](/slides/vi/java/), bạn có thể gỡ mã hóa hoặc bảo vệ chống ghi khỏi bản trình bày ODP. Dùng `LoadOptions.setPassword` để mở bản trình bày đã mã hóa và các phương thức `removeEncryption` và `removeWriteProtection` của `ProtectionManager` để gỡ thiết lập bảo vệ.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Gỡ bảo vệ bằng mật khẩu khỏi ODP bằng Java" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.odp", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Gỡ bảo vệ chống ghi khỏi bản trình bày ODP bằng Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách gỡ mật khẩu khỏi ODP bằng Java" intro="Làm theo các bước sau để gỡ bảo vệ khỏi bản trình bày ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp ODP bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dùng `LoadOptions.setPassword` khi bản trình bày đã được mã hóa.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi `removeEncryption` hoặc `removeWriteProtection` của đối tượng `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu bản trình bày đã mở khóa bằng `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Được xây dựng bằng Aspose.Slides" title="Mở khóa tệp ODP trực tuyến" description="Ứng dụng Aspose.Slides Unlock miễn phí được xây dựng bằng [Aspose.Slides for Java](https://products.aspose.com/slides/vi/java/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp ODP của riêng bạn." button="Mở Aspose.Slides Unlock" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides gỡ bảo vệ trước khi bạn viết mã.
- Gỡ mật khẩu hoặc bảo vệ chống ghi khỏi tệp ODP của bạn.
- Tải xuống tệp đã mở khóa.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng mở khóa được hỗ trợ khác" subTitle="Với Java, bạn cũng có thể gỡ bảo vệ khỏi các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
