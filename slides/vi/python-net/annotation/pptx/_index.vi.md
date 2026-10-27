---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Xóa nhận xét khỏi PPTX bằng Python
url: /vi/python-net/annotation/pptx/ 
description: Xóa nhận xét và tác giả nhận xét khỏi bản trình bày PPTX trong Python với Aspose.Slides for Python via .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Xóa nhận xét và tác giả nhận xét khỏi PPTX bằng Python" h2="Dùng Aspose.Slides for Python via .NET để xóa nhận xét trong bản trình bày cùng các tác giả liên quan." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Xóa nhận xét khỏi PPTX qua Python" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/vi/python-net/) cung cấp quyền truy cập vào nhận xét và tác giả nhận xét được lưu trong bản trình bày PPTX. Tải tệp bằng `Presentation`, xóa sạch tập hợp `comments` của từng tác giả, xóa sạch `comment_authors` và lưu kết quả ở định dạng PPTX.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Xóa nhận xét khỏi PPTX bằng Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách xóa nhận xét khỏi PPTX qua Python" intro="Làm theo các bước sau để xóa tất cả nhận xét và tác giả nhận xét khỏi bản trình bày PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt [Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp PPTX bằng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Duyệt qua `comment_authors` và xóa sạch tập hợp `comments` của từng tác giả.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Xóa sạch tập hợp `comment_authors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi `save` với `SaveFormat.PPTX` để ghi bản trình bày PPTX đã cập nhật.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Được xây dựng bằng Aspose.Slides" title="Xóa nhận xét PPTX trực tuyến" description="Ứng dụng Aspose.Slides Annotation miễn phí được xây dựng bằng [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/vi/python-net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPTX của riêng bạn." button="Mở Aspose.Slides Annotation" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides xóa nhận xét trước khi bạn viết mã.
- Xóa tất cả nhận xét khỏi tệp PPTX của bạn.
- Tải xuống tệp đã được làm sạch.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác được hỗ trợ cho chú thích" subTitle="Với Python, bạn cũng có thể xóa chú thích khỏi các định dạng khác." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
