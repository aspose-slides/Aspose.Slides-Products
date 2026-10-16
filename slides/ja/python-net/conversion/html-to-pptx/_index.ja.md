---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python で HTML を PPTX に変換する
url: /ja/python-net/conversion/html-to-pptx/
keywords: HTML を PPTX に変換、HTML を PPTX に変換、PowerPoint、HTML、PPTX、Python API、Python ライブラリ
description: Python で HTML を PPTX に変換します。 Python ライブラリ API を使用して HTML を PowerPoint に変換する
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python で HTML を PPTX に変換する" h2="Python コードを使用して HTML を PPTX に変換するための強力なクロスプラットフォーム Python API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python で HTML を PPTX に変換する" variant="code" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ja/python-net/) を使用すると、わずか数行のコードで HTML ドキュメントを PowerPoint プレゼンテーションに変換できます。

{{< blocks/products/pf/slides-design-update-10-2026/code title="HTML を PPTX に変換するための Python コード" >}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    with open("page.html", "rb") as htmlStream:
        pres.slides.add_from_html(htmlStream)

    pres.save("MyPresentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides を使用して HTML を PPTX に変換する" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/ja/python-net/) は、PowerPoint プレゼンテーション、PDF、 HTML ドキュメント、およびその他のファイル。 HTML を PPTX に変換すると、基本的に HTML ドキュメントのコンテンツが PowerPoint プレゼンテーションのスライドに移動されます。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PythonでHTMLをPPTXに変換する方法" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ライブラリを参照としてプロジェクトに追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}プレゼンテーション クラスのインスタンスを作成します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX に変換する HTML ドキュメントを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}結果のファイルを PPTX プレゼンテーションとして保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="無料のオンラインコンバーター"
  description="[Python で PPT を HTML に変換する方法](https://products.aspose.com/slides/ja/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="サポートされているその他の PowerPoint 変換" subTitle="他の形式のファイルを PowerPoint に変換することもできます" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
