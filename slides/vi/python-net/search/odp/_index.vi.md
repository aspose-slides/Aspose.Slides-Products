---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tìm kiếm văn bản trong các bản trình bày ODP bằng Python
url: /vi/python-net/search/odp/
description: Tìm kiếm văn bản trong bản trình bày ODP bằng Python và Aspose.Slides.
keywords: tìm kiếm văn bản trong ODP, tìm từ trong ODP, tìm kiếm bản trình bày ODP bằng Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tìm kiếm văn bản trong các bản trình bày ODP bằng Python" h2="Xây dựng ứng dụng Python tìm văn bản trong bản trình bày OpenDocument bằng Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tìm kiếm văn bản trong bản trình bày ODP bằng Python" variant="code" %}}

Với [Aspose.Slides for Python via .NET](/slides/vi/python-net/), bạn có thể dùng [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) để tìm trên mỗi trang chiếu các khung văn bản chứa một chuỗi nhất định.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tìm kiếm văn bản trong bản trình bày ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách tìm kiếm văn bản trong ODP bằng Python" intro="Làm theo các bước sau để tìm kiếm văn bản trong bản trình bày ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp ODP bằng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Duyệt qua các trang chiếu và gọi [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) cho từng trang.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Đọc thuộc tính `text` của từng khung văn bản khớp.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Được xây dựng bằng Aspose.Slides" title="Tìm kiếm văn bản trong tệp ODP trực tuyến" description="Ứng dụng Aspose.Slides Search miễn phí được xây dựng bằng [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/vi/python-net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp ODP của riêng bạn." button="Mở Aspose.Slides Search" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides tìm văn bản trước khi bạn viết mã.
- Tìm văn bản thuần hoặc biểu thức chính quy trong tệp ODP của bạn.
- Tải xuống kết quả dưới dạng tệp văn bản.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác được hỗ trợ để tìm kiếm" subTitle="Dùng Python để tìm kiếm văn bản trong các định dạng bản trình bày được hỗ trợ khác." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
