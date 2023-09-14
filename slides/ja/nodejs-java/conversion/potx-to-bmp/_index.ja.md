---
title: Node.js で POTX を BMP に変換します
url: /ja/nodejs-java/conversion/potx-to-bmp/
keywords: POTX から BMP、POTX から BMP への変換、Node.js API、Node.js ライブラリ、POTX、BMP
description: Node.js で POTX を BMP に変換します。 Node.js ライブラリ API を使用して、POTX ファイルを BMP に変換します
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Node.js で POTX を BMP に変換します" h2="Java 経由の Aspose.Slides for Node.js は、PowerPoint プレゼンテーションを Node.js のさまざまな形式に変換できる強力で使いやすいライブラリです。すべてのプレゼンテーション要素と形式をサポートし、それらにアクセスして変更するための豊富な API を提供します。また、スライドをさまざまな形式にエクスポートして、さらに処理したり共有したりすることもできます。" >}}

{{% blocks/products/pf/feature-page-section h2="Node.js で POTX を BMP に変換します" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/ja/nodejs-java/) は、プレゼンテーション ファイルを作成および操作するための強力な Node.js ライブラリです。さらに、POTX を BMP に変換する柔軟な方法を提供します。 Java 経由で **Aspose.Slides for Node.js** を使用すると、開発者やアプリケーションはわずか数行のコードで POTX ファイルを BMP ファイルに変換できます。

最新のドキュメント処理 API として、Aspose.Slides for Node.js は、POTX ファイルを BMP ファイル形式にすばやくエクスポートします。 Aspose PowerPoint ライブラリを使用すると、POTX を BMP やその他の多くのファイル形式に変換できます

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Node.js を使用して POTX を BMP に変換します" %}}
POTX を BMP に変換するには、POTX ファイルからプレゼンテーションを作成し、それを BMP として保存する必要があります。

{{% blocks/products/pf/agp/code-block title="POTX を BMP に変換するための Node.js コード" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.potx");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".bmp");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "bmp", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java API 経由で Aspose.Slides for Node.js を使用して POTX を BMP に変換する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Java 経由で Aspose.Slides for Node.js を使用して POTX を BMP に変換するには、JavaScript ファイルにパッケージをインポートし、Presentation クラスのインスタンスを作成する必要があります。 Presentation クラスは PowerPoint ドキュメントを表し、その要素にアクセスして操作するためのメソッドを提供します。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/ja/nodejs-java/) をインストールします。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js プロジェクトにライブラリ参照を追加します (ライブラリをインポートします)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js でソース POTX ファイルを開きます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を BMP ファイルとして保存します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="POTX を他のサポートされている形式に変換する" subTitle="POTX を変換して他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-pptx/" name="POTX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-ppt/" name="POTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-pdf/" name="POTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-html/" name="POTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-png/" name="POTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-jpg/" name="POTX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-fodp/" name="POTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-gif/" name="POTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-odp/" name="POTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-otp/" name="POTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-pot/" name="POTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-potm/" name="POTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-pps/" name="POTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-ppsm/" name="POTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-ppsx/" name="POTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-pptm/" name="POTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-svg/" name="POTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/nodejs-java/conversion/potx-to-tiff/" name="POTX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}