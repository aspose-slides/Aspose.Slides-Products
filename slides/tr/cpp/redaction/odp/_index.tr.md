---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ ile ODP Sunumlarını Karartma
url: /tr/cpp/redaction/odp/
description: C++ ile ODP sunumlarını karartın. Sunum dosyalarındaki hassas metni bulup değiştirmek için Aspose.Slides for C++ kullanın.
keywords: ODP karartma, ODP içinde metin bulma ve değiştirme, ODP sunumunu güncelleme
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ ile ODP Karartma" h2="Microsoft PowerPoint olmadan sunum dosyalarındaki hassas metni bulup değiştirmek için Aspose.Slides for C++ kullanın." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ ile ODP Sunumunu Karartma" variant="code" %}}

Aspose.Slides for C++, slaytlardaki hassas metni değiştirerek ODP sunumlarını karartmanızı sağlar. Sunumda arama yapmak ve güncellenen dosyayı kaydetmeden önce eşleşen metni değiştirmek için `SlideUtil::FindAndReplaceText` yöntemini bir `Presentation` nesnesiyle kullanın.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ Kullanarak ODP Sunumunu Karartma" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ ile ODP Nasıl Karartılır" intro="Bir ODP sunumunu karartmak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP dosyasını `Presentation` sınıfıyla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hassas metni bulup değiştirmek için [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) yöntemini kullanın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Karartılmış dosyayı `SaveFormat::Odp` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Aspose.Slides ile geliştirildi" title="ODP Dosyalarını Çevrimiçi Karartma" description="Ücretsiz Aspose.Slides Redaction uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi ODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Redaction uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın metni nasıl bulup değiştirdiğini görün.
- ODP dosyanızdaki metni, normal ifadeler dahil, bulun ve değiştirin.
- Karartılmış dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Karartma İçin Desteklenen Diğer Biçimler" subTitle="C++ ile aşağıdaki biçimleri de karartabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/cpp/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/cpp/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
