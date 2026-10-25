---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Thêm hình mờ vào bản trình bày PPT bằng C++
url: /vi/cpp/watermark/ppt/
description: Thêm hình mờ văn bản hoặc hình ảnh vào bản trình bày PPT trong C++. Dùng Aspose.Slides for C++ để đặt hình mờ lên trang chiếu.
keywords: thêm hình mờ vào PPT, thêm hình mờ văn bản vào PPT, thêm hình mờ hình ảnh vào PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Thêm hình mờ vào bản trình bày PPT bằng C++" h2="Dùng Aspose.Slides for C++ để thêm hình mờ văn bản hoặc hình ảnh vào tệp bản trình bày mà không cần Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Thêm hình mờ vào bản trình bày PPT qua C++" variant="code" %}}

Aspose.Slides for C++ cho phép bạn thêm hình mờ văn bản hoặc hình ảnh vào bản trình bày PPT. Thêm hình dạng hình mờ vào trang chiếu cái bằng `AddAutoShape`, thêm văn bản bằng `AddTextFrame` hoặc tô hình dạng bằng hình ảnh được tải qua `File::ReadAllBytes` và `AddImage`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Thêm hình mờ văn bản vào PPT bằng C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Thêm hình mờ hình ảnh vào bản trình bày PPT bằng C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách thêm hình mờ vào PPT bằng C++" intro="Làm theo các bước sau để thêm hình mờ văn bản hoặc hình ảnh vào tệp PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPT bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chọn trang chiếu cái từ tập hợp `Presentation::get_Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm hình dạng hình mờ bằng phương thức `AddAutoShape`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm văn bản hình mờ bằng phương thức `AddTextFrame` hoặc đặt màu tô hình ảnh bằng `AddImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu tệp có hình mờ bằng `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Được xây dựng bằng Aspose.Slides" title="Thêm hình mờ vào tệp PPT trực tuyến" description="Ứng dụng Aspose.Slides Watermark miễn phí được xây dựng bằng [Aspose.Slides for C++](https://products.aspose.com/slides/vi/cpp/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPT của riêng bạn." button="Mở Aspose.Slides Watermark" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem Aspose.Slides thêm hình mờ như thế nào trước khi viết mã.
- Thêm hình mờ văn bản hoặc hình ảnh vào tệp PPT của bạn.
- Tải xuống tệp có hình mờ.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác hỗ trợ hình mờ" subTitle="Với C++, bạn cũng có thể thêm hình mờ vào các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
