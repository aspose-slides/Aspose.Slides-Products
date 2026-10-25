---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Xem hoặc chỉnh sửa siêu dữ liệu PPTM bằng Python
url: /vi/python-net/metadata/pptm/
description: Xem và chỉnh sửa thuộc tính siêu dữ liệu tích hợp và tùy chỉnh trong tệp PPTM bằng Python.
keywords: chỉnh sửa siêu dữ liệu PPTM, xem siêu dữ liệu PPTM, chỉnh sửa thuộc tính PPTM, xem thuộc tính PPTM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Xem và chỉnh sửa siêu dữ liệu PPTM bằng Python" h2="Xây dựng ứng dụng Python đọc và sửa đổi thuộc tính tích hợp và tùy chỉnh của bản trình bày bằng Aspose.Slides." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Xem và sửa đổi siêu dữ liệu PPTM bằng Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/vi/python-net/) cho phép bạn đọc và cập nhật siêu dữ liệu tích hợp, đồng thời thêm, cập nhật hoặc xóa thuộc tính tài liệu tùy chỉnh trong bản trình bày PPTM. Truy cập đối tượng [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/) qua `Presentation.document_properties`, sửa đổi rồi lưu bản trình bày ở định dạng PPTM.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cập nhật thuộc tính tích hợp của PPTM – Python" >}}
```python
with slides.Presentation("presentation.pptm") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.pptm", slides.export.SaveFormat.PPTM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Thêm và xóa thuộc tính tùy chỉnh của PPTM – Python" >}}
```python
with slides.Presentation("presentation.pptm") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.pptm", slides.export.SaveFormat.PPTM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chỉnh sửa siêu dữ liệu PPTM bằng Python" intro="Làm theo các bước sau để chỉnh sửa siêu dữ liệu trong tệp PPTM." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở tệp PPTM bằng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Truy cập đối tượng `IDocumentProperties` qua `Presentation.document_properties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cập nhật thuộc tính tích hợp hoặc dùng `set_custom_property_value` và `remove_custom_property` cho thuộc tính tùy chỉnh.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu bản trình bày bằng `Presentation.save` và `SaveFormat.PPTM`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Được xây dựng bằng Aspose.Slides" title="Xem và chỉnh sửa siêu dữ liệu PPTM trực tuyến" description="Ứng dụng Aspose.Slides Metadata miễn phí được xây dựng bằng [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/vi/python-net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPTM của riêng bạn." button="Mở Aspose.Slides Metadata" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem Aspose.Slides đọc và ghi thuộc tính như thế nào trước khi viết mã.
- Xem và chỉnh sửa thuộc tính tích hợp và tùy chỉnh của tệp PPTM.
- Lưu và tải xuống tệp đã cập nhật.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng siêu dữ liệu khác được hỗ trợ" subTitle="Với Python, bạn cũng có thể quản lý siêu dữ liệu của các định dạng bản trình bày khác được hỗ trợ." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
