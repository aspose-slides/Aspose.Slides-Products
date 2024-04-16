---
title: Python で PPS を SVG に変換します
url: /ja/python-java/conversion/pps-to-svg/
keywords: Python プレゼンテーション変換、プレゼンテーションを Python に変換、プレゼンテーション用 Python、Aspose.Slides Python、PPS から SVG への変換、Python プレゼンテーション ライブラリ
description: Python で PPS を SVG に変換します。 Python ライブラリ API を使用して、PPS ファイルを SVG に変換します
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python で PPS を SVG に簡単に変換: Aspose.Slides で解決!" h2="Python を使用してプレゼンテーションに新しい命を吹き込みます。私たちのガイドでは、既存の PowerPoint スライドを魅力的な Python プレゼンテーションに変換する手順を説明します。" >}}

{{% blocks/products/pf/feature-page-section h2="Python で PPS を SVG に変換します" %}}

複雑なプレゼンテーション ソフトウェアと格闘することにうんざりしていませんか? [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/ja/python-java/) 以外に探す必要はありません。この強力なライブラリを使用すると、プレゼンテーションを簡単に作成、編集し、さまざまな形式間で変換できます。 PPS から SVG に切り替える必要がありますか? Aspose.Slides を使用すると、Python コードを数行記述するだけで簡単に実行できます。

**Aspose.Slides for Python via Java** は、最先端のドキュメント処理 API として超高速の変換速度を誇り、PPS プレゼンテーションを SVG 形式に迅速に変換できます。従来のツールの制限を取り除く - Aspose.Slides を使用すると、プレゼンテーションを PPS から SVG だけでなく、他の幅広い形式に変換する柔軟性が得られ、プレゼンテーションをあらゆる状況に完璧に適応させることができます。

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python を使用して PPS を SVG に変換します" %}}
PPS を SVG に変換するには、PPS ファイルからプレゼンテーションを作成し、それを SVG として保存する必要があります。

{{% blocks/products/pf/agp/code-block title="PPS を SVG に変換するための Python チュートリアル" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.pps");

for i in range(pres.getSlides().size()):
    outputStream = open('slide" + i + ".svg', "wb")
    outputStream.write(Slide.writeAsSvgToBytes(pres.getSlides().get_Item(i)))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python のチュートリアル。 Java API 経由で Aspose.Slides for Python を使用して PPS を SVG に変換する方法。" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Java 経由で Aspose.Slides for Python を使用して PPS を SVG に変換するには、パッケージを Python スクリプトにインポートし、Presentation クラスのインスタンスを作成する必要があります。 Presentation クラスは PowerPoint ドキュメントを表し、その要素にアクセスして操作するためのメソッドを提供します。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/ja/python-java/) をインストールします。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ライブラリ参照を Python プロジェクトに追加します (ライブラリをインポートします)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python でソース PPS ファイルを開きます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を SVG ファイルとして保存します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PPS を他のサポートされている形式に変換する" subTitle="PPS を変換して他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-pptx/" name="PPS TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-ppt/" name="PPS TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-pdf/" name="PPS TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-html/" name="PPS TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-png/" name="PPS TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-bmp/" name="PPS TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-jpg/" name="PPS TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-fodp/" name="PPS TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-gif/" name="PPS TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-odp/" name="PPS TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-otp/" name="PPS TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-pot/" name="PPS TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-potm/" name="PPS TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-potx/" name="PPS TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-pptm/" name="PPS TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/pps-to-tiff/" name="PPS TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}