---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Přidání vodoznaků do prezentací ODP v Pythonu
url: /cs/python-net/watermark/odp/
description: Přidávejte textové a obrázkové vodoznaky do prezentací ODP pomocí Pythonu a Aspose.Slides.
keywords: přidat vodoznak do ODP, přidat textový vodoznak do ODP, přidat obrázkový vodoznak do ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Přidání vodoznaků do prezentací ODP v Pythonu" h2="Vytvářejte aplikace v Pythonu, které pomocí Aspose.Slides přidávají do prezentací ODP textové nebo obrázkové vodoznaky." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Přidání vodoznaku do prezentace ODP v Pythonu" variant="code" %}}

Pomocí [Aspose.Slides for Python via .NET](/slides/cs/python-net/) můžete do prezentace ODP přidat textový nebo obrázkový vodoznak bez sady OpenOffice. Vodoznak může označit vlastníka, označit prezentaci jako důvěrnou nebo jako koncept, případně zajistit jednotný vzhled značky. Následující příklady umísťují vodoznak na první předlohu snímků, takže se zobrazí na snímcích, které tuto předlohu používají.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Přidání textového vodoznaku do prezentace ODP – Python" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/code title="Přidání obrázkového vodoznaku do prezentace ODP – Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak přidat vodoznak do ODP v Pythonu" intro="Pomocí těchto kroků přidáte do prezentace ODP textový vodoznak." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete soubor ODP pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Získejte první předlohu snímků z kolekce `masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte `add_auto_shape` a přidejte na předlohu snímků obdélník.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte `add_text_frame` a přidejte text vodoznaku, poté tvar naformátujte a uzamkněte.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte `save` s `SaveFormat.ODP` a uložte prezentaci s vodoznakem.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Vytvořeno pomocí Aspose.Slides" title="Přidávejte vodoznaky do souborů ODP online" description="Bezplatná aplikace Aspose.Slides Watermark je vytvořena pomocí [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/cs/python-net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory ODP." button="Otevřít Aspose.Slides Watermark" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides přidává vodoznaky, ještě než napíšete kód.
- Přidejte do svého souboru ODP textový nebo obrázkový vodoznak.
- Stáhněte soubor s vodoznakem.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další formáty podporující vodoznaky" subTitle="V Pythonu můžete přidávat vodoznaky i do dalších podporovaných formátů prezentací." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
