---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Mở khóa bản trình bày PPT bằng C++
url: /vi/cpp/unlock/ppt/
description: Mở khóa bản trình bày PPT trong C++. Dùng Aspose.Slides for C++ để gỡ mã hóa và bảo vệ chống ghi khỏi tệp bản trình bày.
keywords: Gỡ bảo vệ chống ghi PPT, giải mã PPT, mở khóa bản trình bày PPT, bỏ bảo vệ PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Mở khóa PPT bằng C++" h2="Dùng Aspose.Slides for C++ để gỡ mã hóa và bảo vệ chống ghi khỏi tệp bản trình bày mà không cần Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Gỡ bảo vệ khỏi bản trình bày PPT bằng C++" variant="code" %}}

Aspose.Slides for C++ cho phép bạn gỡ mã hóa hoặc bảo vệ chống ghi khỏi bản trình bày PPT. Dùng `LoadOptions` để mở tệp đã mã hóa, sau đó dùng đối tượng `ProtectionManager` của lớp `Presentation` để gọi `RemoveEncryption` hoặc `RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Gỡ bảo vệ bằng mật khẩu khỏi PPT bằng C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.ppt", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Gỡ bảo vệ chống ghi khỏi bản trình bày PPT bằng C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.ppt");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách gỡ mật khẩu khỏi PPT bằng C++" intro="Làm theo các bước sau để gỡ bảo vệ khỏi bản trình bày PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPT bằng lớp `Presentation`, kèm `LoadOptions` nếu cần mật khẩu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dùng đối tượng `ProtectionManager` để gỡ bảo vệ.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi `RemoveEncryption` cho tệp đã mã hóa hoặc `RemoveWriteProtection` cho tệp được bảo vệ chống ghi.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu tệp đã mở khóa bằng `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Được xây dựng bằng Aspose.Slides" title="Mở khóa tệp PPT trực tuyến" description="Ứng dụng Aspose.Slides Unlock miễn phí được xây dựng bằng [Aspose.Slides for C++](https://products.aspose.com/slides/vi/cpp/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPT của riêng bạn." button="Mở Aspose.Slides Unlock" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides gỡ bảo vệ trước khi bạn viết mã.
- Gỡ mật khẩu hoặc bảo vệ chống ghi khỏi tệp PPT của bạn.
- Tải xuống tệp đã mở khóa.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng mở khóa được hỗ trợ khác" subTitle="Với C++, bạn cũng có thể gỡ bảo vệ khỏi các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
