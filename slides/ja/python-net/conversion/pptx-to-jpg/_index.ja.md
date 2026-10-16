---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PythonでPPTXをJPGに変換する
weight: 2700
url: /ja/python-net/conversion/pptx-to-jpg/ 
keywords: "Convert, PowerPoint, PPTX, JPG, Presentation, Python"
description: PPTXからJPGPythonへの変換のサンプルコード。 PowerPoint Python APIを使用して、PPTXファイルをJPGファイルにバッチ変換します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PythonでPPTXをJPGに変換する" h2="PPTXをJPGに変換するための強力なPowerPointPythonライブラリ"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PythonでPPTXをJPGに変換する" %}}

プログラムでPPTXファイルをJPGに変換する必要がありますか？ [* Aspose.Slides for Python via .NET *](https://products.aspose.com/slides/ja/python-net/)を使用すると、開発者は数行のPythonコードでPPTXをJPG形式に変換できます。

最新のプレゼンテーション処理APIとして、Aspose.SlidesforPythonはPPTXからJPGをすばやく作成します。 [ブラウザ](https://products.aspose.app/slides/conversion/ppt-to-jpg)でPPTXからJPGへの変換の品質をテストします。 Aspose PowerPoint PPTXライブラリを使用すると、PPTXファイルを多くの一般的な形式に変換できます。

次のpipコマンドを使用して、[PyPI](https://pypi.org/project/Aspose.Slides/)からライブラリをインストールできます。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="コンソール/ターミナル" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PythonでPPTXをJPGとして保存" %}}

無料アプリを使用して、PPTXからJPGへの変換プロセスのデモをご覧ください。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="このサンプルコードは、PPTXからJPGへのPython変換を示しています" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PythonでPPTXをJPGに変換する方法" intro="これらは、Pythonを使用してPPTXファイルをJPGに変換する手順です。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentationクラスのインスタンスを含むPPTXファイルをロードします{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}パラメータとして出力ファイルパスとSaveFormat.JPGを指定しながら、`save`メソッドを呼び出します{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTXファイルは指定されたパスに保存されます{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要求" intro="Python変換サンプルソースコードを実行する前に、次の前提条件があることを確認してください。" %}}

- Microsoft WindowsまたはLinuxベースのOS（[詳細](https://docs.aspose.com/slides/python-net/system-requirements/)を参照）。
- Python3.5以降
- プロジェクトで参照されているPython用のAspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="pptx-to-jpg"
  title="PPTXをJPGに変換するための無料アプリ"
  description="[PPTをJPGに変換するために無料のアプリを試してみてください](https://products.aspose.app/slides/conversion/ppt-to-jpg)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他のサポートされている変換" subTitle="PPTXを他の多くのファイル形式に変換することもできます。以下のサポートされている他の変換を参照してください" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="ビットマップ画像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-emf/" name="PPTX TO EMF" description="強化されたメタファイル形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-fodp/" name="PPTX TO FODP" description="OpenDocumentフラットXMLプレゼンテーション" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-gif/" name="PPTX TO GIF" description="グラフィカルな交換形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-html/" name="PPTX TO HTML" description="ハイパーテキストマークアップ言語" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocumentプレゼンテーション形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument標準フォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="ポータブルドキュメントフォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-png/" name="PPTX TO PNG" description="ポータブルネットワークグラフィックス" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-pot/" name="PPTX TO POT" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-potm/" name="PPTX TO POTM" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-potx/" name="PPTX TO POTX" description="MicrosoftPowerPointテンプレートプレゼンテーション" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-pps/" name="PPTX TO PPS" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="マクロ対応のスライドショー" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="マクロ対応のプレゼンテーションファイル" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-svg/" name="PPTX TO SVG" description="スケーラブルベクターグラフィックス" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-swf/" name="PPTX TO SWF" description="SWFフォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="タグ付き画像形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML用紙仕様" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
