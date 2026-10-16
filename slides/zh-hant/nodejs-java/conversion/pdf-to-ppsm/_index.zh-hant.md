---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 Node.js 中將 PDF 轉換為 PPSM
url: /zh-hant/nodejs-java/conversion/pdf-to-ppsm/
keywords: PDF 到 PPSM、將 PDF 轉換為 PPSM、Node.js API、Node.js 庫、PDF、PPSM
description: 在 Node.js 中將 PDF 轉換為 PPSM。使用 Node.js 庫 API 將 PDF 文件轉換為 PPSM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 Node.js 中將 PDF 轉換為 PPSM" h2="Aspose.Slides for Node.js via Java 是一個功能強大且易於使用的庫，允許您將 PowerPoint 演示文稿轉換為 Node.js 中的各種格式。它支持所有演示元素和格式，並提供豐富的 API 來訪問和修改它們。它還允許您將幻燈片導出為各種格式以進行進一步處理或共享。" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Node.js 將 PDF 轉換為 PPSM" variant="code" %}}

要將 PDF 轉換為 PPSM，您需要從 PDF 文件創建演示文稿並將其另存為 PPSM。

{{< blocks/products/pf/slides-design-update-10-2026/code title="用於將 PDF 轉換為 PPSM 的 Node.js 代碼" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation();
try
{
    pres.getSlides().removeAt(0);
    pres.getSlides().addFromPdf("welcome-to-powerpoint.pdf");

    pres.save("output.ppsm", aspose.slides.SaveFormat.Ppsm);
}
finally
{
    if (pres != null) pres.dispose();
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 Node.js 中將 PDF 轉換為 PPSM" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/zh-hant/nodejs-java/) 是一個強大的Node.js 庫，用於創建和操作演示文稿文件。此外，它還提供了將 PDF 轉換為 PPSM 的靈活方法。使用 **Aspose.Slides for Node.js via Java**，任何開發人員或應用程序只需幾行代碼即可將 PDF 轉換為 PPSM 文件。

作為現代文檔處理 API，Aspose.Slides for Node.js 將 PDF 文件快速導出為 PPSM 文件格式。 Aspose PowerPoint 庫允許您將 PDF 轉換為 PPSM 以及許多其他文件格式

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何通過 Java API 使用 Aspose.Slides for Node.js 將 PDF 轉換為 PPSM" intro="要通過 Java 使用 Aspose.Slides for Node.js 將 PDF 轉換為 PPSM，您需要在 JavaScript 文件中導入該包並創建Presentation 類的實例。 Presentation 類表示 PowerPoint 文檔並提供訪問和操作其元素的方法。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/zh-hant/nodejs-java/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}將庫引用（導入庫）添加到您的 Node.js 項目。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在 Node.js 中打開源 PDF 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}將結果保存為 PPSM 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="將 PDF 轉換為其他支持的格式" subTitle="您還可以轉換 PDF 並保存為其他文件格式。查看下面所有支持的格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
