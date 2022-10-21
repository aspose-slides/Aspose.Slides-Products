---
title: Python を使用して POT ファイルを PPSM にマージ
url: /ja/python-net/merge/pot-to-ppsm/
keywords: POT を PPSM に結合、POT を PPSM に結合、POT を PPSM に結合、PowerPoint、プレゼンテーション、PPSM、Python、Aspose
description: Python で複数の POT ファイルをマージします。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PythonでPOTファイルをPPSMにマージします" h2="MicrosoftやOpen Office、Adobe PDFなどのソフトウェアを使用せずに、Microsoft PowerPointおよびOpenOfficeプレゼンテーションファイルを作成、マージ、検査、または変換する機能を備えたアプリケーションの開発に役立つ、高速でクロスプラットフォームのPython API。" >}}

{{% blocks/products/pf/feature-page-section h2="Python で POT を PPSM にマージする" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ja/python-net/) は、プレゼンテーション ファイルを作成および操作するための強力な Python ライブラリです。さらに、複数の POT プレゼンテーションを柔軟に組み合わせることができます。あるプレゼンテーションを別のプレゼンテーションにマージすると、それらのスライドを効果的に 1 つのプレゼンテーションに結合して 1 つのファイルを取得します。 Aspose.Slides では、2 つのプレゼンテーションを異なる方法でマージできます。品質やデータの損失を心配することなく、プレゼンテーションをすべての形状、スタイル、テキスト、書式、コメント、アニメーションなどと結合できます。

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python を使用して POT ファイルを PPSM にマージします" %}}
PowerPoint プレゼンテーションを結合するには、あるプレゼンテーションから別のプレゼンテーションにスライドを複製する必要があります。

{{% blocks/products/pf/agp/code-block title="複数の POT を単一の PPSM ファイルにマージするための Python コード" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.pot") as pres1:
    with slides.Presentation("presentation2.pot") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.ppsm", slides.export.SaveFormat.PPSM)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Python API を使用して POT を PPSM にマージする方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、Python で 2 つの POT ファイルをマージし、結果を PPSM として保存する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ja/python-net/) をインストールします。
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python プロジェクトにライブラリ参照を追加 (ライブラリをインポート) します。
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Python でソース POT ファイルを開きます。
```
pres1 = slides.Presentation('pres1.pot')
pres2 = slides.Presentation('pres2.pot')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) メソッドを使用して POT ファイルを結合します。
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションを保存し、結果を単一の PPSM ファイルとして取得します。
```
pres1.save("presentation.ppsm", slides.export.SaveFormat.PPSM)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="POT を他のサポートされている形式にエクスポート" subTitle="POT を組み合わせて、他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-pptx/" name="POT TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-ppt/" name="POT TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-pdf/" name="POT TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-html/" name="POT TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-png/" name="POT TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-bmp/" name="POT TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-jpg/" name="POT TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-fodp/" name="POT TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-gif/" name="POT TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-odp/" name="POT TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-otp/" name="POT TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-potm/" name="POT TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-potx/" name="POT TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-pps/" name="POT TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-ppsx/" name="POT TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-pptm/" name="POT TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-svg/" name="POT TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-tiff/" name="POT TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pot-to-xps/" name="POT TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}