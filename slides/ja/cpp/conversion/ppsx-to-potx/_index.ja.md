---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++アプリケーションを介してPPSXをPOTXに変換する
weight: 7900
url: /ja/cpp/conversion/ppsx-to-potx/ 
description: PPSXドキュメントからPOTX形式へのサンプルC++変換コード。任意のC++アプリケーション内でのバッチPPSXからPOTXへの変換にサンプルコードを使用します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++を介してPPSXをPOTXに変換します" h2="Microsoft PowerPointをインストールせずに、C++ライブラリを使用した高性能PPSXからPOTXへの変換。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++を使用してPPSXをPOTXに変換する方法" %}}

PPSXをPOTXに変換するには、
 [Aspose.Slides for C ++](https://products.aspose.com/slides/ja/cpp)
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSXからPOTXC++への変換ソースコード" >}}
```cs
// Load the PPSX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.ppsx");
// Save in POTX format.
prs->Save(u"convertedFile.potx", Aspose::Slides::Export::SaveFormat::Potx);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++を介してPPSXをPOTXに変換する手順" intro="C ++開発者は、わずか数行のコードでPPSXファイルをPOTXに簡単に変換できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}C++プレゼンテーションオブジェクトのAspose.Slidesを使用してPPSXファイルをロードします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save（）メソッドを呼び出します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}出力ファイルパスを（POTX）ファイル拡張子で渡します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}POTXファイルは指定されたパスに保存されます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}互換性のあるプログラムでPOTXファイルを開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要求" intro="C ++変換のサンプルコードを実行する前に、次の前提条件があることを確認してください。" %}}

- MicrosoftWindowsまたはWindows32ビット、Windows 64ビット、Linux64ビット用のC++ランタイム環境と互換性のあるOS。
- プロジェクトで参照されているC++DLLのAspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="PPSXをPOTXに変換するための無料アプリ"
  description="[無料のEditorアプリを試してください](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他のサポートされている変換" subTitle="PPSXを、以下にリストされているいくつかを含む他の多くのファイル形式に変換することもできます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="ビットマップ画像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="強化されたメタファイル形式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="グラフィカルな交換形式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-html/" name="PPSX TO HTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="JPEG画像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocumentプレゼンテーション形式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument標準フォーマット" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="ポータブルドキュメントフォーマット" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-png/" name="PPSX TO PNG" description="ポータブルネットワークグラフィックス" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-pot/" name="PPSX TO POT" description="MicrosoftPowerPointテンプレートファイル" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="MicrosoftPowerPointテンプレートファイル" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="PowerPointのスライドショー" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="マクロ対応のスライドショー" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="マクロ対応のプレゼンテーションファイル" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="XMLプレゼンテーション形式を開く" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="スケーラブルベクターグラフィックス" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="タグ付き画像形式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-xml/" name="PPSX TO XML" description="拡張マークアップ言語" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="XML用紙仕様" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
