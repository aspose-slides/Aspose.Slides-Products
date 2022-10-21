---
title: Python を使用して PPTX ファイルを JPG にマージ
url: /ja/python-net/merge/pptx-to-jpg/
keywords: PPTX を JPG に結合、PPTX を JPG に結合、PPTX を JPG に結合、PowerPoint、プレゼンテーション、JPG、Python、Aspose
description: Python で複数の PPTX ファイルをマージします。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PythonでPPTXファイルをJPGにマージします" h2="MicrosoftやOpen Office、Adobe PDFなどのソフトウェアを使用せずに、Microsoft PowerPointおよびOpenOfficeプレゼンテーションファイルを作成、マージ、検査、または変換する機能を備えたアプリケーションの開発に役立つ、高速でクロスプラットフォームのPython API。" >}}

{{% blocks/products/pf/feature-page-section h2="Python で PPTX を JPG にマージする" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ja/python-net/) は、プレゼンテーション ファイルを作成および操作するための強力な Python ライブラリです。さらに、複数の PPTX プレゼンテーションを柔軟に組み合わせることができます。あるプレゼンテーションを別のプレゼンテーションにマージすると、それらのスライドを効果的に 1 つのプレゼンテーションに結合して 1 つのファイルを取得します。 Aspose.Slides では、2 つのプレゼンテーションを異なる方法でマージできます。品質やデータの損失を心配することなく、プレゼンテーションをすべての形状、スタイル、テキスト、書式、コメント、アニメーションなどと結合できます。

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python を使用して PPTX ファイルを JPG にマージします" %}}
PowerPoint プレゼンテーションを結合するには、あるプレゼンテーションから別のプレゼンテーションにスライドを複製する必要があります。

{{% blocks/products/pf/agp/code-block title="複数の PPTX を単一の JPG ファイルにマージするための Python コード" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation1.pptx") as pres1:
    with slides.Presentation("presentation2.pptx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Python API を使用して PPTX を JPG にマージする方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、Python で 2 つの PPTX ファイルをマージし、結果を JPG として保存する手順です。" >}}

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
Python でソース PPTX ファイルを開きます。
```
pres1 = slides.Presentation('pres1.pptx')
pres2 = slides.Presentation('pres2.pptx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) メソッドを使用して PPTX ファイルを結合します。
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションを保存し、結果を単一の JPG ファイルとして取得します。
```
for slide in pres1.slides:
    slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PPTX を他のサポートされている形式にエクスポート" subTitle="PPTX を組み合わせて、他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-ppt/" name="PPTX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-pdf/" name="PPTX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-html/" name="PPTX TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-png/" name="PPTX TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-bmp/" name="PPTX TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-fodp/" name="PPTX TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-gif/" name="PPTX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-odp/" name="PPTX TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-otp/" name="PPTX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-pot/" name="PPTX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-potm/" name="PPTX TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-potx/" name="PPTX TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-pps/" name="PPTX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-ppsm/" name="PPTX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-ppsx/" name="PPTX TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-pptm/" name="PPTX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-svg/" name="PPTX TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-tiff/" name="PPTX TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/merge/pptx-to-xps/" name="PPTX TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}