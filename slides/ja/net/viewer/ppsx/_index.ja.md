---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C# で PPSX を表示
keywords: PPSX 表示, PPSX を開く, PPSX ビューアー, PPSX, PowerPoint, C# API, .NET ライブラリ
weight: 2370
url: /ja/net/viewer/ppsx/ 
description: C# で PPSX ファイルを表示します。Aspose.Slides for .NET を使用して、プレゼンテーション ファイルを開き、HTML として保存できます。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# で PPSX を表示" h2="PPSX ファイルを開いてレスポンシブな HTML として保存するための C# API。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides で PPSX を表示" %}}

PPSX ファイルを表示するには、高機能で使いやすい C# 向け API である [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net/) を使用します。[NuGet](https://www.nuget.org/packages/aspose.slides.net) パッケージ マネージャーを開き、**Aspose.Slides** を検索してインストールしてください。パッケージ マネージャー コンソールで次のコマンドを実行することもできます。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="パッケージ マネージャー コンソールのコマンド" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

[**Aspose.Slides for .NET**](/slides/ja/net/) を使用すると、数行のコードで PPSX ファイルを読み込み、レスポンシブな HTML として保存できます。

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSX を表示する C# コード" >}}
```cs
using var presentation = new Presentation("presentation.ppsx");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# で PPSX を表示する方法" intro="Aspose.Slides を使用すると、わずか数行のコードで PPSX ファイルを表示できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for .NET** をインストールします。[**インストール**](https://docs.aspose.com/slides/net/installation/) を参照してください。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}プロジェクトにライブラリへの参照を追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで `PPSX` ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}レスポンシブな HTML 出力用に `ResponsiveHtmlController` オブジェクトを作成します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`HtmlOptions` オブジェクトを作成し、`HtmlFormatter` プロパティを設定します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Html` を使用して PPSX ファイルを HTML として保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要件" intro="Aspose.Slides for .NET は主要なオペレーティング システムをすべてサポートしています。次の前提条件を満たしていることを確認してください。" %}}

- Microsoft Windows、または .NET Framework、.NET Core、Windows Azure、Mono、Xamarin に対応した OS
- Microsoft Visual Studio などの開発環境
- プロジェクトでの Aspose.Slides for .NET への参照

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Aspose.Slides で構築" title="PPSX ファイルをオンラインで表示" description="無料の Aspose.Slides Viewer アプリは、上記のコードと同じ API である [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net/) で構築されています。アプリを開いて、ご自身の PPSX ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Viewer を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がファイルをどうレンダリングするかを確認できます。
- PPSX ファイルをアップロードして、スライドをすぐに表示できます。
- PC でもモバイルでも動作し、PowerPoint は不要です。
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSX" readMoreLink="https://docs.fileformat.com/presentation/ppsx/" %}}

PPSX ファイルは、Microsoft PowerPoint 2007 以降で作成される Open XML 形式の PowerPoint スライド ショーです。PowerPoint 97–2003 で使われる PPS 形式の、Open XML による後継形式です。既定で編集モードで開く PPTX ファイルとは異なり、PPSX ファイルは直接スライド ショーとして開きます。プレゼンテーションのスライドの順序を保持し、画像、音声、その他の埋め込みメディアを含めることができます。

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他のファイルを表示" subTitle="その他の形式のプレゼンテーションも開いて表示できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/odp/" name="ODP" description="OpenDocument プレゼンテーション" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/otp/" name="OTP" description="OpenDocument プレゼンテーション テンプレート" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/pot/" name="POT" description="PowerPoint 97-2003 テンプレート" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/potm/" name="POTM" description="PowerPoint マクロ有効テンプレート" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/potx/" name="POTX" description="PowerPoint テンプレート" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/pps/" name="PPS" description="PowerPoint 97-2003 スライド ショー" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/ppsm/" name="PPSM" description="PowerPoint マクロ有効スライド ショー" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/ppt/" name="PPT" description="PowerPoint 97-2003 プレゼンテーション" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/pptm/" name="PPTM" description="PowerPoint マクロ有効プレゼンテーション" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/pptx/" name="PPTX" description="PowerPoint プレゼンテーション" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
