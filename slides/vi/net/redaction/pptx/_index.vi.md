---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Che thông tin trong tệp bản trình bày PPTX bằng .NET
url: /vi/net/redaction/pptx/
description: Mã nguồn C# để tìm và thay thế văn bản trong bản trình bày PPTX.
keywords: Che thông tin PPTX, tìm và thay thế văn bản trong PPTX, cập nhật bản trình bày PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Che thông tin trong tệp PPTX bằng C#" h2="Xây dựng ứng dụng .NET tìm và thay thế văn bản trong bản trình bày bằng API phía máy chủ." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Che thông tin trong bản trình bày PPTX bằng C#" variant="code" %}}

Với [Aspose.Slides for .NET](/slides/vi/net/), bạn có thể tìm và thay thế văn bản trong bản trình bày PPTX. Dùng `Presentation.ReplaceText` với `TextSearchOptions` để kiểm soát việc tìm kiếm, sau đó lưu bản trình bày đã sửa đổi.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Che thông tin trong bản trình bày PPTX bằng C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách che thông tin trong bản trình bày PPTX bằng C#" intro="Làm theo các bước sau để thay thế văn bản trong bản trình bày PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPTX bằng `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dùng [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) với `TextSearchOptions` để thay thế văn bản cần thiết.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu bản trình bày đã sửa đổi bằng `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Được xây dựng bằng Aspose.Slides" title="Che thông tin trong tệp PPTX trực tuyến" description="Ứng dụng Aspose.Slides Redaction miễn phí được xây dựng bằng [Aspose.Slides for .NET](https://products.aspose.com/slides/vi/net/), cùng API với đoạn mã ở trên. Hãy mở ứng dụng và xem API có thể làm gì với các tệp PPTX của riêng bạn." button="Mở Aspose.Slides Redaction" note="[Tất cả ứng dụng miễn phí](https://products.aspose.app/slides/family)" >}}
- Chạy trong trình duyệt, không cần cài đặt gì.
- Xem cách Aspose.Slides tìm và thay thế văn bản trước khi bạn viết mã.
- Tìm và thay thế văn bản trong tệp PPTX của bạn, kể cả bằng biểu thức chính quy.
- Tải xuống tệp đã che thông tin.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng khác được hỗ trợ để che thông tin" subTitle="Với C#, bạn cũng có thể che thông tin trong các định dạng sau." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/vi/net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
