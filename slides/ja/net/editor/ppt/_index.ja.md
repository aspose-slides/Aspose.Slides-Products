---
title: C# で PPT を編集する
url: /ja/net/editor/ppt/
keywords: PPT の編集、PowerPoint の編集、PPT、PowerPoint、C# API、.NET ライブラリ
description: C# で PPT を編集します。 .NET ライブラリ API を使用して PowerPoint プレゼンテーションを編集する
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C# で PPT を編集する" h2="NET Framework、.NET Core、Windows Azure、Mono、または Xamarin プラットフォームで C# コードを使用して PPT を編集するための強力なクロスプラットフォーム .NET API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides を使用して PPT を編集する" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ja/net/) は、プレゼンテーションの操作と編集に使用される強力な .NET ライブラリです。新しいテキスト行を追加することで、PPT プレゼンテーションを編集できます。 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="C# で PPT を編集する" %}}
[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ja/net/) を使用すると、わずか数行のコードで新しいテキスト行を PPT ドキュメントに追加できます。

{{% blocks/products/pf/agp/code-block title="PPT を編集するための C# コード" offSpacer="true" %}}
```cs
using (Presentation presentation = new Presentation("pres.ppt"))
{
    AutoShape shape = (AutoShape)presentation.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";
    presentation.Save("pres.ppt", SaveFormat.Ppt);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C# で PPT を編集する方法" >}}


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
編集する PPT プレゼンテーションを読み込みます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
新しいテキスト行を追加します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
変更した PowerPoint ファイルを保存します。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="他のファイルを編集する" subTitle="他の形式のファイルを編集することもできます" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}