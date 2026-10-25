---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Trích xuất văn bản từ tệp ODP bằng Python
url: /vi/python-net/parser/odp/
description: Trích xuất văn bản và chi tiết định dạng văn bản từ bản trình bày ODP bằng Python.
keywords: phân tích ODP bằng Python, trình phân tích ODP Python, trích xuất dữ liệu từ ODP trong Python, trích xuất văn bản từ ODP bằng Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Trích xuất văn bản từ bản trình bày ODP bằng Python" h2="Xây dựng ứng dụng Python trích xuất văn bản và chi tiết định dạng từ bản trình bày OpenDocument bằng Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Trích xuất văn bản từ một bản trình bày ODP bằng Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/vi/python-net/) cung cấp phương thức tĩnh [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) trên `SlideUtil`. Phương thức này trả về các đối tượng `TextFrame` của toàn bộ bản trình bày và có thể bao gồm văn bản từ trang chiếu cái. Ví dụ sau trích xuất văn bản và chi tiết phông chữ liên quan từ bản trình bày ODP.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Trích xuất văn bản từ bản trình bày ODP – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.odp") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách trích xuất văn bản từ ODP bằng Python" intro="Làm theo các bước sau để trích xuất văn bản từ tệp ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp ODP bằng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi `SlideUtil.get_all_text_frames` và chỉ định có bao gồm trang chiếu cái hay không.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Duyệt qua các đối tượng `TextFrame` được trả về.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Duyệt qua tập hợp `paragraphs` của mỗi khung văn bản.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Duyệt qua tập hợp `portions` của mỗi đoạn văn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Đọc `text` và các thuộc tính định dạng của phần văn bản hiện tại.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Được xây dựng bằng Aspose.Slides" title="Trích xuất văn bản và hình ảnh trực tuyến" description="Ứng dụng Aspose.Slides Parser miễn phí được xây dựng bằng [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/vi/python-net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp ODP của riêng bạn." button="Mở Aspose.Slides Parser" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem Aspose.Slides đọc tệp của bạn như thế nào trước khi viết mã.
- Tải lên tệp ODP và nhận văn bản cùng hình ảnh của tệp.
- Tải xuống tất cả dưới dạng một tệp ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng phân tích khác được hỗ trợ" subTitle="Với Python, bạn cũng có thể trích xuất văn bản từ các định dạng bản trình bày khác được hỗ trợ." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
