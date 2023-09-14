---
title: 在 Node.js 中将 POTX 转换为 BMP
url: /zh/nodejs-java/conversion/potx-to-bmp/
keywords: POTX 到 BMP、将 POTX 转换为 BMP、Node.js API、Node.js 库、POTX、BMP
description: 在 Node.js 中将 POTX 转换为 BMP。使用 Node.js 库 API 将 POTX 文件转换为 BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Node.js 中将 POTX 转换为 BMP" h2="Aspose.Slides for Node.js via Java 是一个功能强大且易于使用的库，允许您将 PowerPoint 演示文稿转换为 Node.js 中的各种格式。它支持所有演示元素和格式，并提供丰富的 API 来访问和修改它们。它还允许您将幻灯片导出为各种格式以进行进一步处理或共享。" >}}

{{% blocks/products/pf/feature-page-section h2="在 Node.js 中将 POTX 转换为 BMP" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/zh/nodejs-java/) 是一个强大的 Node.js 库，用于创建和操作演示文件。此外，它还提供了将 POTX 转换为 BMP 的灵活方法。使用 **Aspose.Slides for Node.js via Java**，任何开发人员或应用程序都只需几行代码即可将 POTX 转换为 BMP 文件。

作为现代文档处理 API，Aspose.Slides for Node.js 将 POTX 文件快速导出为 BMP 文件格式。 Aspose PowerPoint 库允许您将 POTX 转换为 BMP 以及许多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Node.js 将 POTX 转换为 BMP" %}}
要将 POTX 转换为 BMP，您需要从 POTX 文件创建演示文稿并将其另存为 BMP。

{{% blocks/products/pf/agp/code-block title="用于将 POTX 转换为 BMP 的 Node.js 代码" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.potx");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".bmp");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "bmp", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何通过 Java API 使用 Aspose.Slides for Node.js 将 POTX 转换为 BMP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="要通过 Java 使用 Aspose.Slides for Node.js 将 POTX 转换为 BMP，您需要在 JavaScript 文件中导入包并创建 Presenter 类的实例。 Presentation 类表示 PowerPoint 文档并提供访问和操作其元素的方法。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安装[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/zh/nodejs-java/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将库引用（导入库）添加到您的 Node.js 项目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 Node.js 中打开源 POTX 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将结果保存为 BMP 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="将 POTX 转换为其他支持的格式" subTitle="您还可以转换 POTX 并保存为其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-pptx/" name="POTX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-ppt/" name="POTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-pdf/" name="POTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-html/" name="POTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-png/" name="POTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-jpg/" name="POTX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-fodp/" name="POTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-gif/" name="POTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-odp/" name="POTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-otp/" name="POTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-pot/" name="POTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-potm/" name="POTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-pps/" name="POTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-ppsm/" name="POTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-ppsx/" name="POTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-pptm/" name="POTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-svg/" name="POTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/nodejs-java/conversion/potx-to-tiff/" name="POTX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}