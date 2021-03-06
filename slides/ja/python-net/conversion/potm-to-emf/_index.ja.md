---
title: PythonでPOTMをEMFに変換する
weight: 1120
url: /ja/python-net/conversion/potm-to-emf/ 
keywords: "Convert, PowerPoint, POTM, EMF, Presentation, Python"
description: POTMからEMFPythonへの変換のサンプルコード。 PowerPoint Python APIを使用して、POTMファイルをEMFファイルにバッチ変換します。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="PythonでPOTMをEMFに変換する" h2="POTMをEMFに変換するための強力なPowerPointPythonライブラリ" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="PythonでPOTMをEMFに変換する" %}}

プログラムでPOTMファイルをEMFに変換する必要がありますか？ [* Aspose.Slides for Python via .NET *]（https://products.aspose.com/slides/ja/python-net/）を使用すると、開発者は数行のPythonコードでPOTMをEMF形式に変換できます。

最新のプレゼンテーション処理APIとして、Aspose.SlidesforPythonはPOTMからEMFをすばやく作成します。 [ブラウザ]（https://products.aspose.app/slides/conversion）でPOTMからEMFへの変換の品質をテストします。 Aspose PowerPoint PPTXライブラリを使用すると、POTMファイルを多くの一般的な形式に変換できます。

次のpipコマンドを使用して、[PyPI]（https://pypi.org/project/Aspose.Slides/）からライブラリをインストールできます。

{{% blocks/products/pf/agp/code-block title="コンソール/ターミナル" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="PythonでPOTMをEMFに変換する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、Pythonを使用してPOTMファイルをEMFに変換する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentationクラスのインスタンスを含むPOTMファイルをロードします
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
パラメータとして出力ファイルパスとSaveFormat.EMFを指定しながら、`save`メソッドを呼び出します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
POTMファイルは指定されたパスに保存されます
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Python変換サンプルソースコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

-Microsoft WindowsまたはLinuxベースのOS（[詳細]（https://docs.aspose.com/slides/python-net/system-requirements/）を参照）。
-Python3.5以降
-プロジェクトで参照されているPython用のAspose.Slides。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="このサンプルコードは、POTMからEMFへのPython変換を示しています" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.potm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.emf".format(str(slide.slide_number)), drawing.imaging.ImageFormat.emf)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="PythonでPOTMをEMFとして保存" %}}
無料アプリを使用して、POTMからEMFへの変換プロセスのデモンストレーションをご覧ください。 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="POTMをEMFに変換するための無料アプリ" 
        sectionDescription="[無料のVideoアプリを試してください](https://products.aspose.app/slides/video/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="POTMを他の多くのファイル形式に変換することもできます。以下のサポートされている他の変換を参照してください" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-bmp/" name="POTM TO BMP" description="ビットマップ画像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-fodp/" name="POTM TO FODP" description="OpenDocumentフラットXMLプレゼンテーション" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-gif/" name="POTM TO GIF" description="グラフィカルな交換形式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-html/" name="POTM TO HTML" description="ハイパーテキストマークアップ言語" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-jpg/" name="POTM TO JPG" description="JPEG画像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-odp/" name="POTM TO ODP" description="OpenDocumentプレゼンテーション形式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-otp/" name="POTM TO OTP" description="OpenDocument標準フォーマット" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-pdf/" name="POTM TO PDF" description="ポータブルドキュメントフォーマット" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-png/" name="POTM TO PNG" description="ポータブルネットワークグラフィックス" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-pot/" name="POTM TO POT" description="MicrosoftPowerPointテンプレートファイル" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-potx/" name="POTM TO POTX" description="MicrosoftPowerPointテンプレートプレゼンテーション" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-pps/" name="POTM TO PPS" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="マクロ対応のスライドショー" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="PowerPointのスライドショー" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-pptm/" name="POTM TO PPTM" description="マクロ対応のプレゼンテーションファイル" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-pptx/" name="POTM TO PPTX" description="XMLプレゼンテーション形式を開く" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-svg/" name="POTM TO SVG" description="スケーラブルベクターグラフィックス" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-swf/" name="POTM TO SWF" description="SWFフォーマット" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-tiff/" name="POTM TO TIFF" description="タグ付き画像形式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/conversion/potm-to-xps/" name="POTM TO XPS" description="XML用紙仕様" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}