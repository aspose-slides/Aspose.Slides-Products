---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++アプリケーションを介してODPをPPSXに変換する
weight: 6290
url: /ja/cpp/conversion/odp-to-ppsx/ 
description: ODPドキュメントからPPSX形式へのサンプルC++変換コード。任意のC++アプリケーション内でのバッチODPからPPSXへの変換にサンプルコードを使用します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++を介してODPをPPSXに変換します" h2="Microsoft PowerPointをインストールせずに、C++ライブラリを使用した高性能ODPからPPSXへの変換。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++を使用してODPをPPSXに変換する方法" %}}

ODPをPPSXに変換するには、
 [Aspose.Slides for C ++](https://products.aspose.com/slides/cpp)
 機能が豊富で強力で使いやすいC++プラットフォーム用のドキュメント操作および変換APIであるAPI。最新バージョンを直接ダウンロードできます。開くだけです。
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 パッケージマネージャー、検索
 Aspose.Slides.Cpp
 とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="指示" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODPからPPSXC++への変換ソースコード" >}}
```cs
// Load the ODP.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.odp");
// Save in PPSX format.
prs->Save(u"convertedFile.ppsx", Aspose::Slides::Export::SaveFormat::Ppsx);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++を介してODPをPPSXに変換する手順" intro="C ++開発者は、わずか数行のコードでODPファイルをPPSXに簡単に変換できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}C++プレゼンテーションオブジェクトのAspose.Slidesを使用してODPファイルをロードします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save（）メソッドを呼び出します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}出力ファイルパスを（PPSX）ファイル拡張子で渡します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSXファイルは指定されたパスに保存されます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}互換性のあるプログラムでPPSXファイルを開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要求" intro="C ++変換のサンプルコードを実行する前に、次の前提条件があることを確認してください。" %}}

- MicrosoftWindowsまたはWindows32ビット、Windows 64ビット、Linux64ビット用のC++ランタイム環境と互換性のあるOS。
- プロジェクトで参照されているC++DLLのAspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="ODPをPPSXに変換するための無料アプリ"
  description="[無料のVideoアプリを試してください](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他のサポートされている変換" subTitle="また、ODPを、以下にリストされているいくつかを含む他の多くのファイル形式に変換することもできます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-bmp/" name="ODP TO BMP" description="ビットマップ画像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-emf/" name="ODP TO EMF" description="強化されたメタファイル形式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-gif/" name="ODP TO GIF" description="グラフィカルな交換形式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-html/" name="ODP TO HTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="JPEG画像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-otp/" name="ODP TO OTP" description="OpenDocument標準フォーマット" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pdf/" name="ODP TO PDF" description="ポータブルドキュメントフォーマット" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-png/" name="ODP TO PNG" description="ポータブルネットワークグラフィックス" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pot/" name="ODP TO POT" description="MicrosoftPowerPointテンプレートファイル" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-potm/" name="ODP TO POTM" description="MicrosoftPowerPointテンプレートファイル" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-potx/" name="ODP TO POTX" description="MicrosoftPowerPointテンプレートプレゼンテーション" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pps/" name="ODP TO PPS" description="PowerPointのスライドショー" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="マクロ対応のスライドショー" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pptm/" name="ODP TO PPTM" description="マクロ対応のプレゼンテーションファイル" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pptx/" name="ODP TO PPTX" description="XMLプレゼンテーション形式を開く" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-svg/" name="ODP TO SVG" description="スケーラブルベクターグラフィックス" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-tiff/" name="ODP TO TIFF" description="タグ付き画像形式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-xml/" name="ODP TO XML" description="拡張マークアップ言語" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-xps/" name="ODP TO XPS" description="XML用紙仕様" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
