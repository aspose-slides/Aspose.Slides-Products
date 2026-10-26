---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Mở khóa tệp bản trình bày ODP bằng .NET
url: /vi/net/unlock/odp/
description: Mã nguồn C# để gỡ bảo vệ bằng mật khẩu khỏi bản trình bày ODP.
keywords: Gỡ bảo vệ chống ghi ODP, giải mã ODP, mở khóa bản trình bày ODP, bỏ bảo vệ ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Mở khóa tệp ODP bằng C#" h2="Xây dựng ứng dụng .NET gỡ mã hóa và bảo vệ chống ghi khỏi bản trình bày bằng API phía máy chủ." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Gỡ bảo vệ khỏi bản trình bày ODP bằng C#" variant="code" %}}

Với [Aspose.Slides for .NET](/slides/vi/net/), bạn có thể gỡ mã hóa hoặc bảo vệ chống ghi khỏi bản trình bày ODP. Để gỡ mã hóa, hãy tải bản trình bày bằng mật khẩu đúng và gọi `ProtectionManager.RemoveEncryption`. Để gỡ bảo vệ chống ghi, hãy gọi `ProtectionManager.RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Gỡ mã hóa khỏi bản trình bày ODP bằng C#" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.odp", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Gỡ bảo vệ chống ghi khỏi bản trình bày ODP bằng C#" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.odp");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách gỡ bảo vệ khỏi bản trình bày ODP bằng C#" intro="Làm theo các bước sau để gỡ bảo vệ khỏi bản trình bày ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp ODP bằng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Với tệp đã mã hóa, hãy cung cấp mật khẩu qua `LoadOptions.Password` trước khi tải.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi `ProtectionManager.RemoveEncryption` hoặc `ProtectionManager.RemoveWriteProtection`, tùy theo loại bảo vệ đã áp dụng.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu bản trình bày đã mở khóa bằng `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Được xây dựng bằng Aspose.Slides" title="Mở khóa tệp ODP trực tuyến" description="Ứng dụng Aspose.Slides Unlock miễn phí được xây dựng bằng [Aspose.Slides for .NET](https://products.aspose.com/slides/vi/net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp ODP của riêng bạn." button="Mở Aspose.Slides Unlock" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides gỡ bảo vệ trước khi bạn viết mã.
- Gỡ mật khẩu hoặc bảo vệ chống ghi khỏi tệp ODP của bạn.
- Tải xuống tệp đã mở khóa.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng mở khóa được hỗ trợ khác" subTitle="Với C#, bạn cũng có thể gỡ bảo vệ khỏi các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
