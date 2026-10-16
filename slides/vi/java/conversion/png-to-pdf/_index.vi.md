---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Chuyển đổi PNG thành PDF trong Java
url: /vi/java/conversion/png-to-pdf/
keywords: PNG sang PDF, Chuyển đổi PNG sang PDF, API Java, Thư viện Java, PNG, PDF
description: Chuyển đổi PNG thành PDF trong Java. Sử dụng API thư viện Java để chuyển đổi tệp PNG thành tệp PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Chuyển đổi PNG thành PDF trong Java" h2="Thư viện Java tốc độ cao và đa nền tảng giúp phát triển các ứng dụng với khả năng tạo, hợp nhất, kiểm tra hoặc chuyển đổi các tệp trình chiếu Microsoft PowerPoint và OpenOffice mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi PNG thành PDF bằng Java" variant="code" %}}

Để chuyển đổi PNG sang PDF, bạn cần tạo Bản trình bày từ tệp PNG và lưu dưới dạng PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mã Java để chuyển đổi PNG thành PDF" >}}
```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    pres.save("index.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Chuyển đổi PNG thành PDF trong Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/vi/java/) là một thư viện Java mạnh mẽ để tạo và thao tác các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để chuyển đổi PNG thành PDF. Sử dụng **Aspose.Slides cho Java**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi các tệp PNG sang PDF chỉ bằng một vài dòng mã Java.

Là một API xử lý tài liệu hiện đại, Aspose.Slides dành cho Java xuất tệp PNG sang định dạng tệp PDF một cách nhanh chóng. Thư viện Aspose PowerPoint cho phép bạn chuyển đổi PNG thành PDFs và nhiều định dạng tệp khác

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cách chuyển đổi PNG sang PDF bằng API Aspose.Slides cho Java" intro="Đây là các bước để chuyển đổi PNG thành PDF trong Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cài đặt [**Aspose.Slides cho Java**](https://products.aspose.com/slides/vi/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Thêm tham chiếu thư viện (nhập thư viện) vào dự án Java của bạn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mở các tệp PNG nguồn trong Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lưu kết quả dưới dạng tệp PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Chuyển đổi trực tuyến miễn phí"
  description="[Cách chuyển đổi PPT sang HTML bằng Python](https://products.aspose.com/slides/vi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Chuyển đổi PNG sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PNG và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/java/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
