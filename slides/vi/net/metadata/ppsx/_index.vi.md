---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Xem hoặc chỉnh sửa siêu dữ liệu tệp PPSX bằng .NET
url: /vi/net/metadata/ppsx/
description: Mã nguồn C# để xem hoặc chỉnh sửa siêu dữ liệu PPSX.
keywords: chỉnh sửa siêu dữ liệu PPSX, xem siêu dữ liệu PPSX, chỉnh sửa thuộc tính PPSX, xem thuộc tính PPSX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chỉnh sửa thuộc tính PPSX bằng C#" h2="Xây dựng ứng dụng .NET đọc và sửa đổi thuộc tính tích hợp và tùy chỉnh của bản trình bày bằng API phía máy chủ." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sửa đổi thuộc tính PPSX bằng C#" variant="code" %}}

Với [Aspose.Slides for .NET](/slides/vi/net/), nhà phát triển có thể truy cập và sửa đổi thuộc tính tích hợp và tùy chỉnh của bản trình bày. Dùng thuộc tính [`DocumentProperties`](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) của đối tượng `Presentation` để đọc và cập nhật siêu dữ liệu PPSX.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Sửa đổi thuộc tính tích hợp của PPSX – C#" >}}
```cs
using var presentation = new Presentation("presentation.ppsx");
var documentProperties = presentation.DocumentProperties;

documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

presentation.Save("DocumentProperties_out.ppsx", SaveFormat.Ppsx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Thêm thuộc tính tùy chỉnh vào PPSX – C#" >}}
```cs
using var presentation = new Presentation();
var documentProperties = presentation.DocumentProperties;

documentProperties["New Custom"] = 12;
documentProperties["My Name"] = "Aspose Metadata Editor";
documentProperties["Custom"] = 124;

var propertyName = documentProperties.GetCustomPropertyName(2);
documentProperties.RemoveCustomProperty(propertyName);

presentation.Save("CustomDocumentProperties_out.ppsx", SaveFormat.Ppsx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách xem hoặc chỉnh sửa siêu dữ liệu PPSX trong C#" intro="Làm theo các bước sau để xem hoặc chỉnh sửa siêu dữ liệu PPSX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPSX bằng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lấy đối tượng `DocumentProperties` của bản trình bày.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Đọc hoặc cập nhật các thuộc tính tích hợp như `Author`, `Title` và `Subject`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Truy cập và sửa đổi thuộc tính tùy chỉnh bằng `DocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Được xây dựng bằng Aspose.Slides" title="Xem và chỉnh sửa siêu dữ liệu PPSX trực tuyến" description="Ứng dụng Aspose.Slides Metadata miễn phí được xây dựng bằng [Aspose.Slides for .NET](https://products.aspose.com/slides/vi/net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPSX của riêng bạn." button="Mở Aspose.Slides Metadata" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem Aspose.Slides đọc và ghi thuộc tính như thế nào trước khi viết mã.
- Xem và chỉnh sửa thuộc tính tích hợp và tùy chỉnh của tệp PPSX.
- Lưu và tải xuống tệp đã cập nhật.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng siêu dữ liệu khác được hỗ trợ" subTitle="Với C#, bạn cũng có thể quản lý siêu dữ liệu của các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
