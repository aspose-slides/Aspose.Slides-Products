---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Watermerken toevoegen aan ODP-presentaties met Python
url: /nl/python-net/watermark/odp/
description: Voeg tekst- en afbeeldingswatermerken toe aan ODP-presentaties met Python en Aspose.Slides.
keywords: watermerk toevoegen aan ODP, tekstwatermerk toevoegen aan ODP, afbeeldingswatermerk toevoegen aan ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Watermerken toevoegen aan ODP-presentaties met Python" h2="Bouw Python-toepassingen die met Aspose.Slides tekst- of afbeeldingswatermerken toevoegen aan ODP-presentaties." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Een watermerk toevoegen aan een ODP-presentatie met Python" variant="code" %}}

Met [Aspose.Slides for Python via .NET](/slides/nl/python-net/) voegt u een tekst- of afbeeldingswatermerk toe aan een ODP-presentatie zonder OpenOffice. Een watermerk kan de eigenaar aangeven, een presentatie markeren als vertrouwelijk of als concept, of zorgen voor een consistente huisstijl. In de onderstaande voorbeelden staat het watermerk op de eerste modeldia, zodat het verschijnt op alle dia's die dat model gebruiken.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Een tekstwatermerk toevoegen aan een ODP-presentatie – Python" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/code title="Een afbeeldingswatermerk toevoegen aan een ODP-presentatie – Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Een watermerk toevoegen aan ODP met Python: zo werkt het" intro="Volg deze stappen om een tekstwatermerk toe te voegen aan een ODP-presentatie." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open het ODP-bestand met `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Haal de eerste modeldia op uit de verzameling `masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep `add_auto_shape` aan om een rechthoek toe te voegen aan de modeldia.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep `add_text_frame` aan om de watermerktekst toe te voegen en maak de vorm daarna op en vergrendel deze.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep `save` aan met `SaveFormat.ODP` om de presentatie met watermerk op te slaan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Gebouwd met Aspose.Slides" title="Watermerken toevoegen aan ODP-bestanden online" description="De gratis app Aspose.Slides Watermark is gebouwd met [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/nl/python-net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen ODP-bestanden." button="Aspose.Slides Watermark openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Zie hoe Aspose.Slides watermerken toevoegt voordat u code schrijft.
- Voeg een tekst- of afbeeldingswatermerk toe aan uw ODP-bestand.
- Download het bestand met watermerk.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor watermerken" subTitle="Met Python kunt u ook watermerken toevoegen aan andere ondersteunde presentatieformaten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
