---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Xóa chú thích PPT bằng C++
url: /vi/cpp/annotation/ppt/ 
description: Mã nguồn C++ để xóa chú thích khỏi bản trình bày PPT.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Xóa nhận xét và tác giả nhận xét khỏi PPT bằng C++" h2="Xây dựng ứng dụng C++ quản lý nhận xét và tác giả trong tệp bản trình bày bằng API phía máy chủ." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Xóa nhận xét khỏi PPT qua C++" variant="code" %}}

Dùng [Aspose.Slides for C++](/slides/vi/cpp/) để xóa nhận xét và tác giả nhận xét khỏi bản trình bày PPT. Ví dụ dưới đây xóa nhận xét của từng tác giả từ `get_CommentAuthors`, sau đó xóa sạch tập hợp tác giả nhận xét.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Xóa chú thích khỏi PPT – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.ppt");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách xóa nhận xét khỏi PPT qua C++" intro="Làm theo các bước sau để xóa nhận xét và tác giả nhận xét khỏi bản trình bày PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt Aspose.Slides for C++. Xem [Cài đặt](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPT bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Duyệt qua các tác giả nhận xét từ `get_CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Xóa nhận xét của từng tác giả bằng `get_Comments()->Clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Xóa sạch tập hợp tác giả nhận xét.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu bản trình bày đã cập nhật với `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Được xây dựng bằng Aspose.Slides" title="Xóa nhận xét PPT trực tuyến" description="Ứng dụng Aspose.Slides Annotation miễn phí được xây dựng bằng [Aspose.Slides for C++](https://products.aspose.com/slides/vi/cpp/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPT của riêng bạn." button="Mở Aspose.Slides Annotation" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides xóa nhận xét trước khi bạn viết mã.
- Xóa tất cả nhận xét khỏi tệp PPT của bạn.
- Tải xuống tệp đã được làm sạch.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác được hỗ trợ cho chú thích" subTitle="Với C++, bạn cũng có thể xóa chú thích khỏi các định dạng khác." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
