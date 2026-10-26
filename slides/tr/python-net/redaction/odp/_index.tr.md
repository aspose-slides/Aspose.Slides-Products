---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python ile ODP Sunumlarında Metin Karartma
url: /tr/python-net/redaction/odp/
description: Python ile ODP sunumlarındaki hassas metni bulun ve değiştirin.
keywords: ODP karartma, ODP içinde metin bulma ve değiştirme, ODP sunumunu güncelleme
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python ile ODP Sunumlarında Metin Karartma" h2="Aspose.Slides ile sunumlardaki hassas metni bulan ve değiştiren Python uygulamaları oluşturun." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python ile Bir ODP Sunumunda Metin Karartma" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/tr/python-net/) ile bir ODP sunumunun tamamındaki hassas metni değiştirebilirsiniz. Aramayı denetlemek için `Presentation.replace_text` yöntemini `TextSearchOptions` ile kullanın, ardından değiştirilen sunumu kaydedin.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Bir ODP Sunumunda Metin Karartma – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.odp") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python ile Bir ODP Sunumunda Metin Nasıl Karartılır" intro="Bir ODP sunumundaki hassas metni değiştirmek için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP dosyasını `Presentation` ile açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}İstenen metni değiştirmek için [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) yöntemini `TextSearchOptions` ile kullanın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Değiştirilen sunumu `SaveFormat.ODP` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Aspose.Slides ile geliştirildi" title="ODP Dosyalarını Çevrimiçi Karartma" description="Ücretsiz Aspose.Slides Redaction uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/tr/python-net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi ODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Redaction uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın metni nasıl bulup değiştirdiğini görün.
- ODP dosyanızdaki metni, normal ifadeler dahil, bulun ve değiştirin.
- Karartılmış dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Karartma İçin Desteklenen Diğer Biçimler" subTitle="Desteklenen diğer sunum biçimlerinde de metin karartmak için Python kullanın." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
