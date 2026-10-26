---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Bảo vệ tệp bản trình bày PPTX bằng Python
url: /vi/python-net/protect/pptx/
description: Mã hóa bản trình bày PPTX hoặc đặt bảo vệ chống ghi bằng Python.
keywords: bảo vệ chống ghi PPTX, mã hóa PPTX bằng Python, khóa bản trình bày PPTX, bảo vệ PPTX bằng Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bảo vệ bản trình bày PPTX bằng Python" h2="Xây dựng ứng dụng Python mã hóa bản trình bày hoặc đặt bảo vệ chống ghi bằng Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Bảo vệ bản trình bày PPTX bằng Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/vi/python-net/) cung cấp hai cơ chế bảo vệ riêng biệt. Gọi `ProtectionManager.encrypt` để mã hóa bản trình bày PPTX và yêu cầu mật khẩu khi mở. Ngoài ra, gọi `ProtectionManager.set_write_protection` để ngăn chỉnh sửa mà không cần mã hóa tệp. Người dùng vẫn có thể mở bản trình bày được bảo vệ chống ghi và lưu thay đổi vào một tệp khác.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã hóa bản trình bày PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Đặt bảo vệ chống ghi cho bản trình bày PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách bảo vệ PPTX bằng Python" intro="Làm theo các bước sau để bảo vệ tệp PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp PPTX bằng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dùng `ProtectionManager.encrypt` để yêu cầu mật khẩu khi mở, hoặc dùng `ProtectionManager.set_write_protection` để ngăn thay đổi.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu bản trình bày đã bảo vệ dưới dạng PPTX bằng `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Được xây dựng bằng Aspose.Slides" title="Bảo vệ tệp PPTX bằng mật khẩu trực tuyến" description="Ứng dụng Aspose.Slides Lock miễn phí được xây dựng bằng [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/vi/python-net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPTX của riêng bạn." button="Mở Aspose.Slides Lock" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides bảo vệ bản trình bày trước khi bạn viết mã.
- Đặt mật khẩu để mở hoặc chỉnh sửa tệp PPTX của bạn.
- Tải xuống tệp đã bảo vệ.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng bảo vệ được hỗ trợ khác" subTitle="Dùng Python để bảo vệ các định dạng bản trình bày được hỗ trợ khác." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
