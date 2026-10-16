---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: JavaScript で FODP を PDF に変換します
url: /ja/nodejs-net/conversion/fodp-to-pdf/
keywords: FODP から PDF、FODP から PDF への変換、Node.js API、JavaScript ライブラリ、FODP、PDF
description: JavaScript で FODP を PDF に変換します。 Node.js ライブラリ API を使用して、FODP ファイルを PDF に変換します
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="JavaScript で FODP を PDF に変換します" h2="Aspose.Slides for Node.js via .NET は、PowerPoint プレゼンテーションを JavaScript のさまざまな形式に変換できる強力で使いやすいライブラリです。すべてのプレゼンテーション要素と形式をサポートし、それらにアクセスして変更するための豊富な API を提供します。また、スライドをさまざまな形式にエクスポートして、さらに処理したり共有したりすることもできます。" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="JavaScript を使用して FODP を PDF に変換します" variant="code" %}}

FODP を PDF に変換するには、FODP ファイルからプレゼンテーションを作成し、それを PDF として保存する必要があります。

{{< blocks/products/pf/slides-design-update-10-2026/code title="FODP を PDF に変換するための JavaScript コード" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.fodp");
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Node.js で FODP を PDF に変換します" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/ja/nodejs-net/) は、プレゼンテーション ファイルを作成および操作するための強力な Node.js ライブラリです。さらに、FODP を PDF に変換する柔軟な方法を提供します。 **Aspose.Slides for Node.js via .NET** を使用すると、開発者やアプリケーションはわずか数行のコードで FODP ファイルを PDF ファイルに変換できます。

最新のドキュメント処理 API として、.NET 経由の Aspose.Slides for Node.js は、FODP ファイルを PDF ファイル形式にすばやくエクスポートします。 Aspose PowerPoint ライブラリを使用すると、FODP を PDF やその他の多くのファイル形式に変換できます

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title=".NET API 経由で Aspose.Slides for Node.js を使用して FODP を PDF に変換する方法" intro=".NET 経由で Aspose.Slides for Node.js を使用して FODP を PDF に変換するには、JavaScript ファイルにパッケージをインポートし、Presentation クラスのインスタンスを作成する必要があります。 Presentation クラスは PowerPoint ドキュメントを表し、その要素にアクセスして操作するためのメソッドを提供します。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/ja/nodejs-net/) をインストールします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Node.js プロジェクトにライブラリ参照を追加します (ライブラリをインポートします)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Node.js でソース FODP ファイルを開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}結果を PDF ファイルとして保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="FODP を他のサポートされている形式に変換する" subTitle="FODP を変換して他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-png/" name="FODP TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-bmp/" name="FODP TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-jpg/" name="FODP TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-potm/" name="FODP TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-svg/" name="FODP TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/fodp-to-tiff/" name="FODP TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
