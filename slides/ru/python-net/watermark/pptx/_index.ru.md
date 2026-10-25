---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Добавление водяных знаков в презентации PPTX на Python
url: /ru/python-net/watermark/pptx/
description: Добавляйте текстовые и графические водяные знаки в презентации PPTX с помощью Python и Aspose.Slides.
keywords: добавить водяной знак в PPTX, добавить текстовый водяной знак в PPTX, добавить графический водяной знак в PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Добавление водяных знаков в презентации PPTX на Python" h2="Создавайте приложения на Python, которые с помощью Aspose.Slides добавляют текстовые или графические водяные знаки в презентации PPTX." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Добавление водяного знака в презентацию PPTX на Python" variant="code" %}}

С помощью [Aspose.Slides for Python via .NET](/slides/ru/python-net/) можно добавить текстовый или графический водяной знак в презентацию PPTX без Microsoft PowerPoint. Водяной знак может указывать владельца, помечать презентацию как конфиденциальную или черновую либо поддерживать единый фирменный стиль. В примерах ниже водяной знак размещается на первом образце слайдов, поэтому он отображается на всех слайдах, которые используют этот образец.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Добавление текстового водяного знака в презентацию PPTX — Python" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/code title="Добавление графического водяного знака в презентацию PPTX — Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как добавить водяной знак в PPTX на Python" intro="Выполните следующие шаги, чтобы добавить текстовый водяной знак в презентацию PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте файл PPTX с помощью `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Получите первый образец слайдов из коллекции `masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите `add_auto_shape`, чтобы добавить прямоугольник на образец слайдов.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите `add_text_frame`, чтобы добавить текст водяного знака, затем отформатируйте и заблокируйте фигуру.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите `save` с `SaveFormat.PPTX`, чтобы сохранить презентацию с водяным знаком.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Создано на основе Aspose.Slides" title="Добавляйте водяные знаки в файлы PPTX онлайн" description="Бесплатное приложение Aspose.Slides Watermark создано на основе [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ru/python-net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPTX." button="Открыть Aspose.Slides Watermark" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides добавляет водяные знаки, ещё до написания кода.
- Добавьте текстовый или графический водяной знак в файл PPTX.
- Скачайте файл с водяным знаком.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие форматы с поддержкой водяных знаков" subTitle="С помощью Python можно также добавлять водяные знаки в другие поддерживаемые форматы презентаций." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
