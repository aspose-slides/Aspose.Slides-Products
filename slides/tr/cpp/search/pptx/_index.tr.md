---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ ile PPTX Sunumlarında Metin Arama
url: /tr/cpp/search/pptx/
description: C++ ile PPTX sunumlarında metin arayın. Sunum dosyalarında metin bulmak için Aspose.Slides for C++ kullanın.
keywords: PPTX içinde kelime arama, PPTX içinde metin bulma, PPTX sunum metninde arama
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ ile PPTX İçinde Metin Arama" h2="Microsoft PowerPoint olmadan sunum dosyalarında metin bulmak için Aspose.Slides for C++ kullanın." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ ile Bir PPTX Sunumunda Metin Arama" variant="code" %}}

Aspose.Slides for C++, PPTX sunumlarında metin aramanızı sağlar. Bir slaydın metin çerçevelerini toplamak için `SlideUtil::GetAllTextBoxes` yöntemini kullanın, ardından metinlerinin istenen ifadeyi içerip içermediğini kontrol edin.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ Kullanarak Bir PPTX Sunumunda Metin Arama" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ ile PPTX İçinde Metin Nasıl Aranır" intro="Bir PPTX sunumunda metin aramak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX dosyasını `Presentation` sınıfıyla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}İstenen slaydı `Presentation::get_Slides` ile alın ve metin çerçevelerini [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/) ile okuyun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Her çerçevenin metninin istenen ifadeyi içerip içermediğini kontrol edin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides ile geliştirildi" title="PPTX Dosyalarında Çevrimiçi Metin Arama" description="Ücretsiz Aspose.Slides Search uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPTX dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Search uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın metni nasıl bulduğunu görün.
- PPTX dosyanızda düz metin veya normal ifadelerle arama yapın.
- Eşleşmeleri metin dosyası olarak indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Arama İçin Desteklenen Diğer Biçimler" subTitle="C++ ile aşağıdaki biçimlerde de metin arayabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/cpp/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
