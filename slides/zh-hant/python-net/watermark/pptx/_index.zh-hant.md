---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 為 PPTX 簡報新增浮水印
url: /zh-hant/python-net/watermark/pptx/
description: 使用 Python 與 Aspose.Slides 為 PPTX 簡報新增文字與圖片浮水印。
keywords: 為 PPTX 新增浮水印, 為 PPTX 新增文字浮水印, 為 PPTX 新增圖片浮水印
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 為 PPTX 簡報新增浮水印" h2="建置使用 Aspose.Slides 為 PPTX 簡報新增文字或圖片浮水印的 Python 應用程式。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 為 PPTX 簡報新增浮水印的範例" variant="code" %}}

透過 [Aspose.Slides for Python via .NET](/slides/zh-hant/python-net/)，無需使用 Microsoft PowerPoint 即可為 PPTX 簡報新增文字或圖片浮水印。浮水印可以標示所有權、將簡報標記為機密或草稿，或提供一致的品牌形象。下列範例會將浮水印放在第一個投影片母片上，因此浮水印會顯示在使用該母片的投影片上。

{{< blocks/products/pf/slides-design-update-10-2026/code title="為 PPTX 簡報新增文字浮水印 - Python" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/code title="為 PPTX 簡報新增圖片浮水印 - Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 為 PPTX 新增浮水印" intro="依照下列步驟為 PPTX 簡報新增文字浮水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 開啟 PPTX 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}從 `masters` 集合取得第一個投影片母片。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}呼叫 `add_auto_shape` 在投影片母片上新增矩形。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}呼叫 `add_text_frame` 新增浮水印文字，然後設定圖形格式並鎖定圖形。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.PPTX` 呼叫 `save`，儲存加上浮水印的簡報。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="以 Aspose.Slides 建置" title="線上為 PPTX 檔案新增浮水印" description="免費的 Aspose.Slides Watermark 應用程式以 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh-hant/python-net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPTX 檔案。" button="開啟 Aspose.Slides Watermark" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何新增浮水印。
- 為 PPTX 檔案新增文字或圖片浮水印。
- 下載加上浮水印的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援浮水印的格式" subTitle="使用 Python，也可以為其他支援的簡報格式新增浮水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
