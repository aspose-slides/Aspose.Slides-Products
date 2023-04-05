---
title: Hợp nhất SVG thành PNG trong Java
url: /vi/java/merger/svg-to-png/
keywords: Hợp nhất SVG thành PNG, SVG thành PNG, Nối SVG thành PNG, Kết hợp SVG thành PNG, API Java, Thư viện Java
description: Hợp nhất SVG thành PNG trong Java. Sử dụng API thư viện Java để kết hợp các tệp SVG và PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Hợp nhất SVG thành PNG trong Java" h2="Thư viện Java tốc độ cao và đa nền tảng để hợp nhất các hình ảnh SVG thành PNG bằng mã Java" >}}

{{% blocks/products/pf/feature-page-section h2="Hợp nhất SVG thành PNG bằng Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/vi/java/) là một thư viện Java mạnh mẽ được sử dụng để hợp nhất và thao tác với các bản trình bày, hình ảnh và các tệp khác. Khi bạn hợp nhất SVG với PNG, bạn đang kết hợp hiệu quả các hình ảnh SVG để có được một hình ảnh PNG.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Hợp nhất SVG thành PNG trong Java" %}}
Sử dụng [**Aspose.Slides for Java**](https://products.aspose.com/slides/vi/java/), bạn có thể nhanh chóng hợp nhất các tệp SVG với PNG chỉ bằng một vài dòng mã

{{% blocks/products/pf/agp/code-block title="Mã Java để hợp nhất SVG với PNG" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    String svgContent = new String(Files.readAllBytes("image.svg"));
    ISvgImage svgImage = new SvgImage(svgContent);
    IPPImage ppImage = pres.getImages().addImage(svgImage);
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 
			ppImage.getWidth(), ppImage.getHeight(), ppImage);

    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail();
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cách hợp nhất SVG thành PNG trong Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt **Aspose.Slides cho Java**. Xem [**Cài đặt**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm thư viện làm tài liệu tham khảo trong dự án của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tạo một thể hiện của lớp Trình bày.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải các tệp SVG mà bạn muốn hợp nhất lại với nhau.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu hình ảnh PNG kết quả.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Hợp nhất các tệp PDF trực tuyến" sectionDescription="[Cách hợp nhất PDF trong Python](https://products.aspose.com/slides/vi/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Hợp nhất các tệp khác" subTitle="Bạn cũng có thể kết hợp các tệp ở các định dạng khác để có được một tệp duy nhất" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}