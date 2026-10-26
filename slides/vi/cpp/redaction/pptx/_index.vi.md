---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Che thông tin trong các bản trình bày PPTX bằng C++
url: /vi/cpp/redaction/pptx/
description: Che thông tin trong các bản trình bày PPTX bằng C++. Dùng Aspose.Slides for C++ để tìm và thay thế văn bản nhạy cảm trong tệp bản trình bày.
keywords: che thông tin PPTX, tìm và thay thế văn bản trong PPTX, cập nhật bản trình bày PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Che thông tin trong PPTX bằng C++" h2="Dùng Aspose.Slides for C++ để tìm và thay thế văn bản nhạy cảm trong tệp bản trình bày mà không cần Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Che thông tin trong bản trình bày PPTX qua C++" variant="code" %}}

Aspose.Slides for C++ cho phép bạn che thông tin trong bản trình bày PPTX bằng cách thay thế văn bản nhạy cảm trên các trang chiếu. Dùng `SlideUtil::FindAndReplaceText` với đối tượng `Presentation` để tìm kiếm trong bản trình bày và thay thế văn bản khớp trước khi lưu tệp đã cập nhật.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Che thông tin trong bản trình bày PPTX bằng C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách che thông tin trong PPTX qua C++" intro="Làm theo các bước sau để che thông tin trong bản trình bày PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPTX bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dùng phương thức [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) để tìm và thay thế văn bản nhạy cảm.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu tệp đã che thông tin bằng `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Được xây dựng bằng Aspose.Slides" title="Che thông tin trong tệp PPTX trực tuyến" description="Ứng dụng Aspose.Slides Redaction miễn phí được xây dựng bằng [Aspose.Slides for C++](https://products.aspose.com/slides/vi/cpp/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPTX của riêng bạn." button="Mở Aspose.Slides Redaction" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides tìm và thay thế văn bản trước khi bạn viết mã.
- Tìm và thay thế văn bản trong tệp PPTX của bạn, kể cả bằng biểu thức chính quy.
- Tải xuống tệp đã che thông tin.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác được hỗ trợ để che thông tin" subTitle="Với C++, bạn cũng có thể che thông tin trong các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
