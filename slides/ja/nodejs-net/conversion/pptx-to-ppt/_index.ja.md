---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: JavaScript で PPTX を PPT に変換します
url: /ja/nodejs-net/conversion/pptx-to-ppt/
keywords: PPTX から PPT、PPTX から PPT への変換、Node.js API、JavaScript ライブラリ、PPTX、PPT
description: JavaScript で PPTX を PPT に変換します。 Node.js ライブラリ API を使用して、PPTX ファイルを PPT に変換します
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="JavaScript で PPTX を PPT に変換します" h2="Aspose.Slides for Node.js via .NET は、PowerPoint プレゼンテーションを JavaScript のさまざまな形式に変換できる強力で使いやすいライブラリです。すべてのプレゼンテーション要素と形式をサポートし、それらにアクセスして変更するための豊富な API を提供します。また、スライドをさまざまな形式にエクスポートして、さらに処理したり共有したりすることもできます。" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="JavaScript を使用して PPTX を PPT に変換します" variant="code" %}}

PPTX を PPT に変換するには、PPTX ファイルからプレゼンテーションを作成し、それを PPT として保存する必要があります。

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX を PPT に変換するための JavaScript コード" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pptx");
try
{
    pres.save("output.ppt", SaveFormat.Ppt);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Node.js で PPTX を PPT に変換します" %}}

[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/ja/nodejs-net/) は、プレゼンテーション ファイルを作成および操作するための強力な Node.js ライブラリです。さらに、PPTX を PPT に変換する柔軟な方法を提供します。 **Aspose.Slides for Node.js via .NET** を使用すると、開発者やアプリケーションはわずか数行のコードで PPTX ファイルを PPT ファイルに変換できます。

最新のドキュメント処理 API として、.NET 経由の Aspose.Slides for Node.js は、PPTX ファイルを PPT ファイル形式にすばやくエクスポートします。 Aspose PowerPoint ライブラリを使用すると、PPTX を PPT やその他の多くのファイル形式に変換できます

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title=".NET API 経由で Aspose.Slides for Node.js を使用して PPTX を PPT に変換する方法" intro=".NET 経由で Aspose.Slides for Node.js を使用して PPTX を PPT に変換するには、JavaScript ファイルにパッケージをインポートし、Presentation クラスのインスタンスを作成する必要があります。 Presentation クラスは PowerPoint ドキュメントを表し、その要素にアクセスして操作するためのメソッドを提供します。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Node.js via .NET**](https://products.aspose.com/slides/ja/nodejs-net/) をインストールします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Node.js プロジェクトにライブラリ参照を追加します (ライブラリをインポートします)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Node.js でソース PPTX ファイルを開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}結果を PPT ファイルとして保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="PPTX を他のサポートされている形式に変換する" subTitle="PPTX を変換して他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-jpg/" name="PPTX TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-fodp/" name="PPTX TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-odp/" name="PPTX TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-otp/" name="PPTX TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-pot/" name="PPTX TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-potm/" name="PPTX TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-potx/" name="PPTX TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-pps/" name="PPTX TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/nodejs-net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
