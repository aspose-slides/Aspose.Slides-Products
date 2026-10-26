---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tìm kiếm văn bản trong tệp bản trình bày ODP bằng Java
url: /vi/java/search/odp/
description: Tìm kiếm văn bản trong bản trình bày ODP bằng Java với Aspose.Slides for Java.
keywords: tìm kiếm từ trong ODP, tìm kiếm văn bản trong ODP, tìm kiếm văn bản bản trình bày ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tìm kiếm văn bản trong ODP bằng Java" h2="Xây dựng ứng dụng Java tìm kiếm văn bản trong tệp bản trình bày bằng API phía máy chủ." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tìm kiếm văn bản trong bản trình bày ODP qua Java" variant="code" %}}

Với [Aspose.Slides for Java](/slides/vi/java/), bạn có thể tìm kiếm văn bản trong bản trình bày ODP. Dùng phương thức `SlideUtil.getAllTextBoxes` để thu thập các khung văn bản, sau đó kiểm tra các đối tượng `ITextFrame`, `IParagraph` và `IPortion`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tìm kiếm văn bản trong bản trình bày ODP bằng Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách tìm kiếm văn bản trong ODP qua Java" intro="Làm theo các bước sau để tìm kiếm văn bản trong bản trình bày ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp ODP bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức `SlideUtil.getAllTextBoxes` để thu thập các khung văn bản từ mỗi trang chiếu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kiểm tra các đối tượng `ITextFrame`, `IParagraph` và `IPortion` để tìm văn bản khớp.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Được xây dựng bằng Aspose.Slides" title="Tìm kiếm văn bản trong tệp ODP trực tuyến" description="Ứng dụng Aspose.Slides Search miễn phí được xây dựng bằng [Aspose.Slides for Java](https://products.aspose.com/slides/vi/java/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp ODP của riêng bạn." button="Mở Aspose.Slides Search" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides tìm văn bản trước khi bạn viết mã.
- Tìm văn bản thuần hoặc biểu thức chính quy trong tệp ODP của bạn.
- Tải xuống kết quả dưới dạng tệp văn bản.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác được hỗ trợ để tìm kiếm" subTitle="Với Java, bạn cũng có thể tìm kiếm văn bản trong các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
