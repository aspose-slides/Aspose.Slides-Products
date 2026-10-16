---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 JavaScript 中將 PPTM 轉換為 OTP
url: /zh-hant/nodejs-net/conversion/pptm-to-otp/
keywords: PPTM 到 OTP、將 PPTM 轉換成 OTP、Node.js API、JavaScript 函式庫、PPTM、OTP
description: 在 JavaScript 中將 PPTM 轉換為 OTP。使用 Node.js 函式庫 API 將 PPTM 檔案轉換為 OTP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 JavaScript 中將 PPTM 轉換為 OTP" h2="Aspose.Slides for Node.js via .NET 是一個功能強大且易於使用的函式庫，可讓您將 PowerPoint 簡報轉換為 JavaScript 中的各種格式。它支援所有演示元素和格式，並提供豐富的 API 來存取和修改它們。它還允許您將幻燈片匯出為各種格式以進行進一步處理或共用。" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 JavaScript 將 PPTM 轉換為 OTP" variant="code" %}}

要將 PPTM 轉換為 OTP，您需要從 PPTM 文件創建演示文稿並將其另存為 OTP。

{{< blocks/products/pf/slides-design-update-10-2026/code title="用於將 PPTM 轉換為 OTP 的 JavaScript 程式碼" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pptm");
try
{
    pres.save("output.otp", SaveFormat.Otp);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 Node.js 中將 PPTM 轉換為 OTP" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/zh-hant/nodejs-net/) 是一個強大的Node.js 函式庫，用於建立和操作示範文件。此外，它還提供了將 PPTM 轉換為 OTP 的靈活方法。透過 .NET 使用 **Aspose.Slides for Node.js**，任何開發人員或應用程式只需幾行程式碼即可將 PPTM 轉換為 OTP 檔案。

作為現代文件處理 API，Aspose.Slides for Node.js 透過 .NET 將 PPTM 檔案快速匯出為 OTP 檔案格式。 Aspose PowerPoint 函式庫可讓您將 PPTM 轉換為 OTP 以及許多其他檔案格式

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何透過 .NET API 使用 Aspose.Slides for Node.js 將 PPTM 轉換為 OTP" intro="要透過 .NET 使用 Aspose.Slides for Node.js 將 PPTM 轉換為 OTP，您需要在 JavaScript 檔案中匯入該套件並建立 Presenter 類別的實例。 Presentation 類別表示 PowerPoint 文件並提供存取和操作其元素的方法。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/zh-hant/nodejs-net/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}將庫引用（導入庫）添加到您的 Node.js 項目。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在 Node.js 中打開源 PPTM 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}將結果保存為 OTP 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="將 PPTM 轉換為其他支持的格式" subTitle="您還可以轉換 PPTM 並保存為其他文件格式。查看下面所有支持的格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-pptx/" name="PPTM TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-ppt/" name="PPTM TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-pdf/" name="PPTM TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-html/" name="PPTM TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-png/" name="PPTM TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-bmp/" name="PPTM TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-jpg/" name="PPTM TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-fodp/" name="PPTM TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-gif/" name="PPTM TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-odp/" name="PPTM TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-pot/" name="PPTM TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-potm/" name="PPTM TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-potx/" name="PPTM TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-pps/" name="PPTM TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-svg/" name="PPTM TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/nodejs-net/conversion/pptm-to-tiff/" name="PPTM TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
