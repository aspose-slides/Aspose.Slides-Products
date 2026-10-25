---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 为 PPT 演示文稿添加水印
url: /zh/python-net/watermark/ppt/
description: 使用 Python 和 Aspose.Slides 为 PPT 演示文稿添加文本和图片水印。
keywords: 为 PPT 添加水印, 为 PPT 添加文本水印, 为 PPT 添加图片水印
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 为 PPT 演示文稿添加水印" h2="构建使用 Aspose.Slides 为 PPT 演示文稿添加文本或图片水印的 Python 应用程序。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 为 PPT 演示文稿添加水印的示例" variant="code" %}}

借助 [Aspose.Slides for Python via .NET](/slides/zh/python-net/)，无需使用 Microsoft PowerPoint 即可为 PPT 演示文稿添加文本或图片水印。水印可以标明所有权、将演示文稿标记为机密或草稿，或提供一致的品牌形象。以下示例将水印放在第一个母版幻灯片上，因此水印会显示在使用该母版的幻灯片上。

{{< blocks/products/pf/slides-design-update-10-2026/code title="为 PPT 演示文稿添加文本水印 - Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
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

    presentation.save("watermarked.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="为 PPT 演示文稿添加图片水印 - Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    with open("watermark.png", "rb") as image_stream:
        watermark_image = presentation.images.add_image(image_stream.read())

    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 100, 100, watermark_image.width, watermark_image.height)

    watermark_shape.fill_format.fill_type = slides.FillType.PICTURE
    watermark_shape.fill_format.picture_fill_format.picture.image = watermark_image
    watermark_shape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    presentation.save("watermarked.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 为 PPT 添加水印" intro="按照以下步骤为 PPT 演示文稿添加文本水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 打开 PPT 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}从 `masters` 集合中获取第一个母版幻灯片。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 `add_auto_shape` 在母版幻灯片上添加矩形。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 `add_text_frame` 添加水印文本，然后设置形状格式并锁定形状。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.PPT` 调用 `save`，保存带水印的演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="基于 Aspose.Slides 构建" title="在线为 PPT 文件添加水印" description="免费的 Aspose.Slides Watermark 应用基于 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh/python-net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPT 文件。" button="打开 Aspose.Slides Watermark" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何添加水印。
- 为 PPT 文件添加文本或图片水印。
- 下载带水印的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持水印的格式" subTitle="使用 Python，还可以为其他受支持的演示文稿格式添加水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
