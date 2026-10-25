---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Wasserzeichen zu ODP-Präsentationen mit Python hinzufügen
url: /de/python-net/watermark/odp/
description: Fügen Sie ODP-Präsentationen mit Python und Aspose.Slides Text- und Bildwasserzeichen hinzu.
keywords: Wasserzeichen zu ODP hinzufügen, Textwasserzeichen zu ODP hinzufügen, Bildwasserzeichen zu ODP hinzufügen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Wasserzeichen zu ODP-Präsentationen mit Python hinzufügen" h2="Entwickeln Sie Python-Anwendungen, die ODP-Präsentationen mit Aspose.Slides Text- oder Bildwasserzeichen hinzufügen." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Einer ODP-Präsentation mit Python ein Wasserzeichen hinzufügen" variant="code" %}}

Mit [Aspose.Slides for Python via .NET](/slides/de/python-net/) fügen Sie einer ODP-Präsentation ein Text- oder Bildwasserzeichen hinzu, ohne OpenOffice zu verwenden. Ein Wasserzeichen kennzeichnet den Eigentümer, markiert eine Präsentation als vertraulich oder als Entwurf oder sorgt für ein einheitliches Branding. Die folgenden Beispiele platzieren das Wasserzeichen auf der ersten Masterfolie, sodass es auf allen Folien erscheint, die diesen Master verwenden.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Einer ODP-Präsentation ein Textwasserzeichen hinzufügen – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
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

    presentation.save("watermarked.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Einer ODP-Präsentation ein Bildwasserzeichen hinzufügen – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    with open("watermark.png", "rb") as image_stream:
        watermark_image = presentation.images.add_image(image_stream.read())

    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 100, 100, watermark_image.width, watermark_image.height)

    watermark_shape.fill_format.fill_type = slides.FillType.PICTURE
    watermark_shape.fill_format.picture_fill_format.picture.image = watermark_image
    watermark_shape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    presentation.save("watermarked.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So fügen Sie ODP mit Python ein Wasserzeichen hinzu" intro="Gehen Sie wie folgt vor, um einer ODP-Präsentation ein Textwasserzeichen hinzuzufügen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die ODP-Datei mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die erste Masterfolie aus der Sammlung `masters` ab.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie `add_auto_shape` auf, um der Masterfolie ein Rechteck hinzuzufügen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie `add_text_frame` auf, um den Wasserzeichentext hinzuzufügen, und formatieren und sperren Sie anschließend die Form.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie `save` mit `SaveFormat.ODP` auf, um die Präsentation mit Wasserzeichen zu speichern.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Entwickelt mit Aspose.Slides" title="ODP-Dateien online mit Wasserzeichen versehen" description="Die kostenlose App Aspose.Slides Watermark basiert auf [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/de/python-net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen ODP-Dateien leisten kann." button="Aspose.Slides Watermark öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Wasserzeichen hinzufügt, bevor Sie Code schreiben.
- Fügen Sie Ihrer ODP-Datei ein Text- oder Bildwasserzeichen hinzu.
- Laden Sie die Datei mit Wasserzeichen herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate für Wasserzeichen" subTitle="Mit Python können Sie auch anderen unterstützten Präsentationsformaten Wasserzeichen hinzufügen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/python-net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
