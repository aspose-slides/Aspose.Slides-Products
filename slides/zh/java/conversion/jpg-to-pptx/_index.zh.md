---
title: 在 Java 中将 JPG 转换为 PPTX
url: /zh/java/conversion/jpg-to-pptx/
keywords: 将 JPG 转换为 PPTX、将 JPG 转换为 PPTX、PowerPoint、JPG、PPTX、Java API、Java 库
description: 在 Java 中将 JPG 转换为 PPTX。使用 Java 库 API 将 JPG 图像转换为 PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Java 中将 JPG 转换为 PPTX" h2="强大的跨平台 Java API，用于使用 Java 代码将 JPG 转换为 PPTX" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 将 JPG 转换为 PPTX" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/) 是一个功能强大的 Java 库，用于创建、转换和操作 PowerPoint 演示文稿、PDF、HTML 文档和其他文件。将 JPG 转换为 PPTX 时，实际上是在创建包含基于 JPG 图像的幻灯片的 PowerPoint 演示文稿。

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="在 Java 中将 JPG 转换为 PPTX" %}}
使用 [**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/)，只需几行代码，您就可以将 JPG 图片转换为 PowerPoint 演示文稿：

{{% blocks/products/pf/agp/code-block title="JPG转PPTX的Java代码" offSpacer="true" %}}
```java
Presentation pres = new Presentation();
try {
	ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

	pres.save("pres.pptx", SaveFormat.Pptx);
} finally {
	if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 Java 中将 JPG 转换为 PPTX" >}}


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
加载要转换为 PPTX 的 JPG 图像。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将生成的文件另存为 PPTX 演示文稿。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="免费在线转换器" sectionDescription="[如何在 Python 中将 PPT 转换为 HTML](https://products.aspose.com/slides/zh/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的 PowerPoint 转换" subTitle="您还可以将其他格式的文件转换为 PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}