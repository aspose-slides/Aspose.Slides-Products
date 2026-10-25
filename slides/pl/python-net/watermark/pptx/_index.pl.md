---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Dodawanie znaków wodnych do prezentacji PPTX w Pythonie
url: /pl/python-net/watermark/pptx/
description: Dodawaj tekstowe i graficzne znaki wodne do prezentacji PPTX za pomocą Pythona i Aspose.Slides.
keywords: dodawanie znaku wodnego do PPTX, tekstowy znak wodny PPTX, graficzny znak wodny PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Dodawanie znaków wodnych do prezentacji PPTX w Pythonie" h2="Twórz aplikacje w Pythonie, które za pomocą Aspose.Slides dodają tekstowe lub graficzne znaki wodne do prezentacji PPTX." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Dodawanie znaku wodnego do prezentacji PPTX w Pythonie" variant="code" %}}

Dzięki [Aspose.Slides for Python via .NET](/slides/pl/python-net/) możesz dodać tekstowy lub graficzny znak wodny do prezentacji PPTX bez programu Microsoft PowerPoint. Znak wodny może wskazywać właściciela, oznaczać prezentację jako poufną lub roboczą albo zapewniać spójny wizerunek marki. Poniższe przykłady umieszczają znak wodny na pierwszym wzorcu slajdów, dzięki czemu pojawia się on na slajdach korzystających z tego wzorca.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Dodawanie tekstowego znaku wodnego do prezentacji PPTX – Python" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/code title="Dodawanie graficznego znaku wodnego do prezentacji PPTX – Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak dodać znak wodny do PPTX w Pythonie" intro="Wykonaj poniższe kroki, aby dodać tekstowy znak wodny do prezentacji PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otwórz plik PPTX za pomocą `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pobierz pierwszy wzorzec slajdów z kolekcji `masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj `add_auto_shape`, aby dodać prostokąt do wzorca slajdów.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj `add_text_frame`, aby dodać tekst znaku wodnego, a następnie sformatuj i zablokuj kształt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj `save` z `SaveFormat.PPTX`, aby zapisać prezentację ze znakiem wodnym.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Zbudowano z Aspose.Slides" title="Dodawaj znaki wodne do plików PPTX online" description="Bezpłatna aplikacja Aspose.Slides Watermark została zbudowana z użyciem [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pl/python-net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPTX." button="Otwórz Aspose.Slides Watermark" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides dodaje znaki wodne, zanim napiszesz kod.
- Dodaj tekstowy lub graficzny znak wodny do pliku PPTX.
- Pobierz plik ze znakiem wodnym.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne formaty obsługujące znaki wodne" subTitle="W Pythonie możesz też dodawać znaki wodne do innych obsługiwanych formatów prezentacji." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
