---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python で PDF を編集する
url: /ja/python-net/editor/pdf/
keywords: PDF の編集、PDF、Python API、Python ライブラリ
description: Python で PDF を編集します。 Python ライブラリ API を使用して PDF ドキュメントを編集する
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python で PDF を編集する" h2="Python コードを使用して PDF を編集するための高速でクロスプラットフォームの Python ライブラリ" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python で PDF を編集する" variant="code" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ja/python-net/) を使用すると、ほんの数行のテキストで PDF ドキュメントに新しいテキスト行を追加できます。コード行。

{{< blocks/products/pf/slides-design-update-10-2026/code title="PDF を編集するための Python コード" >}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    pres.slides.add_from_pdf("document.pdf")

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("document.pdf", slides.export.SaveFormat.PDF)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides を使用して PDF を編集" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ja/python-net/) は、プレゼンテーション、PDF ドキュメント、およびその他のファイルの操作と編集に使用される強力な Python ライブラリです。 .新しいテキスト行を追加して PDF ドキュメントを編集できます。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PythonでPDFを編集する方法" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ライブラリを参照としてプロジェクトに追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}プレゼンテーション クラスのインスタンスを作成します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}編集する PDF ドキュメントを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}新しいテキスト行を追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}変更した PDF ファイルを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="他のファイルを編集する" subTitle="他の形式のファイルを編集することもできます" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
