---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Java 为 ODP 演示文稿文件添加水印
url: /zh/java/watermark/odp/
description: 使用 Aspose.Slides for Java 在 Java 中为 ODP 演示文稿添加文本和图片水印。
keywords: 为 ODP 添加水印, 为 ODP 添加文本水印, 为 ODP 添加图片水印
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Java 为 ODP 演示文稿添加水印" h2="构建使用服务器端 API 在演示文稿文件中插入文本或图片水印的 Java 应用程序。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="通过 Java 为 ODP 演示文稿添加水印" variant="code" %}}

借助 [Aspose.Slides for Java](/slides/zh/java/)，可以为 ODP 演示文稿添加文本和图片水印。将水印形状添加到母版幻灯片，水印就会显示在使用该母版的幻灯片上。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Java 为 ODP 添加文本水印" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Java 为 ODP 演示文稿添加图片水印" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Java 为 ODP 添加水印" intro="按照以下步骤为 ODP 文件添加文本或图片水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 类加载 `ODP` 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `getMasters` 方法选择母版幻灯片。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 `addAutoShape` 方法添加水印形状。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 `addTextFrame` 方法添加水印文本，或使用 `addImage` 添加图片水印。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将带水印的演示文稿保存为 ODP 格式。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="基于 Aspose.Slides 构建" title="在线为 ODP 文件添加水印" description="免费的 Aspose.Slides Watermark 应用基于 [Aspose.Slides for Java](https://products.aspose.com/slides/zh/java/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 ODP 文件。" button="打开 Aspose.Slides Watermark" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何添加水印。
- 为 ODP 文件添加文本或图片水印。
- 下载带水印的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持水印的格式" subTitle="使用 Java，还可以为以下格式添加水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
