---
title: Node.js で PDF を PPTM に変換します
url: /ja/nodejs-java/conversion/pdf-to-pptm/
keywords: PDF から PPTM、PDF から PPTM への変換、Node.js API、Node.js ライブラリ、PDF、PPTM
description: Node.js で PDF を PPTM に変換します。 Node.js ライブラリ API を使用して、PDF ファイルを PPTM に変換します
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Node.js で PDF を PPTM に変換します" h2="Java 経由の Aspose.Slides for Node.js は、PowerPoint プレゼンテーションを Node.js のさまざまな形式に変換できる強力で使いやすいライブラリです。すべてのプレゼンテーション要素と形式をサポートし、それらにアクセスして変更するための豊富な API を提供します。また、スライドをさまざまな形式にエクスポートして、さらに処理したり共有したりすることもできます。" >}}

{{% blocks/products/pf/feature-page-section h2="Node.js で PDF を PPTM に変換します" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/ja/nodejs-java/) は、プレゼンテーション ファイルを作成および操作するための強力な Node.js ライブラリです。さらに、PDF を PPTM に変換する柔軟な方法を提供します。 Java 経由で **Aspose.Slides for Node.js** を使用すると、開発者やアプリケーションはわずか数行のコードで PDF ファイルを PPTM ファイルに変換できます。

最新のドキュメント処理 API として、Aspose.Slides for Node.js は、PDF ファイルを PPTM ファイル形式にすばやくエクスポートします。 Aspose PowerPoint ライブラリを使用すると、PDF を PPTM やその他の多くのファイル形式に変換できます

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Node.js を使用して PDF を PPTM に変換します" %}}
PDF を PPTM に変換するには、PDF ファイルからプレゼンテーションを作成し、それを PPTM として保存する必要があります。

{{% blocks/products/pf/agp/code-block title="PDF を PPTM に変換するための Node.js コード" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation();
try
{
    pres.getSlides().removeAt(0);
    pres.getSlides().addFromPdf("welcome-to-powerpoint.pdf");

    pres.save("output.pptm", aspose.slides.SaveFormat.Pptm);
}
finally
{
    if (pres != null) pres.dispose();
} 

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java API 経由で Aspose.Slides for Node.js を使用して PDF を PPTM に変換する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Java 経由で Aspose.Slides for Node.js を使用して PDF を PPTM に変換するには、JavaScript ファイルにパッケージをインポートし、Presentation クラスのインスタンスを作成する必要があります。 Presentation クラスは PowerPoint ドキュメントを表し、その要素にアクセスして操作するためのメソッドを提供します。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/ja/nodejs-java/) をインストールします。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js プロジェクトにライブラリ参照を追加します (ライブラリをインポートします)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js でソース PDF ファイルを開きます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を PPTM ファイルとして保存します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PDF を他のサポートされている形式に変換する" subTitle="PDF を変換して他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}