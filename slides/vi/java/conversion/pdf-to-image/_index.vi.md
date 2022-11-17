---
title: Chuyển đổi PDF thành Image trong Java
url: /vi/java/conversion/pdf-to-image/
keywords: PDF sang Image, Chuyển đổi PDF sang Image, API Java, Thư viện Java, PDF, Image
description: Chuyển đổi PDF thành Image trong Java. Sử dụng API thư viện Java để chuyển đổi tệp PDF thành tệp Image
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chuyển đổi PDF thành Image trong Java" h2="Thư viện Java tốc độ cao và đa nền tảng giúp phát triển các ứng dụng với khả năng tạo, hợp nhất, kiểm tra hoặc chuyển đổi các tệp trình chiếu Microsoft PowerPoint và OpenOffice mà không cần sử dụng bất kỳ phần mềm nào như Microsoft hoặc Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi PDF thành Image trong Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/vi/java/) là một thư viện Java mạnh mẽ để tạo và thao tác các tệp bản trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để chuyển đổi PDF thành Image. Sử dụng **Aspose.Slides cho Java**, bất kỳ nhà phát triển hoặc ứng dụng nào cũng có thể chuyển đổi các tệp PDF sang Image chỉ bằng một vài dòng mã Java.

Là một API xử lý tài liệu hiện đại, Aspose.Slides dành cho Java xuất tệp PDF sang định dạng tệp Image một cách nhanh chóng. Thư viện Aspose PowerPoint cho phép bạn chuyển đổi PDF thành Images và nhiều định dạng tệp khác

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PDF thành Image bằng Java" %}}
Để chuyển đổi PDF sang Image, bạn cần tạo Bản trình bày từ tệp PDF và lưu dưới dạng Image.

{{% blocks/products/pf/agp/code-block title="Mã Java để chuyển đổi PDF thành Image" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    pres.getSlides().addFromPdf("InputPDF.pdf");
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách chuyển đổi PDF sang Image bằng API Aspose.Slides cho Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để chuyển đổi PDF thành Image trong Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt [**Aspose.Slides cho Java**](https://products.aspose.com/slides/vi/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm tham chiếu thư viện (nhập thư viện) vào dự án Java của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mở các tệp PDF nguồn trong Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả dưới dạng tệp Image.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Chuyển đổi PDF sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PDF và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}