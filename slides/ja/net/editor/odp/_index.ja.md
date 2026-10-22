---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NETを介してODPファイルを編集する
url: /ja/net/editor/odp/ 
description: .NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームでODPドキュメントを編集するためのC＃ソースコード。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C＃でODP形式を編集する" h2="MicrosoftやAdobePDFなどのソフトウェアを使用せずに、サーバー側のAspose.Slides for.NETAPIを使用したネイティブで高性能なODPドキュメント編集。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,OTP,PDF,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C＃を使用してODPファイルを編集する方法" %}}

ODPファイルを編集するには、機能が豊富で強力な<a href="https://products.aspose.com/slides/ja/net"> Aspose.Slides for .NET</a>APIを使用します。あらゆるエディター向けのC＃プラットフォーム用の使いやすいAPI。 <a href="https://www.nuget.org/packages/aspose.slides.net"> NuGet </a>パッケージマネージャーを開き、<b> Aspose.Slides</b>を検索してインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="指示" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODPファイルの編集-C＃" >}}
```cs
using var presentation = new Presentation("document.odp");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C＃でODPファイルを編集する手順" intro="を使用した基本的なドキュメント編集 [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net) APIは、ほんの数行のコードで実行できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` オブジェクトで ODP ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}変数を使って対象のスライドと図形にアクセスします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`TextFrame` を使ってテキストを更新します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Odp` を指定して、編集したプレゼンテーションを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要求" intro="当社のAPIは、すべての主要なプラットフォームとオペレーティングシステムでサポートされています。以下のコードを実行する前に、システムに次の前提条件があることを確認してください。" %}}

- Microsoft Windows、または.NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームと互換性のあるOS
- MicrosoftVisualStudioのような開発環境
- プロジェクトで参照されているAspose.Slidesfor.NETDLL-上の[ダウンロード]ボタンを使用してNuGetからインストールします

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice).

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
