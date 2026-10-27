---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Xóa chú thích PPTX bằng .NET
url: /vi/net/annotation/pptx/ 
description: Xóa nhận xét và tác giả nhận xét khỏi bản trình bày PPTX bằng C#.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Xóa nhận xét và tác giả nhận xét khỏi PPTX bằng C#" h2="Xây dựng ứng dụng .NET quản lý nhận xét và tác giả trong tệp bản trình bày bằng API phía máy chủ." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Xóa nhận xét khỏi PPTX qua C#" variant="code" %}}

Dùng [Aspose.Slides for .NET](/slides/vi/net/) để xóa nhận xét và tác giả nhận xét khỏi tệp bản trình bày PPTX. Ví dụ dưới đây xóa sạch tập hợp `Comments` của từng tác giả, sau đó xóa sạch tập hợp `CommentAuthors` của bản trình bày.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Xóa chú thích khỏi PPTX – C#" >}}
```cs
using var presentation = new Presentation("example.pptx");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách xóa nhận xét khỏi PPTX qua C#" intro="Làm theo các bước sau để xóa nhận xét và tác giả nhận xét khỏi bản trình bày PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt Aspose.Slides for .NET. Xem [Cài đặt](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPTX bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Duyệt qua tập hợp `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Xóa sạch tập hợp `Comments` của từng tác giả nhận xét.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Xóa sạch tập hợp `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu bản trình bày đã cập nhật với `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Được xây dựng bằng Aspose.Slides" title="Xóa nhận xét PPTX trực tuyến" description="Ứng dụng Aspose.Slides Annotation miễn phí được xây dựng bằng [Aspose.Slides for .NET](https://products.aspose.com/slides/vi/net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPTX của riêng bạn." button="Mở Aspose.Slides Annotation" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides xóa nhận xét trước khi bạn viết mã.
- Xóa tất cả nhận xét khỏi tệp PPTX của bạn.
- Tải xuống tệp đã được làm sạch.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác được hỗ trợ cho chú thích" subTitle="Với C#, bạn cũng có thể xóa chú thích khỏi các định dạng khác." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
