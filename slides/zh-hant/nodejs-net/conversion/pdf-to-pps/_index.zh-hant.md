---
title: 在 JavaScript 中將 PDF 轉換為 PPS
url: /zh-hant/nodejs-net/conversion/pdf-to-pps/
keywords: PDF 到 PPS、將 PDF 轉換成 PPS、Node.js API、JavaScript 函式庫、PDF、PPS
description: 在 JavaScript 中將 PDF 轉換為 PPS。使用 Node.js 函式庫 API 將 PDF 檔案轉換為 PPS
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 JavaScript 中將 PDF 轉換為 PPS" h2="Aspose.Slides for Node.js via .NET 是一個功能強大且易於使用的函式庫，可讓您將 PowerPoint 簡報轉換為 JavaScript 中的各種格式。它支援所有演示元素和格式，並提供豐富的 API 來存取和修改它們。它還允許您將幻燈片匯出為各種格式以進行進一步處理或共用。" >}}

{{% blocks/products/pf/feature-page-section h2="在 Node.js 中將 PDF 轉換為 PPS" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/zh-hant/nodejs-net/) 是一個強大的Node.js 函式庫，用於建立和操作示範文件。此外，它還提供了將 PDF 轉換為 PPS 的靈活方法。透過 .NET 使用 **Aspose.Slides for Node.js**，任何開發人員或應用程式只需幾行程式碼即可將 PDF 轉換為 PPS 檔案。

作為現代文件處理 API，Aspose.Slides for Node.js 透過 .NET 將 PDF 檔案快速匯出為 PPS 檔案格式。 Aspose PowerPoint 函式庫可讓您將 PDF 轉換為 PPS 以及許多其他檔案格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 JavaScript 將 PDF 轉換為 PPS" %}}
要將 PDF 轉換為 PPS，您需要從 PDF 文件創建演示文稿並將其另存為 PPS。

{{% blocks/products/pf/agp/code-block title="用於將 PDF 轉換為 PPS 的 JavaScript 程式碼" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat, ShapeType } = asposeSlides;

var pres = new Presentation();
try
{
    pres.slides.removeAt(0);
    var slides = pres.slides.addFromPdf("welcome-to-powerpoint.pdf");

    pres.save("output.pps", SaveFormat.Pps);
}
finally
{
    if (pres != null) pres.dispose();
} 

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何透過 .NET API 使用 Aspose.Slides for Node.js 將 PDF 轉換為 PPS" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="要透過 .NET 使用 Aspose.Slides for Node.js 將 PDF 轉換為 PPS，您需要在 JavaScript 檔案中匯入該套件並建立 Presenter 類別的實例。 Presentation 類別表示 PowerPoint 文件並提供存取和操作其元素的方法。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安裝[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/zh-hant/nodejs-net/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將庫引用（導入庫）添加到您的 Node.js 項目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 Node.js 中打開源 PDF 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將結果保存為 PPS 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="將 PDF 轉換為其他支持的格式" subTitle="您還可以轉換 PDF 並保存為其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}