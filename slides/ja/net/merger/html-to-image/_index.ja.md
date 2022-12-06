---
title: C# で HTML を画像にマージする
url: /ja/net/merger/html-to-image/
keywords: HTML を画像に結合、HTML を画像に結合、HTML を結合、HTML を結合、画像、C# API、.NET ライブラリ
description: C# で HTML を画像にマージします。 .NET ライブラリ API を使用して HTML を画像に結合する
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C# で画像をマージする" h2="NET Framework、.NET Core、Windows Azure、Mono、または Xamarin プラットフォームで C# コードを使用して HTML を画像にマージするための強力なクロスプラットフォーム .NET API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides を使用して HTML を画像にマージ" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ja/net/) は、プレゼンテーション、HTML ドキュメント、およびその他のファイルをマージおよび操作するために使用される強力な .NET ライブラリです。 HTML を画像にマージすると、HTML ドキュメントのコンテンツを効果的に組み合わせて 1 つの画像を取得できます。 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="C＃でHTMLを画像にマージする" %}}
[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ja/net/) を使用すると、わずか数行のコードで画像ファイルをすばやくマージできます。

{{% blocks/products/pf/agp/code-block title="HTML を画像にマージするための C# コード" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // removes default empty slide

    pres.Slides.AddFromHtml("page_1.html");
    pres.Slides.AddFromHtml("page_2.html");

    pres.Slides[0].GetThumbnail(new Size(960, 720)).Save("MergedFile.png", ImageFormat.Png);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C# で HTML を画像にマージする方法" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for .NET** をインストールします。 [**インストール**](https://docs.aspose.com/slides/net/installation/) を参照してください。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ライブラリを参照としてプロジェクトに追加します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーション クラスのインスタンスを作成します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
マージする HTML ドキュメントを読み込みます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果の画像を保存します。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="他のファイルをマージする" subTitle="他の形式のファイルを結合して 1 つのファイルにすることもできます" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
    
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}