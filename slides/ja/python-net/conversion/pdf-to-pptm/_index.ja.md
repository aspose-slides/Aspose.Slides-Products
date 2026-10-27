---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PythonでPDFをPPTMに変換する
weight: 830
url: /ja/python-net/conversion/pdf-to-pptm/ 
keywords: "Convert, PowerPoint, PDF, PPTM, Presentation, Python"
description: PDFからPPTMPythonへの変換のサンプルコード。 PDFファイルをPPTMファイルにバッチ変換するには、PowerPointPythonAPIを使用します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PythonでPDFをPPTMに変換する" h2="PDFをPPTMに変換するための強力なPowerPointPythonライブラリ"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PythonでPDFをPPTMに変換する" %}}

プログラムでPDFファイルをPPTMに変換する必要がありますか？ [* Aspose.Slides for Python via .NET *](https://products.aspose.com/slides/ja/python-net/)を使用すると、開発者は数行のPythonコードでPDFをPPTM形式に変換できます。

最新のプレゼンテーション処理APIとして、Aspose.SlidesforPythonはPDFからPPTMをすばやく作成します。 [ブラウザ](https://products.aspose.app/slides/conversion)でPDFからPPTMへの変換の品質をテストします。 Aspose PowerPoint PPTXライブラリを使用すると、PDFファイルを多くの一般的な形式に変換できます。

次のpipコマンドを使用して、[PyPI](https://pypi.org/project/Aspose.Slides/)からライブラリをインストールできます。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="コンソール/ターミナル" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PDFをPythonでPPTMとして保存" %}}

無料アプリを使用して、PDFからPPTMへの変換プロセスのデモンストレーションをご覧ください。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="このサンプルコードは、PDFからPPTMへのPython変換を示しています" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("presentation.pptm", slides.export.SaveFormat.PPTM)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PythonでPDFをPPTMに変換する方法" intro="これらは、Pythonを使用してPDFファイルをPPTMに変換する手順です。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentationクラスのインスタンスを含むPDFファイルをロードします{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}パラメータとして出力ファイルパスとSaveFormat.PPTMを指定しながら、`save`メソッドを呼び出します{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PDFファイルは指定されたパスに保存されます{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要求" intro="Python変換サンプルソースコードを実行する前に、次の前提条件があることを確認してください。" %}}

- Microsoft WindowsまたはLinuxベースのOS（[詳細](https://docs.aspose.com/slides/python-net/system-requirements/)を参照）。
- Python3.5以降
- プロジェクトで参照されているPython用のAspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Aspose.Slides で構築" title="PDF を PPTM にオンラインで変換" description="無料の Aspose.Slides Conversion アプリは、上記のコードと同じ API である [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ja/python-net/) で構築されています。アプリを開いて、ご自身の PDF ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Conversion を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" upload="ファイルをドロップまたはアップロード" saveAs="保存形式" convert="変換" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がファイルをどう変換するかを確認できます。
- PDF ファイルをアップロードして、PPTM として保存できます。
- 結果をダウンロードするか、さらにファイルを変換できます。
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他のサポートされている変換" subTitle="PDFを他の多くのファイル形式に変換することもできます。以下のサポートされている他の変換を参照してください" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-bmp/" name="PDF TO BMP" description="ビットマップ画像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-emf/" name="PDF TO EMF" description="強化されたメタファイル形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-fodp/" name="PDF TO FODP" description="OpenDocumentフラットXMLプレゼンテーション" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-gif/" name="PDF TO GIF" description="グラフィカルな交換形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-html/" name="PDF TO HTML" description="ハイパーテキストマークアップ言語" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-jpg/" name="PDF TO JPG" description="JPEG画像" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-odp/" name="PDF TO ODP" description="OpenDocumentプレゼンテーション形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-otp/" name="PDF TO OTP" description="OpenDocument標準フォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-png/" name="PDF TO PNG" description="ポータブルネットワークグラフィックス" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-pot/" name="PDF TO POT" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-potm/" name="PDF TO POTM" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-potx/" name="PDF TO POTX" description="MicrosoftPowerPointテンプレートプレゼンテーション" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-pps/" name="PDF TO PPS" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="マクロ対応のスライドショー" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="XMLプレゼンテーション形式を開く" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-svg/" name="PDF TO SVG" description="スケーラブルベクターグラフィックス" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-swf/" name="PDF TO SWF" description="SWFフォーマット" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="タグ付き画像形式" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-xps/" name="PDF TO XPS" description="XML用紙仕様" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
