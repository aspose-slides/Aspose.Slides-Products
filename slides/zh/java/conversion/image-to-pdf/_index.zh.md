---
title: 在 Java 中将 Image 转换为 PDF
url: /zh/java/conversion/image-to-pdf/
keywords: Image 到 PDF，将 Image 转换为 PDF，Java API，Java 库，Image，PDF
description: 在 Java 中将 Image 转换为 PDF。使用 Java 库 API 将 Image 文件转换为 PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Java 中将 Image 转换为 PDF" h2="高速和跨平台的 Java 库，有助于开发能够创建、合并、检查或转换 Microsoft PowerPoint 和 OpenOffice 演示文稿文件的应用程序，而无需使用 Microsoft 或 Open Office、Adobe PDF 等任何软件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 Java 中将 Image 转换为 PDF" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/) 是一个强大的 Java 库，用于创建和操作演示文稿文件。此外，它提供了将 Image 转换为 PDF 的灵活方法。使用**Aspose.Slides for Java**，任何开发人员或应用程序只需几行 Java 代码就可以将 Image 转换为 PDF 文件。

作为现代文档处理 API，Aspose.Slides for Java 可以快速将 Image 文件导出为 PDF 文件格式。 Aspose PowerPoint 库允许您将 Image 转换为 PDF 和许多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Java 将 Image 转换为 PDF" %}}
要将 Image 转换为 PDF，您需要从 Image 文件创建演示文稿并将其另存为 PDF。

{{% blocks/products/pf/agp/code-block title="将 Image 转换为 PDF 的 Java 代码" offSpacer="true" %}}

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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for Java API 将 Image 转换为 PDF" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是在 Java 中将 Image 转换为 PDF 的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安装 [**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将库引用（导入库）添加到您的 Java 项目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 Java 中打开源 Image 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将结果保存为 PDF 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="免费在线转换器" sectionDescription="[如何在 Python 中将 PPT 转换为 HTML](https://products.aspose.com/slides/zh/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="将 Image 转换为其他支持的格式" subTitle="您还可以转换 Image 并保存为其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}