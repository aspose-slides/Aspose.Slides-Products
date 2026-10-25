---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python で PPTX プレゼンテーションに透かしを追加
url: /ja/python-net/watermark/pptx/
description: Python と Aspose.Slides で PPTX プレゼンテーションにテキストと画像の透かしを追加します。
keywords: PPTX に透かしを追加, PPTX にテキストの透かしを追加, PPTX に画像の透かしを追加
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python で PPTX プレゼンテーションに透かしを追加" h2="Aspose.Slides を使用して PPTX プレゼンテーションにテキストまたは画像の透かしを追加する Python アプリケーションを構築します。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python で PPTX プレゼンテーションに透かしを追加する" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/ja/python-net/) を使用すると、Microsoft PowerPoint を使わずに PPTX プレゼンテーションにテキストまたは画像の透かしを追加できます。透かしは、所有者の明示、機密または下書きであることの表示、ブランドの統一に役立ちます。次の例では最初のスライド マスターに透かしを配置するため、そのマスターを使用するスライドに透かしが表示されます。

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX プレゼンテーションへのテキストの透かしの追加 - Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 100, 100, 400, 50)
    watermark_text_frame = watermark_shape.add_text_frame("CONFIDENTIAL")

    watermark_shape.fill_format.fill_type = slides.FillType.NO_FILL
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    watermark_portion = watermark_text_frame.paragraphs[0].portions[0]
    watermark_portion.portion_format.font_height = 32

    watermark_shape.auto_shape_lock.select_locked = True
    watermark_shape.auto_shape_lock.size_locked = True
    watermark_shape.auto_shape_lock.text_locked = True
    watermark_shape.auto_shape_lock.position_locked = True
    watermark_shape.auto_shape_lock.grouping_locked = True

    presentation.save("watermarked.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX プレゼンテーションへの画像の透かしの追加 - Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    with open("watermark.png", "rb") as image_stream:
        watermark_image = presentation.images.add_image(image_stream.read())

    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 100, 100, watermark_image.width, watermark_image.height)

    watermark_shape.fill_format.fill_type = slides.FillType.PICTURE
    watermark_shape.fill_format.picture_fill_format.picture.image = watermark_image
    watermark_shape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    presentation.save("watermarked.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python で PPTX に透かしを追加する方法" intro="次の手順に従って、PPTX プレゼンテーションにテキストの透かしを追加します。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` で PPTX ファイルを開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`masters` コレクションから最初のスライド マスターを取得します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`add_auto_shape` を呼び出してスライド マスターに四角形を追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`add_text_frame` を呼び出して透かしのテキストを追加し、図形の書式を設定してロックします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.PPTX` を指定して `save` を呼び出し、透かし入りのプレゼンテーションを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides で構築" title="PPTX ファイルにオンラインで透かしを追加" description="無料の Aspose.Slides Watermark アプリは、上記のコードと同じ API である [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ja/python-net/) で構築されています。アプリを開いて、ご自身の PPTX ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Watermark を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides が透かしをどう追加するかを確認できます。
- PPTX ファイルにテキストまたは画像の透かしを追加できます。
- 透かし入りのファイルをダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="透かしに対応したその他の形式" subTitle="Python では、サポートされている他のプレゼンテーション形式にも透かしを追加できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
