---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PythonでPPSをXPSに変換する
weight: 1760
url: /ja/python-net/conversion/pps-to-xps/ 
keywords: "Convert, PowerPoint, PPS, XPS, Presentation, Python"
description: PPSからXPSPythonへの変換のサンプルコード。 PPSファイルをXPSファイルにバッチ変換するには、PowerPointPythonAPIを使用します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PythonでPPSをXPSに変換する" h2="PPSをXPSに変換するための強力なPowerPointPythonライブラリ"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PythonでPPSをXPSに変換する" %}}

プログラムでPPSファイルをXPSに変換する必要がありますか？ [* Aspose.Slides for Python via .NET *](https://products.aspose.com/slides/ja/python-net/)を使用すると、開発者は数行のPythonコードでPPSをXPS形式に変換できます。

最新のプレゼンテーション処理APIとして、Aspose.SlidesforPythonはPPSからXPSをすばやく作成します。 [ブラウザ](https://products.aspose.app/slides/conversion)でPPSからXPSへの変換の品質をテストします。 Aspose PowerPoint PPTXライブラリを使用すると、PPSファイルを多くの一般的な形式に変換できます。

次のpipコマンドを使用して、[PyPI](https://pypi.org/project/Aspose.Slides/)からライブラリをインストールできます。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="コンソール/ターミナル" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PythonでPPSをXPSとして保存する" %}}

無料アプリを使用して、PPSからXPSへの変換プロセスのデモをご覧ください。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="このサンプルコードは、PPSからXPSへのPython変換を示しています" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pps") as presentation:
    presentation.save("presentation.xps", slides.export.SaveFormat.XPS)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PythonでPPSをXPSに変換する方法" intro="これらは、Pythonを使用してPPSファイルをXPSに変換する手順です。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentationクラスのインスタンスを含むPPSファイルをロードします{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}パラメータとして出力ファイルパスとSaveFormat.XPSを指定しながら、`save`メソッドを呼び出します{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSファイルは指定されたパスに保存されます{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要求" intro="Python変換サンプルソースコードを実行する前に、次の前提条件があることを確認してください。" %}}

- Microsoft WindowsまたはLinuxベースのOS（[詳細](https://docs.aspose.com/slides/python-net/system-requirements/)を参照）。
- Python3.5以降
- プロジェクトで参照されているPython用のAspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="PPSをXPSに変換するための無料アプリ"
  description="[無料のVideoアプリを試してください](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他のサポートされている変換" subTitle="PPSを他の多くのファイル形式に変換することもできます。以下のサポートされている他の変換を参照してください" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-bmp/" name="PPS TO BMP" description="ビットマップ画像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-emf/" name="PPS TO EMF" description="強化されたメタファイル形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-fodp/" name="PPS TO FODP" description="OpenDocumentフラットXMLプレゼンテーション" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-gif/" name="PPS TO GIF" description="グラフィカルな交換形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-html/" name="PPS TO HTML" description="ハイパーテキストマークアップ言語" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-jpg/" name="PPS TO JPG" description="JPEG画像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-odp/" name="PPS TO ODP" description="OpenDocumentプレゼンテーション形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-otp/" name="PPS TO OTP" description="OpenDocument標準フォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-pdf/" name="PPS TO PDF" description="ポータブルドキュメントフォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-png/" name="PPS TO PNG" description="ポータブルネットワークグラフィックス" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-pot/" name="PPS TO POT" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-potm/" name="PPS TO POTM" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-potx/" name="PPS TO POTX" description="MicrosoftPowerPointテンプレートプレゼンテーション" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="マクロ対応のスライドショー" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-pptm/" name="PPS TO PPTM" description="マクロ対応のプレゼンテーションファイル" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-pptx/" name="PPS TO PPTX" description="XMLプレゼンテーション形式を開く" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-svg/" name="PPS TO SVG" description="スケーラブルベクターグラフィックス" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-swf/" name="PPS TO SWF" description="SWFフォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pps-to-tiff/" name="PPS TO TIFF" description="タグ付き画像形式" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
