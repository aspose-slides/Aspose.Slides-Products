---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Bảo vệ tệp bản trình bày ODP bằng .NET
url: /vi/net/protect/odp/
description: Mã nguồn C# để bảo vệ bản trình bày ODP bằng mật khẩu.
keywords: Bảo vệ chống ghi ODP, mã hóa ODP, khóa bản trình bày ODP, bảo vệ ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Khóa hoặc bảo vệ tệp ODP bằng mật khẩu với C#" h2="Xây dựng ứng dụng .NET mã hóa bản trình bày và hạn chế chỉnh sửa bằng API phía máy chủ." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Bảo vệ bản trình bày ODP bằng C#" variant="code" %}}

Với [Aspose.Slides for .NET](/slides/vi/net/), bạn có thể mã hóa bản trình bày ODP hoặc hạn chế chỉnh sửa bằng mật khẩu. Để mở bản trình bày đã được mã hóa bằng `ProtectionManager.Encrypt` cần có mật khẩu. Dùng `ProtectionManager.SetWriteProtection` để vẫn cho phép mở bản trình bày nhưng hạn chế thay đổi.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã hóa bản trình bày ODP bằng C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Đặt bảo vệ chống ghi cho bản trình bày ODP bằng C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách bảo vệ bản trình bày ODP bằng mật khẩu với C#" intro="Làm theo các bước sau để bảo vệ bản trình bày ODP bằng mật khẩu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp ODP bằng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mã hóa bản trình bày bằng `ProtectionManager.Encrypt` hoặc hạn chế thay đổi bằng `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu tệp đã bảo vệ bằng `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Được xây dựng bằng Aspose.Slides" title="Bảo vệ tệp ODP bằng mật khẩu trực tuyến" description="Ứng dụng Aspose.Slides Lock miễn phí được xây dựng bằng [Aspose.Slides for .NET](https://products.aspose.com/slides/vi/net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp ODP của riêng bạn." button="Mở Aspose.Slides Lock" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides bảo vệ bản trình bày trước khi bạn viết mã.
- Đặt mật khẩu để mở hoặc chỉnh sửa tệp ODP của bạn.
- Tải xuống tệp đã bảo vệ.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng bảo vệ được hỗ trợ khác" subTitle="Với C#, bạn cũng có thể bảo vệ các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
