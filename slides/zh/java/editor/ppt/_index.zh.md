---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 用Java编辑PPT
url: /zh/java/editor/ppt/
keywords: 编辑 PPT, 编辑 PowerPoint, PPT, PowerPoint, Java API, Java Library
description: 用Java编辑PPT。使用 Java 库 API 编辑 PowerPoint 演示文稿
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="用Java编辑PPT" h2="使用Java代码编辑PPT的高速跨平台Java库" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="用Java编辑PPT" variant="code" %}}

使用 [**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/)，您只需几行代码就可以在 PPT 文档中添加新的文本行。

{{< blocks/products/pf/slides-design-update-10-2026/code title="编辑PPT的Java代码" >}}
```java

Presentation pres = new Presentation("pres.ppt");
try {
    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Aspose.Slides 编辑 PPT" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/) 是一个功能强大的 Java 库，用于操作和编辑演示文稿。您可以通过向其中添加新的文本行来编辑 PPT 演示文稿。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何用Java编辑PPT" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装**Aspose.Slides for Java**。请参阅 [**安装**](https://docs.aspose.com/slides/java/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将库添加为项目中的参考。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}创建一个 Presentation 类的实例。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}加载要编辑的 PPT 演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}添加新的文本行。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}保存更改后的 PowerPoint 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="编辑其他文件" subTitle="您还可以编辑其他格式的文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
