---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python で PNG を SVG に変換する
url: /ja/python-net/conversion/png-to-svg/
keywords: PNG から SVG へ、PNG から SVG への変換、Python API、Python ライブラリ、PNG、SVG
description: Python で PNG を SVG に変換します。 Python ライブラリ API を使用して PNG ファイルを SVG ファイルに変換します
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python で PNG を SVG に変換する" h2="MicrosoftやOpen Office、Adobe PDFなどのソフトウェアを使用せずに、Microsoft PowerPointおよびOpenOfficeプレゼンテーションファイルを作成、マージ、検査、または変換する機能を備えたアプリケーションの開発に役立つ、高速でクロスプラットフォームのPythonライブラリ。" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python を使用して PNG を SVG に変換します" variant="code" %}}

PNG を SVG に変換するには、PNG ファイルからプレゼンテーションを作成し、SVG として保存する必要があります。

{{< blocks/products/pf/slides-design-update-10-2026/code title="PNG を SVG に変換する Python コード" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for index in range(pres.slides.length):
        slide = pres.slides[index]

        with open("slide-{index}.svg".format(index = index), "wb") as file:
            slide.write_as_svg(file)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python で PNG を SVG に変換する" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ja/python-net/) は、プレゼンテーション ファイルを作成および操作するための強力な Python ライブラリです。さらに、PNG を SVG に柔軟に変換する方法を提供します。 .NET 経由で **Aspose.Slides for Python** を使用すると、開発者やアプリケーションは、わずか数行の Python コードで PNG ファイルを SVG ファイルに変換できます。

最新のドキュメント処理 API である Aspose.Slides for Python は、PNG ファイルを SVG ファイル フォーマットにすばやくエクスポートします。 Aspose PowerPoint ライブラリを使用すると、PNG を SVG やその他の多くのファイル形式に変換できます

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Aspose.Slides for Python API を使用して PNG を SVG に変換する方法" intro="これらは、Python で PNG を SVG に変換する手順です。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ja/python-net/) をインストールします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Python プロジェクトにライブラリ参照を追加 (ライブラリをインポート) します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Python でソース PNG ファイルを開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}結果を SVG ファイルとして保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="無料のオンラインコンバーター"
  description="[Python で PPT を HTML に変換する方法](https://products.aspose.com/slides/ja/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="PNG を他のサポートされている形式に変換する" subTitle="PNG を変換して、他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
