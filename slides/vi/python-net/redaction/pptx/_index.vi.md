---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Che văn bản trong các bản trình bày PPTX bằng Python
url: /vi/python-net/redaction/pptx/
description: Tìm và thay thế văn bản nhạy cảm trong bản trình bày PPTX bằng Python.
keywords: che thông tin PPTX, tìm và thay thế văn bản trong PPTX, cập nhật bản trình bày PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Che văn bản trong các bản trình bày PPTX bằng Python" h2="Xây dựng ứng dụng Python tìm và thay thế văn bản nhạy cảm trong bản trình bày bằng Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Che văn bản trong bản trình bày PPTX bằng Python" variant="code" %}}

Với [Aspose.Slides for Python via .NET](/slides/vi/python-net/), bạn có thể thay thế văn bản nhạy cảm trong toàn bộ bản trình bày PPTX. Dùng `Presentation.replace_text` với `TextSearchOptions` để kiểm soát việc tìm kiếm, sau đó lưu bản trình bày đã sửa đổi.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Che văn bản trong bản trình bày PPTX – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.pptx") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách che văn bản trong bản trình bày PPTX bằng Python" intro="Làm theo các bước sau để thay thế văn bản nhạy cảm trong bản trình bày PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp PPTX bằng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dùng [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) với `TextSearchOptions` để thay thế văn bản cần thiết.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu bản trình bày đã sửa đổi bằng `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Được xây dựng bằng Aspose.Slides" title="Che thông tin trong tệp PPTX trực tuyến" description="Ứng dụng Aspose.Slides Redaction miễn phí được xây dựng bằng [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/vi/python-net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPTX của riêng bạn." button="Mở Aspose.Slides Redaction" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides tìm và thay thế văn bản trước khi bạn viết mã.
- Tìm và thay thế văn bản trong tệp PPTX của bạn, kể cả bằng biểu thức chính quy.
- Tải xuống tệp đã che thông tin.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác được hỗ trợ để che thông tin" subTitle="Dùng Python để che văn bản trong các định dạng bản trình bày được hỗ trợ khác." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
