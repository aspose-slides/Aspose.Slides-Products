---
title: C# で PPTX を Word に変換する
url: /ja/net/conversion/pptx-to-word/
keywords: PPTX を Word、PPTX を Word、PPTX を DOC、PowerPoint を Word、C# API、.NET ライブラリに変換
description: C# で PPTX を Word に変換します。 .NET ライブラリ API を使用して PowerPoint を Word に変換する
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C# で PPTX を Word に変換する" h2="NET Framework、.NET Core、Windows Azure、Mono、または Xamarin プラットフォームで C# コードを使用して PowerPoint を Word に変換するための強力なクロスプラットフォーム .NET API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides と Aspose.Words を使用して PowerPoint を Word に変換" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ja/net/) および [**Aspose.Words for .NET**](https://products.aspose. com/words/net/) は、PowerPoint プレゼンテーション、Word ドキュメント、およびその他のファイルの操作と変換に使用される強力な .NET ライブラリです。 PowerPoint を Word に変換すると、基本的にプレゼンテーションのスライドの内容が Word 文書のページに移動されます。

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="C# で PowerPoint を Word に変換する" %}}
わずか数行のコードで PPTX を Word にすばやく変換できます

{{% blocks/products/pf/agp/code-block title="PowerPoint を Word に変換するための C# コード" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
var doc = new Document();
var builder = new DocumentBuilder(doc);
foreach (var slide in presentation.Slides)
{
    // generates and inserts slide image
    using var bitmap = slide.GetThumbnail(1, 1);
    using var stream = new MemoryStream();
    bitmap.Save(stream, ImageFormat.Png);
    stream.Seek(0, SeekOrigin.Begin);
    using var skBitmap = SKBitmap.Decode(stream);
    builder.InsertImage(skBitmap);

    // inserts slide texts
    foreach (var shape in slide.Shapes)
    {
        if (shape is AutoShape autoShape)
        {
            builder.Writeln(autoShape.TextFrame.Text);
        }
    }

    builder.InsertBreak(BreakType.PageBreak);
}
doc.Save("document.docx");
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="PPTXをWordに変換する方法" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for .NET** と **Aspose.Words for .NET** をインストールします。 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
2 つのライブラリを参照としてプロジェクトに追加します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation クラスと Doc クラスのインスタンスを作成します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Word に変換する PPTX プレゼンテーションを読み込みます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
スライドの内容に基づいて画像とテキストを生成します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果の Word ドキュメントを保存します。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="無料のオンラインコンバーター" sectionDescription="[Python で PPT を HTML に変換する方法](https://products.aspose.com/slides/ja/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="PowerPoint を他の形式のファイルに変換することもできます" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}