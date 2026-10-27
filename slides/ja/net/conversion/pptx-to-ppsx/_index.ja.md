---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C＃を介してPPTXをPPSXに変換します
weight: 2180
url: /ja/net/conversion/pptx-to-ppsx/ 
description: PPTXからPPSXC＃への変換のサンプルコード。 VB.NET、Asp.NET、または任意の.NETベースのアプリケーション内でのバッチPPTXファイルからPPSXへの変換にはAPIサンプルコードを使用します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C＃を介してPPTXをPPSXに変換します" h2="PowerPoint®PPTXファイルを.NETFramework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォーム上のPPSXにエクスポートします"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C＃を使用してPPTXをPPSXに変換する方法" %}}

PPTXをPPSXに変換するには、
 [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net)
 機能が豊富で強力で使いやすいC＃プラットフォーム用のドキュメント操作および変換APIであるAPI。開ける
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 パッケージマネージャー、検索
 Aspose.Slides
 とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="パッケージマネージャーコンソールコマンド" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="このサンプルコードは、PPTXからPPSXへのC＃変換を示しています" >}}
```cs
// instantiate a Presentation object that represents a PPTX file
var presentation = new Presentation("template.pptx");
// save the presentation as PPSX
presentation.Save("output.ppsx", SaveFormat.Ppsx); 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C＃を介してPPTXをPPSXに変換する手順" intro=".NET開発者は、わずか数行のコードでPPTXファイルをPPSXに簡単にロードおよび変換できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentationクラスのインスタンスを含むPPTXファイルをロードします{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}出力ファイルのパスとSaveFormat.Ppsxをパラメーターとして指定しながら、Saveメソッドを呼び出します{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSXファイルは指定されたパスに保存されます{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要求" intro=".NET変換サンプルソースコードを実行する前に、次の前提条件があることを確認してください。" %}}

- Microsoft Windows、または.NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームと互換性のあるOS。
- MicrosoftVisualStudioのような開発環境。
- プロジェクトで参照されているAspose.Slidesfor.NETDLL。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Aspose.Slides で構築" title="PPTX を PPSX にオンラインで変換" description="無料の Aspose.Slides Conversion アプリは、上記のコードと同じ API である [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net/) で構築されています。アプリを開いて、ご自身の PPTX ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Conversion を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" upload="ファイルをドロップまたはアップロード" saveAs="保存形式" convert="変換" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がファイルをどう変換するかを確認できます。
- PPTX ファイルをアップロードして、PPSX として保存できます。
- 結果をダウンロードするか、さらにファイルを変換できます。
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他のサポートされている変換" subTitle="PPTXを、以下にリストされているいくつかを含む他の多くのファイル形式に変換することもできます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="ビットマップ画像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-emf/" name="PPTX TO EMF" description="強化されたメタファイル形式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-gif/" name="PPTX TO GIF" description="グラフィカルな交換形式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-html/" name="PPTX TO HTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="JPEG画像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocumentプレゼンテーション形式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument標準フォーマット" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="ポータブルドキュメントフォーマット" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-png/" name="PPTX TO PNG" description="ポータブルネットワークグラフィックス" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-pot/" name="PPTX TO POT" description="MicrosoftPowerPointテンプレートファイル" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-potm/" name="PPTX TO POTM" description="MicrosoftPowerPointテンプレートファイル" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-potx/" name="PPTX TO POTX" description="MicrosoftPowerPointテンプレートプレゼンテーション" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-pps/" name="PPTX TO PPS" description="PowerPointのスライドショー" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="マクロ対応のスライドショー" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="マクロ対応のプレゼンテーションファイル" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-svg/" name="PPTX TO SVG" description="スケーラブルベクターグラフィックス" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-swf/" name="PPTX TO SWF" description="SWFフォーマット" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="タグ付き画像形式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/net/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML用紙仕様" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
