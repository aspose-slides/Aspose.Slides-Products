---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Přidání vodoznaků do prezentací PPTX v Pythonu
url: /cs/python-net/watermark/pptx/
description: Přidávejte textové a obrázkové vodoznaky do prezentací PPTX pomocí Pythonu a Aspose.Slides.
keywords: přidat vodoznak do PPTX, přidat textový vodoznak do PPTX, přidat obrázkový vodoznak do PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Přidání vodoznaků do prezentací PPTX v Pythonu" h2="Vytvářejte aplikace v Pythonu, které pomocí Aspose.Slides přidávají do prezentací PPTX textové nebo obrázkové vodoznaky." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Přidání vodoznaku do prezentace PPTX v Pythonu" variant="code" %}}

Pomocí [Aspose.Slides for Python via .NET](/slides/cs/python-net/) můžete do prezentace PPTX přidat textový nebo obrázkový vodoznak bez aplikace Microsoft PowerPoint. Vodoznak může označit vlastníka, označit prezentaci jako důvěrnou nebo jako koncept, případně zajistit jednotný vzhled značky. Následující příklady umísťují vodoznak na první předlohu snímků, takže se zobrazí na snímcích, které tuto předlohu používají.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Přidání textového vodoznaku do prezentace PPTX – Python" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/code title="Přidání obrázkového vodoznaku do prezentace PPTX – Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak přidat vodoznak do PPTX v Pythonu" intro="Pomocí těchto kroků přidáte do prezentace PPTX textový vodoznak." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete soubor PPTX pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Získejte první předlohu snímků z kolekce `masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte `add_auto_shape` a přidejte na předlohu snímků obdélník.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte `add_text_frame` a přidejte text vodoznaku, poté tvar naformátujte a uzamkněte.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte `save` s `SaveFormat.PPTX` a uložte prezentaci s vodoznakem.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Vytvořeno pomocí Aspose.Slides" title="Přidávejte vodoznaky do souborů PPTX online" description="Bezplatná aplikace Aspose.Slides Watermark je vytvořena pomocí [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/cs/python-net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Watermark" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides přidává vodoznaky, ještě než napíšete kód.
- Přidejte do svého souboru PPTX textový nebo obrázkový vodoznak.
- Stáhněte soubor s vodoznakem.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další formáty podporující vodoznaky" subTitle="V Pythonu můžete přidávat vodoznaky i do dalších podporovaných formátů prezentací." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
