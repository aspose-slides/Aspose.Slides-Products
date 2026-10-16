---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: JavaScript で OTP を PDF に変換します
url: /ja/nodejs-net/conversion/otp-to-pdf/
keywords: OTP から PDF、OTP から PDF への変換、Node.js API、JavaScript ライブラリ、OTP、PDF
description: JavaScript で OTP を PDF に変換します。 Node.js ライブラリ API を使用して、OTP ファイルを PDF に変換します
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="JavaScript で OTP を PDF に変換します" h2="Aspose.Slides for Node.js via .NET は、PowerPoint プレゼンテーションを JavaScript のさまざまな形式に変換できる強力で使いやすいライブラリです。すべてのプレゼンテーション要素と形式をサポートし、それらにアクセスして変更するための豊富な API を提供します。また、スライドをさまざまな形式にエクスポートして、さらに処理したり共有したりすることもできます。" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="JavaScript を使用して OTP を PDF に変換します" variant="code" %}}

OTP を PDF に変換するには、OTP ファイルからプレゼンテーションを作成し、それを PDF として保存する必要があります。

{{< blocks/products/pf/slides-design-update-10-2026/code title="OTP を PDF に変換するための JavaScript コード" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.otp");
try
{
    pres.save("output.pdf", SaveFormat.Pdf);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Node.js で OTP を PDF に変換します" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/ja/nodejs-net/) は、プレゼンテーション ファイルを作成および操作するための強力な Node.js ライブラリです。さらに、OTP を PDF に変換する柔軟な方法を提供します。 **Aspose.Slides for Node.js via .NET** を使用すると、開発者やアプリケーションはわずか数行のコードで OTP ファイルを PDF ファイルに変換できます。

最新のドキュメント処理 API として、.NET 経由の Aspose.Slides for Node.js は、OTP ファイルを PDF ファイル形式にすばやくエクスポートします。 Aspose PowerPoint ライブラリを使用すると、OTP を PDF やその他の多くのファイル形式に変換できます

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title=".NET API 経由で Aspose.Slides for Node.js を使用して OTP を PDF に変換する方法" intro=".NET 経由で Aspose.Slides for Node.js を使用して OTP を PDF に変換するには、JavaScript ファイルにパッケージをインポートし、Presentation クラスのインスタンスを作成する必要があります。 Presentation クラスは PowerPoint ドキュメントを表し、その要素にアクセスして操作するためのメソッドを提供します。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/ja/nodejs-net/) をインストールします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Node.js プロジェクトにライブラリ参照を追加します (ライブラリをインポートします)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Node.js でソース OTP ファイルを開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}結果を PDF ファイルとして保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="OTP を他のサポートされている形式に変換する" subTitle="OTP を変換して他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-pptx/" name="OTP TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-ppt/" name="OTP TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-html/" name="OTP TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-png/" name="OTP TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-bmp/" name="OTP TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-jpg/" name="OTP TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-fodp/" name="OTP TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-gif/" name="OTP TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-odp/" name="OTP TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-pot/" name="OTP TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-potm/" name="OTP TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-potx/" name="OTP TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-pps/" name="OTP TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-ppsm/" name="OTP TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-ppsx/" name="OTP TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-pptm/" name="OTP TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-svg/" name="OTP TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/otp-to-tiff/" name="OTP TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
