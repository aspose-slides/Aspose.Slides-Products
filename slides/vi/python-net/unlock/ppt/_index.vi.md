---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Mở khóa bản trình bày PPT bằng Python
url: /vi/python-net/unlock/ppt/
description: Gỡ mã hóa và bảo vệ chống ghi khỏi bản trình bày PPT bằng Python.
keywords: mở khóa PPT, gỡ mật khẩu khỏi PPT, gỡ mã hóa PPT, gỡ bảo vệ chống ghi khỏi PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Mở khóa bản trình bày PPT bằng Python" h2="Xây dựng ứng dụng Python gỡ mật khẩu mở và thiết lập bảo vệ chống ghi khỏi bản trình bày PPT bằng Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Gỡ mã hóa và bảo vệ chống ghi khỏi PPT bằng Python" variant="code" %}}

Với [Aspose.Slides for Python via .NET](/slides/vi/python-net/), bạn có thể gỡ mã hóa yêu cầu mật khẩu khi mở bản trình bày PPT, hoặc tắt thiết lập bảo vệ chống ghi của nó. Để mở tệp đã mã hóa, hãy cung cấp mật khẩu hiện tại qua `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Gỡ mã hóa khỏi bản trình bày PPT – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.ppt", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Gỡ bảo vệ chống ghi khỏi bản trình bày PPT – Python" >}}
```py
with slides.Presentation("write-protected-presentation.ppt") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách gỡ bảo vệ khỏi PPT bằng Python" intro="Làm theo các bước sau để gỡ bảo vệ khỏi bản trình bày PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Với tệp PPT đã mã hóa, hãy đặt mật khẩu hiện tại trong `LoadOptions`, rồi mở tệp bằng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi `ProtectionManager.remove_encryption` để gỡ mật khẩu mở, hoặc gọi `ProtectionManager.remove_write_protection` để tắt bảo vệ chống ghi.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu bản trình bày thu được bằng `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Được xây dựng bằng Aspose.Slides" title="Mở khóa tệp PPT trực tuyến" description="Ứng dụng Aspose.Slides Unlock miễn phí được xây dựng bằng [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/vi/python-net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPT của riêng bạn." button="Mở Aspose.Slides Unlock" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides gỡ bảo vệ trước khi bạn viết mã.
- Gỡ mật khẩu hoặc bảo vệ chống ghi khỏi tệp PPT của bạn.
- Tải xuống tệp đã mở khóa.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng mở khóa được hỗ trợ khác" subTitle="Dùng Python để gỡ bảo vệ khỏi các định dạng bản trình bày được hỗ trợ khác." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
