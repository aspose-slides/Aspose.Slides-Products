---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python ile PPT Sunumlarında Metin Arama
url: /tr/python-net/search/ppt/
description: Python ve Aspose.Slides ile PPT sunumlarında metin arayın.
keywords: PPT içinde metin arama, PPT içinde kelime bulma, Python ile PPT sunumunda arama
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python ile PPT Sunumlarında Metin Arama" h2="Aspose.Slides ile PowerPoint sunumlarında metin bulan Python uygulamaları oluşturun." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python ile Bir PPT Sunumunda Metin Arama" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/tr/python-net/) ile her slaytta belirli bir dizeyi içeren metin çerçevelerini bulmak için [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) yöntemini kullanabilirsiniz.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Bir PPT Sunumunda Metin Arama – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python ile PPT İçinde Metin Nasıl Aranır" intro="Bir PPT sunumunda metin aramak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT dosyasını `Presentation` ile açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Slaytlarda dolaşın ve her biri için [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) yöntemini çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Eşleşen her metin çerçevesinin `text` özelliğini okuyun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides ile geliştirildi" title="PPT Dosyalarında Çevrimiçi Metin Arama" description="Ücretsiz Aspose.Slides Search uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/tr/python-net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPT dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Search uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın metni nasıl bulduğunu görün.
- PPT dosyanızda düz metin veya normal ifadelerle arama yapın.
- Eşleşmeleri metin dosyası olarak indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Arama İçin Desteklenen Diğer Biçimler" subTitle="Desteklenen diğer sunum biçimlerinde de metin aramak için Python kullanın." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
