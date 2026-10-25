---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Vízjelek hozzáadása PPT bemutatókhoz Pythonnal
url: /hu/python-net/watermark/ppt/
description: Adjon szöveges és képes vízjelet PPT bemutatókhoz Pythonnal és az Aspose.Slides segítségével.
keywords: vízjel hozzáadása PPT fájlhoz, szöveges vízjel PPT, képes vízjel PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Vízjelek hozzáadása PPT bemutatókhoz Pythonnal" h2="Készítsen Python-alkalmazásokat, amelyek az Aspose.Slides segítségével szöveges vagy képes vízjelet adnak PPT bemutatókhoz." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Vízjel hozzáadása egy PPT bemutatóhoz Pythonnal" variant="code" %}}

Az [Aspose.Slides for Python via .NET](/slides/hu/python-net/) segítségével Microsoft PowerPoint nélkül adhat szöveges vagy képes vízjelet egy PPT bemutatóhoz. A vízjel jelezheti a tulajdonost, bizalmasként vagy piszkozatként jelölheti a bemutatót, vagy egységes arculatot biztosíthat. Az alábbi példák az első diamintára helyezik a vízjelet, így az minden dián megjelenik, amely ezt a mintát használja.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Szöveges vízjel hozzáadása egy PPT bemutatóhoz – Python" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/code title="Képes vízjel hozzáadása egy PPT bemutatóhoz – Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Vízjel hozzáadása PPT fájlhoz Pythonnal lépésről lépésre" intro="Kövesse az alábbi lépéseket szöveges vízjel hozzáadásához egy PPT bemutatóhoz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nyissa meg a PPT fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kérje le az első diamintát a `masters` gyűjteményből.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg az `add_auto_shape` metódust egy téglalap diamintához adásához.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg az `add_text_frame` metódust a vízjel szövegének hozzáadásához, majd formázza és zárolja az alakzatot.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a `save` metódust a `SaveFormat.PPT` értékkel a vízjeles bemutató mentéséhez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Az Aspose.Slides segítségével készült" title="Vízjel hozzáadása PPT fájlokhoz online" description="Az ingyenes Aspose.Slides Watermark alkalmazás az [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hu/python-net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPT fájljaival." button="Aspose.Slides Watermark megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan adja hozzá az Aspose.Slides a vízjeleket, mielőtt kódot írna.
- Adjon szöveges vagy képes vízjelet PPT fájljához.
- Töltse le a vízjeles fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További vízjelet támogató formátumok" subTitle="Pythonnal más támogatott bemutatóformátumokhoz is adhat vízjelet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
