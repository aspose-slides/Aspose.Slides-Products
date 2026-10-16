---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++アプリケーションを介してPPSXをSWFに変換する
url: /ja/cpp/conversion/ppsx-to-swf/ 
description: PPSXドキュメントからSWF形式へのサンプルC++変換コード。任意のC++アプリケーション内でのバッチPPSXからSWFへの変換にサンプルコードを使用します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++を介してPPSXをSWFに変換します" h2="Microsoft PowerPointをインストールせずに、C++ライブラリを使用した高性能PPSXからSWFへの変換。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++を使用してPPSXをSWFに変換する方法" %}}

PPSXをSWFに変換するには、機能が豊富で強力な<a href="https://products.aspose.com/slides/ja/cpp"> Aspose.Slides for C ++</a>APIを使用します。 C++プラットフォーム用の使いやすいドキュメント操作および変換API。最新バージョンを直接ダウンロードできます。<ahref="https://www.nuget.org/packages/aspose.slides"> NuGet </a>パッケージマネージャーを開き、<b>Aspose.Slides.Cppを検索してください。 </b>とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="指示" >}}
```cs

PM> Install-Package Aspose.SLIDES.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSXからSWFC++への変換ソースコード" >}}
```cs
// Load the PPSX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.ppsx");
// Save in SWF format.
prs->Save(u"convertedFile.swf", Aspose::Slides::Export::SaveFormat::Swf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++を介してPPSXをSWFに変換する手順" intro="Aspose.SLIDES APIを使用すると、開発者は数行のコードでPPSXファイルをSWFに簡単に変換できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}C++プレゼンテーションオブジェクトのAspose.Slidesを使用してPPSXファイルをロードします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save（）メソッドを呼び出します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}出力ファイルパスを（SWF）ファイル拡張子で渡します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}SWFファイルは指定されたパスに保存されます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}互換性のあるプログラムでSWFファイルを開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要求" intro="Aspose.SLIDES for C ++は、すべての主要なプラットフォームとオペレーティングシステムでサポートされています。次の前提条件があることを確認してください。" %}}

- MicrosoftWindowsまたはWindows32ビット、Windows 64ビット、Linux64ビット用のC++ランタイム環境と互換性のあるOS。
- プロジェクトで参照されているC++DLLのAspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="PPSXをSWFに変換するための無料アプリ"
  description="[無料のText To Gifアプリを試してください](https://products.aspose.app/slides/text-to-gif/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他のサポートされている変換" subTitle="PPSXを、以下にリストされているいくつかを含む他の多くのファイル形式に変換することもできます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Bitmap Image" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="Enhanced Metafile Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Graphical Interchange Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="JPEG Image" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument Presentation Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument Standard Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Portable Document Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Portable Network Graphics" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Microsoft PowerPoint Template Files" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Microsoft PowerPoint Template File" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Microsoft PowerPoint Template Presentation" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="PowerPoint Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Macro-enabled Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Macro-enabled Presentation File" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Open XML presentation Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Scalable Vector Graphics" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Tagged Image Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-xml/" name="PPSX TO XML" description="Extensible Markup Language" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/cpp/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="XML用紙仕様" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
