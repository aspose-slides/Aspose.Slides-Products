---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NETを介してPPSMファイルを編集する
url: /ja/net/editor/ppsm/ 
description: .NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームでPPSMドキュメントを編集するためのC＃ソースコード。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C＃でPPSM形式を編集する" h2="MicrosoftやAdobePDFなどのソフトウェアを使用せずに、サーバー側のAspose.Slides for.NETAPIを使用したネイティブで高性能なPPSMドキュメント編集。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C＃を使用してPPSMファイルを編集する方法" %}}

PPSMファイルを編集するには、機能が豊富で強力な<a href="https://products.aspose.com/slides/ja/net"> Aspose.Slides for .NET</a>APIを使用します。あらゆるエディター向けのC＃プラットフォーム用の使いやすいAPI。 <a href="https://www.nuget.org/packages/aspose.slides.net"> NuGet </a>パッケージマネージャーを開き、<b> Aspose.Slides</b>を検索してインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="指示" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSMファイルの編集-C＃" >}}
```cs
using var presentation = new Presentation("document.ppsm");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.ppsm", SaveFormat.Ppsm);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C＃でPPSMファイルを編集する手順" intro="を使用した基本的なドキュメント編集 [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net) APIは、ほんの数行のコードで実行できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` オブジェクトで PPSM ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}変数を使って対象のスライドと図形にアクセスします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`TextFrame` を使ってテキストを更新します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Ppsm` を指定して、編集したプレゼンテーションを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要求" intro="当社のAPIは、すべての主要なプラットフォームとオペレーティングシステムでサポートされています。以下のコードを実行する前に、システムに次の前提条件があることを確認してください。" %}}

- Microsoft Windows、または.NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームと互換性のあるOS
- MicrosoftVisualStudioのような開発環境
- プロジェクトで参照されているAspose.Slidesfor.NETDLL-上の[ダウンロード]ボタンを使用してNuGetからインストールします

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSM" readMoreLink="https://docs.fileformat.com/presentation/ppsm/" %}}

Files with PPSM extension represent Macro-enabled Slide Show file format created with Microsoft PowerPoint 2007 or higher. Another similar file format is PPTM which differs in opening with Microsoft PowerPoint in editable format instead of running as Slide Show. When run as slide show, the PPSM file shows the presentation slides with contents intact in the slide show and is in read-only mode by default. PPSM files can still be edited in Microsoft PowerPoint by opening it in PowerPoint.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
