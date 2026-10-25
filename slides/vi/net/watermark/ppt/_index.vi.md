---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Thêm hình mờ vào bản trình bày PPT bằng C#
url: /vi/net/watermark/ppt/
description: Thêm hình mờ văn bản và hình ảnh vào bản trình bày PPT trong C# bằng Aspose.Slides for .NET.
keywords: thêm hình mờ vào PPT, thêm hình mờ văn bản vào PPT, thêm hình mờ hình ảnh vào PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Thêm hình mờ vào bản trình bày PPT bằng C#" h2="Xây dựng ứng dụng .NET chèn hình mờ văn bản hoặc hình ảnh vào tệp bản trình bày." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Thêm hình mờ vào bản trình bày PPT qua C#" variant="code" %}}

Với [Aspose.Slides for .NET](/slides/vi/net/), bạn có thể thêm hình mờ văn bản và hình ảnh vào bản trình bày PPT. Thêm hình dạng hình mờ vào trang chiếu cái để hình mờ xuất hiện trên các trang chiếu dùng trang chiếu cái đó.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Thêm hình mờ văn bản vào PPT bằng C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Thêm hình mờ hình ảnh vào bản trình bày PPT bằng C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách thêm hình mờ vào PPT bằng C#" intro="Làm theo các bước sau để thêm hình mờ văn bản hoặc hình ảnh vào tệp PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp `PPT` bằng lớp `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chọn một trang chiếu cái từ tập hợp `Presentation.Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức `AddAutoShape` để thêm hình dạng hình mờ.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gọi phương thức `AddTextFrame` để thêm văn bản hình mờ hoặc dùng `AddImage` cho hình mờ hình ảnh.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu tệp có hình mờ bằng `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Được xây dựng bằng Aspose.Slides" title="Thêm hình mờ vào tệp PPT trực tuyến" description="Ứng dụng Aspose.Slides Watermark miễn phí được xây dựng bằng [Aspose.Slides for .NET](https://products.aspose.com/slides/vi/net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPT của riêng bạn." button="Mở Aspose.Slides Watermark" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem Aspose.Slides thêm hình mờ như thế nào trước khi viết mã.
- Thêm hình mờ văn bản hoặc hình ảnh vào tệp PPT của bạn.
- Tải xuống tệp có hình mờ.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác hỗ trợ hình mờ" subTitle="Với C#, bạn cũng có thể thêm hình mờ vào các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
