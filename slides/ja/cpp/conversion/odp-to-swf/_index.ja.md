---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++アプリケーションを介してODPをSWFに変換する
url: /ja/cpp/conversion/odp-to-swf/ 
description: ODPドキュメントからSWF形式へのサンプルC++変換コード。任意のC++アプリケーション内でのバッチODPからSWFへの変換にサンプルコードを使用します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++を介してODPをSWFに変換します" h2="Microsoft PowerPointをインストールせずに、C++ライブラリを使用した高性能ODPからSWFへの変換。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++を使用してODPをSWFに変換する方法" %}}

ODPをSWFに変換するには、機能が豊富で強力な<a href="https://products.aspose.com/slides/cpp"> Aspose.Slides for C ++</a>APIを使用します。 C++プラットフォーム用の使いやすいドキュメント操作および変換API。最新バージョンを直接ダウンロードできます。<ahref="https://www.nuget.org/packages/aspose.slides"> NuGet </a>パッケージマネージャーを開き、<b>Aspose.Slides.Cppを検索してください。 </b>とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="指示" >}}
```cs

PM> Install-Package Aspose.SLIDES.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODPからSWFへのC++変換ソースコード" >}}
```cs
// Load the ODP.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.odp");
// Save in SWF format.
prs->Save(u"convertedFile.swf", Aspose::Slides::Export::SaveFormat::Swf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++を介してODPをSWFに変換する手順" intro="Aspose.SLIDES APIを使用すると、開発者は数行のコードでODPファイルをSWFに簡単に変換できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}C++プレゼンテーションオブジェクトのAspose.Slidesを使用してODPファイルをロードします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
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
  title="ODPをSWFに変換するための無料アプリ"
  description="[無料のVideoアプリを試してください](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他のサポートされている変換" subTitle="また、ODPを、以下にリストされているいくつかを含む他の多くのファイル形式に変換することもできます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-bmp/" name="ODP TO BMP" description="Bitmap Image" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-emf/" name="ODP TO EMF" description="Enhanced Metafile Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-gif/" name="ODP TO GIF" description="Graphical Interchange Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-html/" name="ODP TO HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="JPEG Image" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-otp/" name="ODP TO OTP" description="OpenDocument Standard Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pdf/" name="ODP TO PDF" description="Portable Document Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-png/" name="ODP TO PNG" description="Portable Network Graphics" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pot/" name="ODP TO POT" description="Microsoft PowerPoint Template Files" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-potm/" name="ODP TO POTM" description="Microsoft PowerPoint Template File" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-potx/" name="ODP TO POTX" description="Microsoft PowerPoint Template Presentation" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pps/" name="ODP TO PPS" description="PowerPoint Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Macro-enabled Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="PowerPoint Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Macro-enabled Presentation File" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Open XML presentation Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-svg/" name="ODP TO SVG" description="Scalable Vector Graphics" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Tagged Image Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-xml/" name="ODP TO XML" description="Extensible Markup Language" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-xps/" name="ODP TO XPS" description="XML用紙仕様" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
