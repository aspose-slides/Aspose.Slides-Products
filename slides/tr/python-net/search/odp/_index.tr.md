---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python ile ODP Sunumlarında Metin Arama
url: /tr/python-net/search/odp/
description: Python ve Aspose.Slides ile ODP sunumlarında metin arayın.
keywords: ODP içinde metin arama, ODP içinde kelime bulma, Python ile ODP sunumunda arama
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python ile ODP Sunumlarında Metin Arama" h2="Aspose.Slides ile OpenDocument sunumlarında metin bulan Python uygulamaları oluşturun." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python ile Bir ODP Sunumunda Metin Arama" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/tr/python-net/) ile her slaytta belirli bir dizeyi içeren metin çerçevelerini bulmak için [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) yöntemini kullanabilirsiniz.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Bir ODP Sunumunda Metin Arama – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python ile ODP İçinde Metin Nasıl Aranır" intro="Bir ODP sunumunda metin aramak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP dosyasını `Presentation` ile açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Slaytlarda dolaşın ve her biri için [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) yöntemini çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Eşleşen her metin çerçevesinin `text` özelliğini okuyun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides ile geliştirildi" title="ODP Dosyalarında Çevrimiçi Metin Arama" description="Ücretsiz Aspose.Slides Search uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/tr/python-net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi ODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Search uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın metni nasıl bulduğunu görün.
- ODP dosyanızda düz metin veya normal ifadelerle arama yapın.
- Eşleşmeleri metin dosyası olarak indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Arama İçin Desteklenen Diğer Biçimler" subTitle="Desteklenen diğer sunum biçimlerinde de metin aramak için Python kullanın." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
