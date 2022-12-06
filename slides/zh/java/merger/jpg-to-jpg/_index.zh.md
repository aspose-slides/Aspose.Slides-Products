---
title: 在 Java 中合并 JPG 图像
url: /zh/java/merger/jpg-to-jpg/
keywords: 合并 JPG、JPEG 到 JPG、加入 JPG、合并 JPG、Java API、Java 库
description: 在 Java 中将 JPG 合并为 JPG。使用 Java 库 API 合并 JPG 文件
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Java 中合并 JPG" h2="用于使用 Java 代码合并 JPG 图像的高速跨平台 Java 库" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 将 JPG 合并为 JPG" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/) 是一个功能强大的 Java 库，用于合并和操作演示文稿、图像和其他文件。当您将 JPG 合并为 JPG 时，实际上是将两张图像组合成一张图片。

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 Java 中将 JPG 合并为 JPG" %}}
使用[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/)，只需几行代码即可快速合并JPG文件

{{% blocks/products/pf/agp/code-block title="将 JPG 合并为 JPG 的 Java 代码" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    IPPImage image1 = pres.getImages().addImage(Files.readAllBytes("image1.jpg"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image1);

    IPPImage image2 = pres.getImages().addImage(Files.readAllBytes("image2.jpg"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail();
        ImageIO.write(bufferedImage, "JPEG", new File("image_java_" + index + ".jpg"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 Java 中合并 JPG" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
安装**Aspose.Slides for Java**。请参阅 [**安装**](https://docs.aspose.com/slides/java/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将库添加为项目中的参考。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
创建一个 Presentation 类的实例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加载要合并为相框的 JPG 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存生成的 JPG 图像。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="合并其他文件" subTitle="您还可以合并其他格式的文件以获取单个文件" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}