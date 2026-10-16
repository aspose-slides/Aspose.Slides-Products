---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 Node.js 中將 PPTM 轉換為 SVG
url: /zh-hant/nodejs-java/conversion/pptm-to-svg/
keywords: PPTM 到 SVG、將 PPTM 轉換為 SVG、Node.js API、Node.js 庫、PPTM、SVG
description: 在 Node.js 中將 PPTM 轉換為 SVG。使用 Node.js 庫 API 將 PPTM 文件轉換為 SVG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 Node.js 中將 PPTM 轉換為 SVG" h2="Aspose.Slides for Node.js via Java 是一個功能強大且易於使用的庫，允許您將 PowerPoint 演示文稿轉換為 Node.js 中的各種格式。它支持所有演示元素和格式，並提供豐富的 API 來訪問和修改它們。它還允許您將幻燈片導出為各種格式以進行進一步處理或共享。" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Node.js 將 PPTM 轉換為 SVG" variant="code" %}}

要將 PPTM 轉換為 SVG，您需要從 PPTM 文件創建演示文稿並將其另存為 SVG。

{{< blocks/products/pf/slides-design-update-10-2026/code title="用於將 PPTM 轉換為 SVG 的 Node.js 代碼" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.pptm");
try
{
    var slide = pres.getSlides().get_Item(0);
    var svgStream = java.newInstanceSync("java.io.FileOutputStream", "image.svg");
    slide.writeAsSvg(svgStream);
    svgStream.close();
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 Node.js 中將 PPTM 轉換為 SVG" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/zh-hant/nodejs-java/) 是一個強大的Node.js 庫，用於創建和操作演示文稿文件。此外，它還提供了將 PPTM 轉換為 SVG 的靈活方法。使用 **Aspose.Slides for Node.js via Java**，任何開發人員或應用程序只需幾行代碼即可將 PPTM 轉換為 SVG 文件。

作為現代文檔處理 API，Aspose.Slides for Node.js 將 PPTM 文件快速導出為 SVG 文件格式。 Aspose PowerPoint 庫允許您將 PPTM 轉換為 SVG 以及許多其他文件格式

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何通過 Java API 使用 Aspose.Slides for Node.js 將 PPTM 轉換為 SVG" intro="要通過 Java 使用 Aspose.Slides for Node.js 將 PPTM 轉換為 SVG，您需要在 JavaScript 文件中導入該包並創建Presentation 類的實例。 Presentation 類表示 PowerPoint 文檔並提供訪問和操作其元素的方法。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/zh-hant/nodejs-java/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}將庫引用（導入庫）添加到您的 Node.js 項目。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在 Node.js 中打開源 PPTM 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}將結果保存為 SVG 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="將 PPTM 轉換為其他支持的格式" subTitle="您還可以轉換 PPTM 並保存為其他文件格式。查看下面所有支持的格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-html/" name="PPTM TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-png/" name="PPTM TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-bmp/" name="PPTM TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-jpg/" name="PPTM TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-fodp/" name="PPTM TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-gif/" name="PPTM TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-odp/" name="PPTM TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-otp/" name="PPTM TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-pot/" name="PPTM TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-potm/" name="PPTM TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-potx/" name="PPTM TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-pps/" name="PPTM TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
