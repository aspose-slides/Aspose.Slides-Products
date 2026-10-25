---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Aggiungere filigrane a presentazioni PPTX con Python
url: /it/python-net/watermark/pptx/
description: Aggiungi filigrane di testo e immagine a presentazioni PPTX con Python e Aspose.Slides.
keywords: aggiungere filigrana a PPTX, aggiungere filigrana di testo a PPTX, aggiungere filigrana immagine a PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Aggiungere filigrane a presentazioni PPTX con Python" h2="Crea applicazioni Python che aggiungono filigrane di testo o immagine a presentazioni PPTX con Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aggiungere una filigrana a una presentazione PPTX con Python" variant="code" %}}

Con [Aspose.Slides for Python via .NET](/slides/it/python-net/) puoi aggiungere una filigrana di testo o immagine a una presentazione PPTX senza usare Microsoft PowerPoint. Una filigrana può indicare il proprietario, contrassegnare una presentazione come riservata o come bozza, oppure garantire un branding coerente. Gli esempi seguenti inseriscono la filigrana nella prima diapositiva master, così compare nelle diapositive che usano quel master.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Aggiungere una filigrana di testo a una presentazione PPTX – Python" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/code title="Aggiungere una filigrana immagine a una presentazione PPTX – Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come aggiungere una filigrana a PPTX con Python" intro="Segui questi passaggi per aggiungere una filigrana di testo a una presentazione PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apri il file PPTX con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ottieni la prima diapositiva master dalla raccolta `masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama `add_auto_shape` per aggiungere un rettangolo alla diapositiva master.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama `add_text_frame` per aggiungere il testo della filigrana, quindi formatta e blocca la forma.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama `save` con `SaveFormat.PPTX` per salvare la presentazione con filigrana.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Realizzato con Aspose.Slides" title="Aggiungi filigrane a file PPTX online" description="L'app gratuita Aspose.Slides Watermark è realizzata con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/it/python-net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPTX." button="Apri Aspose.Slides Watermark" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides aggiunge le filigrane prima di scrivere codice.
- Aggiungi una filigrana di testo o immagine al tuo file PPTX.
- Scarica il file con filigrana.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per le filigrane" subTitle="Con Python puoi aggiungere filigrane anche ad altri formati di presentazione supportati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
