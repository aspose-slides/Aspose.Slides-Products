---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 JavaScript 中将 POTM 转换为 HTML
url: /zh/nodejs-net/conversion/potm-to-html/
keywords: POTM 到 HTML、将 POTM 转换为 HTML、Node.js API、JavaScript 库、POTM、HTML
description: 在 JavaScript 中将 POTM 转换为 HTML。使用 Node.js 库 API 将 POTM 文件转换为 HTML
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 JavaScript 中将 POTM 转换为 HTML" h2="Aspose.Slides for Node.js via .NET 是一个功能强大且易于使用的库，允许您将 PowerPoint 演示文稿转换为 JavaScript 中的各种格式。它支持所有演示元素和格式，并提供丰富的 API 来访问和修改它们。它还允许您将幻灯片导出为各种格式以进行进一步处理或共享。" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 JavaScript 将 POTM 转换为 HTML" variant="code" %}}

要将 POTM 转换为 HTML，您需要从 POTM 文件创建演示文稿并将其另存为 HTML。

{{< blocks/products/pf/slides-design-update-10-2026/code title="用于将 POTM 转换为 HTML 的 JavaScript 代码" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.potm");
try
{
    pres.save("pres.html", SaveFormat.Html);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 Node.js 中将 POTM 转换为 HTML" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/zh/nodejs-net/) 是一个强大的 Node.js 库，用于创建和操作演示文件。此外，它还提供了将 POTM 转换为 HTML 的灵活方法。通过 .NET 使用 **Aspose.Slides for Node.js**，任何开发人员或应用程序只需几行代码即可将 POTM 转换为 HTML 文件。

作为现代文档处理 API，Aspose.Slides for Node.js 通过 .NET 将 POTM 文件快速导出为 HTML 文件格式。 Aspose PowerPoint 库允许您将 POTM 转换为 HTML 以及许多其他文件格式

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何通过 .NET API 使用 Aspose.Slides for Node.js 将 POTM 转换为 HTML" intro="要通过 .NET 使用 Aspose.Slides for Node.js 将 POTM 转换为 HTML，您需要在 JavaScript 文件中导入该包并创建 Presenter 类的实例。 Presentation 类表示 PowerPoint 文档并提供访问和操作其元素的方法。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/zh/nodejs-net/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将库引用（导入库）添加到您的 Node.js 项目。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在 Node.js 中打开源 POTM 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将结果保存为 HTML 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="将 POTM 转换为其他支持的格式" subTitle="您还可以转换 POTM 并保存为其他文件格式。查看下面所有支持的格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-pptx/" name="POTM TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-ppt/" name="POTM TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-pdf/" name="POTM TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-png/" name="POTM TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-bmp/" name="POTM TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-jpg/" name="POTM TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-fodp/" name="POTM TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-gif/" name="POTM TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-odp/" name="POTM TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-otp/" name="POTM TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-pot/" name="POTM TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-potx/" name="POTM TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-pps/" name="POTM TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-ppsm/" name="POTM TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-ppsx/" name="POTM TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-pptm/" name="POTM TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-svg/" name="POTM TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/nodejs-net/conversion/potm-to-tiff/" name="POTM TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
