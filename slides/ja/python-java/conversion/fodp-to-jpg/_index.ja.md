---
title: Python で FODP を JPG に変換します
url: /ja/python-java/conversion/fodp-to-jpg/
keywords: Python プレゼンテーション変換、プレゼンテーションを Python に変換、プレゼンテーション用 Python、Aspose.Slides Python、FODP から JPG への変換、Python プレゼンテーション ライブラリ
description: Python で FODP を JPG に変換します。 Python ライブラリ API を使用して、FODP ファイルを JPG に変換します
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python で FODP を JPG に簡単に変換: Aspose.Slides で解決!" h2="Python を使用してプレゼンテーションに新しい命を吹き込みます。私たちのガイドでは、既存の PowerPoint スライドを魅力的な Python プレゼンテーションに変換する手順を説明します。" >}}

{{% blocks/products/pf/feature-page-section h2="Python で FODP を JPG に変換します" %}}

複雑なプレゼンテーション ソフトウェアと格闘することにうんざりしていませんか? [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/ja/python-java/) 以外に探す必要はありません。この強力なライブラリを使用すると、プレゼンテーションを簡単に作成、編集し、さまざまな形式間で変換できます。 FODP から JPG に切り替える必要がありますか? Aspose.Slides を使用すると、Python コードを数行記述するだけで簡単に実行できます。

**Aspose.Slides for Python via Java** は、最先端のドキュメント処理 API として超高速の変換速度を誇り、FODP プレゼンテーションを JPG 形式に迅速に変換できます。従来のツールの制限を取り除く - Aspose.Slides を使用すると、プレゼンテーションを FODP から JPG だけでなく、他の幅広い形式に変換する柔軟性が得られ、プレゼンテーションをあらゆる状況に完璧に適応させることができます。

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python を使用して FODP を JPG に変換します" %}}
FODP を JPG に変換するには、FODP ファイルからプレゼンテーションを作成し、それを JPG として保存する必要があります。

{{% blocks/products/pf/agp/code-block title="FODP を JPG に変換するための Python チュートリアル" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.fodp");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "JPEG", File("slide" + str(i) + ".jpg"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python のチュートリアル。 Java API 経由で Aspose.Slides for Python を使用して FODP を JPG に変換する方法。" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Java 経由で Aspose.Slides for Python を使用して FODP を JPG に変換するには、パッケージを Python スクリプトにインポートし、Presentation クラスのインスタンスを作成する必要があります。 Presentation クラスは PowerPoint ドキュメントを表し、その要素にアクセスして操作するためのメソッドを提供します。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/ja/python-java/) をインストールします。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ライブラリ参照を Python プロジェクトに追加します (ライブラリをインポートします)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python でソース FODP ファイルを開きます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を JPG ファイルとして保存します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="FODP を他のサポートされている形式に変換する" subTitle="FODP を変換して他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-pdf/" name="FODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-png/" name="FODP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-bmp/" name="FODP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-potm/" name="FODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-svg/" name="FODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}