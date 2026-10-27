---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C# で POT を表示
keywords: POT 表示, POT を開く, POT ビューアー, POT, PowerPoint, C# API, .NET ライブラリ
weight: 6750
url: /ja/net/viewer/pot/ 
description: C# で POT ファイルを表示します。Aspose.Slides for .NET を使用して、プレゼンテーション ファイルを開き、HTML として保存できます。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# で POT を表示" h2="POT ファイルを開いてレスポンシブな HTML として保存するための C# API。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides で POT を表示" %}}

POT ファイルを表示するには、高機能で使いやすい C# 向け API である [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net/) を使用します。[NuGet](https://www.nuget.org/packages/aspose.slides.net) パッケージ マネージャーを開き、**Aspose.Slides** を検索してインストールしてください。パッケージ マネージャー コンソールで次のコマンドを実行することもできます。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="パッケージ マネージャー コンソールのコマンド" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

[**Aspose.Slides for .NET**](/slides/ja/net/) を使用すると、数行のコードで POT ファイルを読み込み、レスポンシブな HTML として保存できます。

{{< blocks/products/pf/slides-design-update-10-2026/code title="POT を表示する C# コード" >}}
```cs
using var presentation = new Presentation("presentation.pot");

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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# で POT を表示する方法" intro="Aspose.Slides を使用すると、わずか数行のコードで POT ファイルを表示できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for .NET** をインストールします。[**インストール**](https://docs.aspose.com/slides/net/installation/) を参照してください。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}プロジェクトにライブラリへの参照を追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで `POT` ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}レスポンシブな HTML 出力用に `ResponsiveHtmlController` オブジェクトを作成します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`HtmlOptions` オブジェクトを作成し、`HtmlFormatter` プロパティを設定します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Html` を使用して POT ファイルを HTML として保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要件" intro="Aspose.Slides for .NET は主要なオペレーティング システムをすべてサポートしています。次の前提条件を満たしていることを確認してください。" %}}

- Microsoft Windows、または .NET Framework、.NET Core、Windows Azure、Mono、Xamarin に対応した OS
- Microsoft Visual Studio などの開発環境
- プロジェクトでの Aspose.Slides for .NET への参照

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Aspose.Slides で構築" title="POT ファイルをオンラインで表示" description="無料の Aspose.Slides Viewer アプリは、上記のコードと同じ API である [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net/) で構築されています。アプリを開いて、ご自身の POT ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Viewer を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がファイルをどうレンダリングするかを確認できます。
- POT ファイルをアップロードして、スライドをすぐに表示できます。
- PC でもモバイルでも動作し、PowerPoint は不要です。
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POT" readMoreLink="https://docs.fileformat.com/presentation/pot/" %}}

拡張子 .POT のファイルは、バイナリ形式の Microsoft PowerPoint プレゼンテーション テンプレートです。この形式は PowerPoint 97-2003 のファイル形式ファミリーに属します。POT ファイルには、新しいプレゼンテーションを作成するための再利用可能なスライド レイアウト、テーマ、スタイル、背景、配色、フォント、その他の書式が格納されます。

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他のファイルを表示" subTitle="その他の形式のプレゼンテーションも開いて表示できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/odp/" name="ODP" description="OpenDocument プレゼンテーション" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/otp/" name="OTP" description="OpenDocument プレゼンテーション テンプレート" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/potm/" name="POTM" description="PowerPoint マクロ有効テンプレート" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/potx/" name="POTX" description="PowerPoint テンプレート" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/pps/" name="PPS" description="PowerPoint 97-2003 スライド ショー" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/ppsm/" name="PPSM" description="PowerPoint マクロ有効スライド ショー" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/ppsx/" name="PPSX" description="PowerPoint スライド ショー" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/ppt/" name="PPT" description="PowerPoint 97-2003 プレゼンテーション" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/pptm/" name="PPTM" description="PowerPoint マクロ有効プレゼンテーション" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/viewer/pptx/" name="PPTX" description="PowerPoint プレゼンテーション" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
