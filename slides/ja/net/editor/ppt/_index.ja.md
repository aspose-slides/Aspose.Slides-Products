---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C# で PPT を編集する
url: /ja/net/editor/ppt/
keywords: PPT の編集、PowerPoint の編集、PPT、PowerPoint、C# API、.NET ライブラリ
description: C# で PPT を編集します。 .NET ライブラリ API を使用して PowerPoint プレゼンテーションを編集する
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# で PPT を編集する" h2="NET Framework、.NET Core、Windows Azure、Mono、または Xamarin プラットフォームで C# コードを使用して PPT を編集するための強力なクロスプラットフォーム .NET API" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# で PPT を編集する" variant="code" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ja/net/) を使用すると、わずか数行のコードで新しいテキスト行を PPT ドキュメントに追加できます。

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT を編集するための C# コード" >}}
```cs
using (Presentation presentation = new Presentation("pres.ppt"))
{
    AutoShape shape = (AutoShape)presentation.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";
    presentation.Save("pres.ppt", SaveFormat.Ppt);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides を使用して PPT を編集する" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ja/net/) は、プレゼンテーションの操作と編集に使用される強力な .NET ライブラリです。新しいテキスト行を追加することで、PPT プレゼンテーションを編集できます。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# で PPT を編集する方法" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for .NET** をインストールします。 [**インストール**](https://docs.aspose.com/slides/net/installation/) を参照してください。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ライブラリを参照としてプロジェクトに追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}プレゼンテーション クラスのインスタンスを作成します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}編集する PPT プレゼンテーションを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}新しいテキスト行を追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}変更した PowerPoint ファイルを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="他のファイルを編集する" subTitle="他の形式のファイルを編集することもできます" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
