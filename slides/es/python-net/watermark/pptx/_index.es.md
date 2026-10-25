---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Agregar marcas de agua a presentaciones PPTX con Python
url: /es/python-net/watermark/pptx/
description: Agregue marcas de agua de texto e imagen a presentaciones PPTX con Python y Aspose.Slides.
keywords: agregar marca de agua a PPTX, agregar marca de agua de texto a PPTX, agregar marca de agua de imagen a PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Agregar marcas de agua a presentaciones PPTX con Python" h2="Cree aplicaciones Python que agreguen marcas de agua de texto o imagen a presentaciones PPTX con Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Agregar una marca de agua a una presentación PPTX con Python" variant="code" %}}

Con [Aspose.Slides for Python via .NET](/slides/es/python-net/), puede agregar una marca de agua de texto o imagen a una presentación PPTX sin usar Microsoft PowerPoint. Una marca de agua puede identificar al propietario, marcar una presentación como confidencial o como borrador, o aportar una imagen de marca coherente. Los ejemplos siguientes colocan la marca de agua en el primer patrón de diapositivas, para que aparezca en las diapositivas que usan ese patrón.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Agregar una marca de agua de texto a una presentación PPTX – Python" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/code title="Agregar una marca de agua de imagen a una presentación PPTX – Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo agregar una marca de agua a PPTX con Python" intro="Siga estos pasos para agregar una marca de agua de texto a una presentación PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra el archivo PPTX con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenga el primer patrón de diapositivas de la colección `masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame a `add_auto_shape` para agregar un rectángulo al patrón de diapositivas.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame a `add_text_frame` para agregar el texto de la marca de agua y, después, dé formato a la forma y bloquéela.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame a `save` con `SaveFormat.PPTX` para guardar la presentación con marca de agua.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Creado con Aspose.Slides" title="Agregue marcas de agua a archivos PPTX en línea" description="La aplicación gratuita Aspose.Slides Watermark está creada con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/es/python-net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPTX." button="Abrir Aspose.Slides Watermark" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides agrega marcas de agua antes de escribir código.
- Agregue una marca de agua de texto o imagen a su archivo PPTX.
- Descargue el archivo con marca de agua.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con marcas de agua" subTitle="Con Python, también puede agregar marcas de agua a otros formatos de presentación compatibles." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
