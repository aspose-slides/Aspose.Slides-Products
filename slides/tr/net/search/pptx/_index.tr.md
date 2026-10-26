---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET ile PPTX Sunum Dosyalarında Metin Arama
url: /tr/net/search/pptx/
description: PPTX sunumlarında metin aramak için C# kaynak kodu.
keywords: PPTX içinde metin arama, PPTX içinde metin bulma, PPTX sunum metninde arama
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# ile PPTX Dosyalarında Metin Arama" h2="Sunucu tarafı API'lerle sunumlarda metin bulan .NET uygulamaları oluşturun." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# ile Bir PPTX Sunumunda Metin Arama" variant="code" %}}

[Aspose.Slides for .NET](/slides/tr/net/) ile bir PPTX sunumunda metin arayabilirsiniz. Bir slaydın metin çerçevelerini `SlideUtil.GetAllTextBoxes` ile alın, ardından `Text` değerlerinde istenen ifadeyi arayın.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# ile Bir PPTX Sunumunda Metin Arama" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# ile Bir PPTX Sunumunda Metin Nasıl Aranır" intro="Bir PPTX sunumunda metin aramak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX dosyasını `Presentation` ile yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}İstenen slaydı `Presentation.Slides` içinden alın ve bir değişkene atayın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Slaydın metin çerçevelerini [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/) ile alın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Her çerçevenin `Text` değerinin istenen ifadeyi içerip içermediğini kontrol edin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides ile geliştirildi" title="PPTX Dosyalarında Çevrimiçi Metin Arama" description="Ücretsiz Aspose.Slides Search uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPTX dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Search uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın metni nasıl bulduğunu görün.
- PPTX dosyanızda düz metin veya normal ifadelerle arama yapın.
- Eşleşmeleri metin dosyası olarak indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Arama İçin Desteklenen Diğer Biçimler" subTitle="C# ile aşağıdaki biçimlerde de metin arayabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
