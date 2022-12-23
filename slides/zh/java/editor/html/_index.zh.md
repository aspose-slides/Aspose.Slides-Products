---
title: 在 Java 中编辑 HTML
url: /zh/java/editor/html/
keywords: 编辑 HTML、HTML、Java API、Java 库
description: 在 Java 中编辑 HTML。使用 Java 库 API 编辑 HTML 文件
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Java 中编辑 HTML" h2="用于使用 Java 代码编辑 HTML 的高速跨平台 Java 库" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 编辑 HTML" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/) 是一个功能强大的 Java 库，用于操作和编辑演示文稿、HTML 文档和其他文件。您可以通过向其中添加新的文本行来编辑 HTML 文档。 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 Java 中编辑 HTML" %}}
使用 [**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/)，您只需几行代码即可向 HTML 文档添加新的文本行。

{{% blocks/products/pf/agp/code-block title="用于编辑 HTML 的 Java 代码" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        pres.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("page.html", SaveFormat.Html5);
} catch(IOException e) {
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 Java 中编辑 HTML" >}}


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
加载要编辑的 HTML 文档。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加新的文本行。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存更改后的 HTML 文件。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="编辑其他文件" subTitle="您还可以编辑其他格式的文件" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}