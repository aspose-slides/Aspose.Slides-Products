---
title: 在 Node.js 中將 PPT 轉換為 SVG
url: /zh-hant/nodejs-java/conversion/ppt-to-svg/
keywords: PPT 到 SVG、將 PPT 轉換為 SVG、Node.js API、Node.js 庫、PPT、SVG
description: 在 Node.js 中將 PPT 轉換為 SVG。使用 Node.js 庫 API 將 PPT 文件轉換為 SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Node.js 中將 PPT 轉換為 SVG" h2="Aspose.Slides for Node.js via Java 是一個功能強大且易於使用的庫，允許您將 PowerPoint 演示文稿轉換為 Node.js 中的各種格式。它支持所有演示元素和格式，並提供豐富的 API 來訪問和修改它們。它還允許您將幻燈片導出為各種格式以進行進一步處理或共享。" >}}

{{% blocks/products/pf/feature-page-section h2="在 Node.js 中將 PPT 轉換為 SVG" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/zh-hant/nodejs-java/) 是一個強大的Node.js 庫，用於創建和操作演示文稿文件。此外，它還提供了將 PPT 轉換為 SVG 的靈活方法。使用 **Aspose.Slides for Node.js via Java**，任何開發人員或應用程序只需幾行代碼即可將 PPT 轉換為 SVG 文件。

作為現代文檔處理 API，Aspose.Slides for Node.js 將 PPT 文件快速導出為 SVG 文件格式。 Aspose PowerPoint 庫允許您將 PPT 轉換為 SVG 以及許多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Node.js 將 PPT 轉換為 SVG" %}}
要將 PPT 轉換為 SVG，您需要從 PPT 文件創建演示文稿並將其另存為 SVG。

{{% blocks/products/pf/agp/code-block title="用於將 PPT 轉換為 SVG 的 Node.js 代碼" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.ppt");
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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何通過 Java API 使用 Aspose.Slides for Node.js 將 PPT 轉換為 SVG" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="要通過 Java 使用 Aspose.Slides for Node.js 將 PPT 轉換為 SVG，您需要在 JavaScript 文件中導入該包並創建Presentation 類的實例。 Presentation 類表示 PowerPoint 文檔並提供訪問和操作其元素的方法。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安裝[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/zh-hant/nodejs-java/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將庫引用（導入庫）添加到您的 Node.js 項目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 Node.js 中打開源 PPT 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將結果保存為 SVG 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="將 PPT 轉換為其他支持的格式" subTitle="您還可以轉換 PPT 並保存為其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-jpg/" name="PPT TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-fodp/" name="PPT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-odp/" name="PPT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-otp/" name="PPT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-pot/" name="PPT TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-potm/" name="PPT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-potx/" name="PPT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-pps/" name="PPT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}