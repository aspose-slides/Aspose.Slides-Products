---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Thêm hình mờ vào bản trình bày PPTX bằng Python
url: /vi/python-net/watermark/pptx/
description: Thêm hình mờ văn bản và hình ảnh vào bản trình bày PPTX bằng Python và Aspose.Slides.
keywords: thêm hình mờ vào PPTX, thêm hình mờ văn bản vào PPTX, thêm hình mờ hình ảnh vào PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Thêm hình mờ vào bản trình bày PPTX bằng Python" h2="Xây dựng ứng dụng Python thêm hình mờ văn bản hoặc hình ảnh vào bản trình bày PPTX bằng Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Thêm hình mờ vào một bản trình bày PPTX bằng Python" variant="code" %}}

Với [Aspose.Slides for Python via .NET](/slides/vi/python-net/), bạn có thể thêm hình mờ văn bản hoặc hình ảnh vào bản trình bày PPTX mà không cần Microsoft PowerPoint. Hình mờ có thể cho biết quyền sở hữu, đánh dấu bản trình bày là bí mật hoặc bản nháp, hoặc tạo nhận diện thương hiệu nhất quán. Các ví dụ dưới đây đặt hình mờ trên trang chiếu cái đầu tiên để hình mờ xuất hiện trên các trang chiếu dùng trang chiếu cái đó.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Thêm hình mờ văn bản vào bản trình bày PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 100, 100, 400, 50)
    watermark_text_frame = watermark_shape.add_text_frame("CONFIDENTIAL")

    watermark_shape.fill_format.fill_type = slides.FillType.NO_FILL
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    watermark_portion = watermark_text_frame.paragraphs[0].portions[0]
    watermark_portion.portion_format.font_height = 32

    watermark_shape.auto_shape_lock.select_locked = True
    watermark_shape.auto_shape_lock.size_locked = True
    watermark_shape.auto_shape_lock.text_locked = True
    watermark_shape.auto_shape_lock.position_locked = True
    watermark_shape.auto_shape_lock.grouping_locked = True

    presentation.save("watermarked.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Thêm hình mờ hình ảnh vào bản trình bày PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    with open("watermark.png", "rb") as image_stream:
        watermark_image = presentation.images.add_image(image_stream.read())

    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 100, 100, watermark_image.width, watermark_image.height)

    watermark_shape.fill_format.fill_type = slides.FillType.PICTURE
    watermark_shape.fill_format.picture_fill_format.picture.image = watermark_image
    watermark_shape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    presentation.save("watermarked.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách thêm hình mờ vào PPTX bằng Python" intro="Làm theo các bước sau để thêm hình mờ văn bản vào bản trình bày PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp PPTX bằng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lấy trang chiếu cái đầu tiên từ tập hợp `masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi `add_auto_shape` để thêm hình chữ nhật vào trang chiếu cái.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi `add_text_frame` để thêm văn bản hình mờ, sau đó định dạng và khóa hình dạng.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi `save` với `SaveFormat.PPTX` để lưu bản trình bày có hình mờ.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Được xây dựng bằng Aspose.Slides" title="Thêm hình mờ vào tệp PPTX trực tuyến" description="Ứng dụng Aspose.Slides Watermark miễn phí được xây dựng bằng [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/vi/python-net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPTX của riêng bạn." button="Mở Aspose.Slides Watermark" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem Aspose.Slides thêm hình mờ như thế nào trước khi viết mã.
- Thêm hình mờ văn bản hoặc hình ảnh vào tệp PPTX của bạn.
- Tải xuống tệp có hình mờ.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác hỗ trợ hình mờ" subTitle="Với Python, bạn cũng có thể thêm hình mờ vào các định dạng bản trình bày khác được hỗ trợ." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
