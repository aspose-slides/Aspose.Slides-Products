---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Bảo vệ bản trình bày PPT bằng C++
url: /vi/cpp/protect/ppt/
description: Bảo vệ bản trình bày PPT trong C++. Dùng Aspose.Slides for C++ để mã hóa tệp và đặt bảo vệ chống ghi.
keywords: Bảo vệ chống ghi PPT, mã hóa PPT, khóa bản trình bày PPT, bảo vệ PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Khóa hoặc bảo vệ PPT bằng mật khẩu với C++" h2="Dùng Aspose.Slides for C++ để mã hóa bản trình bày và đặt bảo vệ chống ghi mà không cần Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Bảo vệ bản trình bày PPT bằng C++" variant="code" %}}

Aspose.Slides for C++ cho phép bạn ngăn bản trình bày PPT bị mở hoặc chỉnh sửa. Dùng đối tượng `ProtectionManager` của lớp `Presentation` để mã hóa tệp bằng `Encrypt` hoặc hạn chế chỉnh sửa bằng `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã hóa bản trình bày PPT bằng C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Đặt bảo vệ chống ghi cho bản trình bày PPT bằng C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách bảo vệ PPT bằng mật khẩu với C++" intro="Làm theo các bước sau để bảo vệ bản trình bày PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPT bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Bảo vệ bản trình bày bằng đối tượng `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dùng `Encrypt` để bảo vệ bằng mật khẩu hoặc `SetWriteProtection` để bảo vệ chống ghi.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu tệp đã bảo vệ bằng `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Được xây dựng bằng Aspose.Slides" title="Bảo vệ tệp PPT bằng mật khẩu trực tuyến" description="Ứng dụng Aspose.Slides Lock miễn phí được xây dựng bằng [Aspose.Slides for C++](https://products.aspose.com/slides/vi/cpp/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPT của riêng bạn." button="Mở Aspose.Slides Lock" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides bảo vệ bản trình bày trước khi bạn viết mã.
- Đặt mật khẩu để mở hoặc chỉnh sửa tệp PPT của bạn.
- Tải xuống tệp đã bảo vệ.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng bảo vệ được hỗ trợ khác" subTitle="Với C++, bạn cũng có thể bảo vệ các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
