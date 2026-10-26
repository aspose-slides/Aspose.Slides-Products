---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tìm kiếm văn bản trong các bản trình bày PPT bằng C++
url: /vi/cpp/search/ppt/
description: Tìm kiếm văn bản trong bản trình bày PPT bằng C++. Dùng Aspose.Slides for C++ để tìm văn bản trong tệp bản trình bày.
keywords: tìm kiếm từ trong PPT, tìm văn bản trong PPT, tìm kiếm văn bản bản trình bày PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tìm kiếm văn bản trong PPT bằng C++" h2="Dùng Aspose.Slides for C++ để tìm văn bản trong tệp bản trình bày mà không cần Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tìm kiếm văn bản trong bản trình bày PPT qua C++" variant="code" %}}

Aspose.Slides for C++ cho phép bạn tìm kiếm văn bản trong bản trình bày PPT. Dùng `SlideUtil::GetAllTextBoxes` để thu thập các khung văn bản của một trang chiếu, sau đó kiểm tra xem văn bản của chúng có chứa cụm từ cần thiết hay không.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tìm kiếm văn bản trong bản trình bày PPT bằng C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách tìm kiếm văn bản trong PPT qua C++" intro="Làm theo các bước sau để tìm kiếm văn bản trong bản trình bày PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPT bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lấy trang chiếu cần thiết bằng `Presentation::get_Slides` và lấy các khung văn bản của nó bằng [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kiểm tra xem văn bản của từng khung có chứa cụm từ cần thiết hay không.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Được xây dựng bằng Aspose.Slides" title="Tìm kiếm văn bản trong tệp PPT trực tuyến" description="Ứng dụng Aspose.Slides Search miễn phí được xây dựng bằng [Aspose.Slides for C++](https://products.aspose.com/slides/vi/cpp/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPT của riêng bạn." button="Mở Aspose.Slides Search" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides tìm văn bản trước khi bạn viết mã.
- Tìm văn bản thuần hoặc biểu thức chính quy trong tệp PPT của bạn.
- Tải xuống kết quả dưới dạng tệp văn bản.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác được hỗ trợ để tìm kiếm" subTitle="Với C++, bạn cũng có thể tìm kiếm văn bản trong các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
