---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ajouter des filigranes à des présentations PPTX avec Python
url: /fr/python-net/watermark/pptx/
description: Ajoutez des filigranes texte et image à des présentations PPTX avec Python et Aspose.Slides.
keywords: ajouter un filigrane à PPTX, ajouter un filigrane texte à PPTX, ajouter un filigrane image à PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ajouter des filigranes à des présentations PPTX avec Python" h2="Créez des applications Python qui ajoutent des filigranes texte ou image à des présentations PPTX avec Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ajouter un filigrane à une présentation PPTX avec Python" variant="code" %}}

Avec [Aspose.Slides for Python via .NET](/slides/fr/python-net/), vous pouvez ajouter un filigrane texte ou image à une présentation PPTX sans Microsoft PowerPoint. Un filigrane peut indiquer le propriétaire, marquer une présentation comme confidentielle ou comme brouillon, ou garantir une image de marque cohérente. Les exemples ci-dessous placent le filigrane sur le premier masque de diapositive, afin qu'il apparaisse sur les diapositives qui utilisent ce masque.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ajouter un filigrane texte à une présentation PPTX – Python" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ajouter un filigrane image à une présentation PPTX – Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment ajouter un filigrane à PPTX avec Python" intro="Suivez ces étapes pour ajouter un filigrane texte à une présentation PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez le fichier PPTX avec `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenez le premier masque de diapositive de la collection `masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez `add_auto_shape` pour ajouter un rectangle au masque de diapositive.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez `add_text_frame` pour ajouter le texte du filigrane, puis mettez en forme et verrouillez la forme.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez `save` avec `SaveFormat.PPTX` pour enregistrer la présentation filigranée.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Conçu avec Aspose.Slides" title="Ajouter des filigranes à des fichiers PPTX en ligne" description="L'application gratuite Aspose.Slides Watermark est conçue avec [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fr/python-net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPTX." button="Ouvrir Aspose.Slides Watermark" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides ajoute des filigranes avant d'écrire du code.
- Ajoutez un filigrane texte ou image à votre fichier PPTX.
- Téléchargez le fichier filigrané.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour les filigranes" subTitle="Avec Python, vous pouvez aussi ajouter des filigranes à d'autres formats de présentation pris en charge." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
