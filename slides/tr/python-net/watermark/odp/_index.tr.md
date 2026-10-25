---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python ile ODP sunularına filigran ekleme
url: /tr/python-net/watermark/odp/
description: Python ve Aspose.Slides ile ODP sunularına metin ve görüntü filigranları ekleyin.
keywords: ODP dosyasına filigran ekle, ODP dosyasına metin filigranı ekle, ODP dosyasına görüntü filigranı ekle
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python ile ODP sunularına filigran ekleme" h2="Aspose.Slides ile ODP sunularına metin veya görüntü filigranı ekleyen Python uygulamaları geliştirin." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python ile bir ODP sunusuna filigran ekleme" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/tr/python-net/) ile OpenOffice kullanmadan bir ODP sunusuna metin veya görüntü filigranı ekleyebilirsiniz. Filigran sahipliği belirtebilir, bir sunuyu gizli veya taslak olarak işaretleyebilir ya da tutarlı bir marka görünümü sağlayabilir. Aşağıdaki örnekler filigranı ilk asıl slayda yerleştirir; böylece filigran bu asıl slaydı kullanan slaytlarda görünür.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Bir ODP sunusuna metin filigranı ekleme – Python" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/code title="Bir ODP sunusuna görüntü filigranı ekleme – Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python ile ODP dosyasına filigran nasıl eklenir" intro="Bir ODP sunusuna metin filigranı eklemek için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP dosyasını `Presentation` ile açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`masters` koleksiyonundan ilk asıl slaydı alın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Asıl slayda dikdörtgen eklemek için `add_auto_shape` çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Filigran metnini eklemek için `add_text_frame` çağırın, ardından şekli biçimlendirip kilitleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Filigranlı sunuyu kaydetmek için `save` yöntemini `SaveFormat.ODP` ile çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides ile geliştirildi" title="ODP dosyalarına çevrimiçi filigran ekleyin" description="Ücretsiz Aspose.Slides Watermark uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/tr/python-net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi ODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Watermark uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın filigranları nasıl eklediğini görün.
- ODP dosyanıza metin veya görüntü filigranı ekleyin.
- Filigranlı dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Filigranı destekleyen diğer biçimler" subTitle="Python ile desteklenen diğer sunu biçimlerine de filigran ekleyebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
