---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Xem hoặc chỉnh sửa siêu dữ liệu FODP bằng C++
url: /vi/cpp/metadata/fodp/
description: Xem và chỉnh sửa siêu dữ liệu FODP trong C++. Dùng Aspose.Slides for C++ để cập nhật thuộc tính tích hợp và tùy chỉnh của bản trình bày.
keywords: chỉnh sửa siêu dữ liệu FODP, xem siêu dữ liệu FODP, chỉnh sửa thuộc tính FODP, xem thuộc tính FODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chỉnh sửa siêu dữ liệu FODP bằng C++" h2="Dùng Aspose.Slides for C++ để xem và cập nhật thuộc tính tích hợp và tùy chỉnh trong tệp bản trình bày." related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sửa đổi thuộc tính FODP bằng C++" variant="code" %}}

Aspose.Slides for C++ cho phép bạn đọc và cập nhật siêu dữ liệu trong tệp FODP mà không cần Microsoft PowerPoint. Dùng đối tượng [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) do `Presentation::get_DocumentProperties` cung cấp để thay đổi thuộc tính tích hợp như `Author` và `Title`, hoặc quản lý thuộc tính tùy chỉnh bằng `idx_set`, `GetCustomPropertyName` và `RemoveCustomProperty`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Sửa đổi thuộc tính tích hợp của FODP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.fodp");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.fodp", SaveFormat::Fodp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Thêm thuộc tính tùy chỉnh vào FODP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.fodp");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.fodp", SaveFormat::Fodp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách xem hoặc chỉnh sửa siêu dữ liệu FODP trong C++" intro="Làm theo các bước sau để xem hoặc chỉnh sửa siêu dữ liệu FODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp FODP bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lấy đối tượng `DocumentProperties` bằng `get_DocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Đọc hoặc cập nhật các thuộc tính tích hợp như `Author` và `Title`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm, đọc hoặc xóa thuộc tính tùy chỉnh bằng `idx_set`, `GetCustomPropertyName` và `RemoveCustomProperty`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Được xây dựng bằng Aspose.Slides" title="Xem và chỉnh sửa siêu dữ liệu FODP trực tuyến" description="Ứng dụng Aspose.Slides Metadata miễn phí được xây dựng bằng [Aspose.Slides for C++](https://products.aspose.com/slides/vi/cpp/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp FODP của riêng bạn." button="Mở Aspose.Slides Metadata" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem Aspose.Slides đọc và ghi thuộc tính như thế nào trước khi viết mã.
- Xem và chỉnh sửa thuộc tính tích hợp và tùy chỉnh của tệp FODP.
- Lưu và tải xuống tệp đã cập nhật.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng siêu dữ liệu khác được hỗ trợ" subTitle="Với C++, bạn cũng có thể quản lý siêu dữ liệu của các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
