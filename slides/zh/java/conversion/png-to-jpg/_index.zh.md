---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 Java 中将 PNG 转换为 JPG
url: /zh/java/conversion/png-to-jpg/
keywords: PNG 到 JPG，将 PNG 转换为 JPG，Java API，Java 库，PNG，JPG
description: 在 Java 中将 PNG 转换为 JPG。使用 Java 库 API 将 PNG 文件转换为 JPG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 Java 中将 PNG 转换为 JPG" h2="高速和跨平台的 Java 库，有助于开发能够创建、合并、检查或转换 Microsoft PowerPoint 和 OpenOffice 演示文稿文件的应用程序，而无需使用 Microsoft 或 Open Office、Adobe PDF 等任何软件。" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Java 将 PNG 转换为 JPG" variant="code" %}}

要将 PNG 转换为 JPG，您需要从 PNG 文件创建演示文稿并将其另存为 JPG。

{{< blocks/products/pf/slides-design-update-10-2026/code title="将 PNG 转换为 JPG 的 Java 代码" >}}
```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "jpeg", new File("image_java_" + index + ".jpg"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 Java 中将 PNG 转换为 JPG" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/) 是一个强大的 Java 库，用于创建和操作演示文稿文件。此外，它提供了将 PNG 转换为 JPG 的灵活方法。使用**Aspose.Slides for Java**，任何开发人员或应用程序只需几行 Java 代码就可以将 PNG 转换为 JPG 文件。

作为现代文档处理 API，Aspose.Slides for Java 可以快速将 PNG 文件导出为 JPG 文件格式。 Aspose PowerPoint 库允许您将 PNG 转换为 JPG 和许多其他文件格式

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Aspose.Slides for Java API 将 PNG 转换为 JPG" intro="这些是在 Java 中将 PNG 转换为 JPG 的步骤。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装 [**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将库引用（导入库）添加到您的 Java 项目。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在 Java 中打开源 PNG 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将结果保存为 JPG 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="免费在线转换器"
  description="[如何在 Python 中将 PPT 转换为 HTML](https://products.aspose.com/slides/zh/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="将 PNG 转换为其他支持的格式" subTitle="您还可以转换 PNG 并保存为其他文件格式。查看下面所有支持的格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
