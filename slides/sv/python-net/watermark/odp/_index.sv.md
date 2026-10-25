---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Lägg till vattenstämplar i ODP-presentationer med Python
url: /sv/python-net/watermark/odp/
description: Lägg till text- och bildvattenstämplar i ODP-presentationer med Python och Aspose.Slides.
keywords: lägg till vattenstämpel i ODP, lägg till textvattenstämpel i ODP, lägg till bildvattenstämpel i ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lägg till vattenstämplar i ODP-presentationer med Python" h2="Bygg Python-program som lägger till text- eller bildvattenstämplar i ODP-presentationer med Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Lägg till en vattenstämpel i en ODP-presentation med Python" variant="code" %}}

Med [Aspose.Slides for Python via .NET](/slides/sv/python-net/) kan du lägga till en text- eller bildvattenstämpel i en ODP-presentation utan OpenOffice. En vattenstämpel kan visa vem som äger presentationen, markera den som konfidentiell eller som utkast, eller ge en enhetlig profil. I exemplen nedan placeras vattenstämpeln på den första bildbakgrunden, så att den visas på alla bilder som använder den.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Lägg till en textvattenstämpel i en ODP-presentation – Python" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/code title="Lägg till en bildvattenstämpel i en ODP-presentation – Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så lägger du till en vattenstämpel i ODP med Python" intro="Följ de här stegen för att lägga till en textvattenstämpel i en ODP-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öppna ODP-filen med `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hämta den första bildbakgrunden från samlingen `masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa `add_auto_shape` för att lägga till en rektangel på bildbakgrunden.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa `add_text_frame` för att lägga till vattenstämpeltexten och formatera och lås sedan formen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa `save` med `SaveFormat.ODP` för att spara presentationen med vattenstämpel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Byggd med Aspose.Slides" title="Lägg till vattenstämplar i ODP-filer online" description="Den kostnadsfria appen Aspose.Slides Watermark är byggd med [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/sv/python-net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna ODP-filer." button="Öppna Aspose.Slides Watermark" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides lägger till vattenstämplar innan du skriver kod.
- Lägg till en text- eller bildvattenstämpel i din ODP-fil.
- Ladda ner filen med vattenstämpel.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöder vattenstämplar" subTitle="Med Python kan du även lägga till vattenstämplar i andra presentationsformat som stöds." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/python-net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/python-net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
