---
title: 在 Java 中将 PNG 转换为 SVG
url: /zh/java/conversion/png-to-svg/
keywords: PNG 到 SVG，将 PNG 转换为 SVG，Java API，Java 库，PNG，SVG
description: 在 Java 中将 PNG 转换为 SVG。使用 Java 库 API 将 PNG 文件转换为 SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Java 中将 PNG 转换为 SVG" h2="高速和跨平台的 Java 库，有助于开发能够创建、合并、检查或转换 Microsoft PowerPoint 和 OpenOffice 演示文稿文件的应用程序，而无需使用 Microsoft 或 Open Office、Adobe PDF 等任何软件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 Java 中将 PNG 转换为 SVG" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/) 是一个强大的 Java 库，用于创建和操作演示文稿文件。此外，它提供了将 PNG 转换为 SVG 的灵活方法。使用**Aspose.Slides for Java**，任何开发人员或应用程序只需几行 Java 代码就可以将 PNG 转换为 SVG 文件。

作为现代文档处理 API，Aspose.Slides for Java 可以快速将 PNG 文件导出为 SVG 文件格式。 Aspose PowerPoint 库允许您将 PNG 转换为 SVG 和许多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Java 将 PNG 转换为 SVG" %}}
要将 PNG 转换为 SVG，您需要从 PNG 文件创建演示文稿并将其另存为 SVG。

{{% blocks/products/pf/agp/code-block title="将 PNG 转换为 SVG 的 Java 代码" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);

        FileOutputStream fileStream = new FileOutputStream("slide-" + index + ".svg");
        try {
            slide.writeAsSvg(fileStream);
        } finally {
            fileStream.close();
        }
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for Java API 将 PNG 转换为 SVG" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是在 Java 中将 PNG 转换为 SVG 的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source PNG files in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as SVG file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="将 PNG 转换为其他支持的格式" subTitle="您还可以转换 PNG 并保存为其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/conversion/png-to-pdf/" name="PNG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}