---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python ile PPT dosyalarından metin çıkarma
url: /tr/python-net/parser/ppt/
description: Python ile PPT sunularından metin ve metin biçimlendirme ayrıntılarını çıkarın.
keywords: Python ile PPT ayrıştırma, PPT ayrıştırıcı Python, Python'da PPT dosyasından veri çıkarma, Python ile PPT dosyasından metin çıkarma
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python ile PPT sunularından metin çıkarma" h2="Aspose.Slides ile PowerPoint sunularından metin ve biçimlendirme ayrıntılarını çıkaran Python uygulamaları geliştirin." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python ile bir PPT sunusundan metin çıkarma" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/tr/python-net/), `SlideUtil` üzerinde statik [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) yöntemini sunar. Bu yöntem tüm sunudaki `TextFrame` nesnelerini döndürür ve asıl slaytlardaki metni de içerebilir. Aşağıdaki örnek bir PPT sunusundan metni ve ilgili yazı tipi ayrıntılarını çıkarır.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Bir PPT sunusundan metin çıkarma – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.ppt") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python ile PPT dosyasından metin nasıl çıkarılır" intro="Bir PPT dosyasından metin çıkarmak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT dosyasını `Presentation` ile açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil.get_all_text_frames` yöntemini çağırın ve asıl slaytların dahil edilip edilmeyeceğini belirtin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Döndürülen `TextFrame` nesneleri üzerinde dolaşın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Her metin çerçevesinin `paragraphs` koleksiyonu üzerinde dolaşın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Her paragrafın `portions` koleksiyonu üzerinde dolaşın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Geçerli parçanın `text` değerini ve biçimlendirme özelliklerini okuyun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides ile geliştirildi" title="Metin ve görüntüleri çevrimiçi çıkarın" description="Ücretsiz Aspose.Slides Parser uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/tr/python-net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPT dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Parser uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın dosyalarınızı nasıl okuduğunu görün.
- Bir PPT dosyası yükleyin ve metnini ve görüntülerini alın.
- Her şeyi tek bir ZIP arşivi olarak indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Ayrıştırma için desteklenen diğer biçimler" subTitle="Python ile desteklenen diğer sunu biçimlerinden de metin çıkarabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
