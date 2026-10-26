---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET ile PPTX Sunum Dosyalarını Karartma
url: /tr/net/redaction/pptx/
description: PPTX sunumlarında metin bulup değiştirmek için C# kaynak kodu.
keywords: PPTX karartma, PPTX içinde metin bulma ve değiştirme, PPTX sunumunu güncelleme
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# ile PPTX Dosyalarını Karartma" h2="Sunucu tarafı API'lerle sunumlarda metin bulan ve değiştiren .NET uygulamaları oluşturun." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# ile PPTX Sunumunu Karartma" variant="code" %}}

[Aspose.Slides for .NET](/slides/tr/net/) ile bir PPTX sunumunda metin bulup değiştirebilirsiniz. Aramayı denetlemek için `Presentation.ReplaceText` yöntemini `TextSearchOptions` ile kullanın, ardından değiştirilen sunumu kaydedin.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# ile PPTX Sunumunu Karartma" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# ile PPTX Sunumu Nasıl Karartılır" intro="Bir PPTX sunumundaki metni değiştirmek için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX dosyasını `Presentation` ile yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}İstenen metni değiştirmek için [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) yöntemini `TextSearchOptions` ile kullanın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Değiştirilen sunumu `SaveFormat.Pptx` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Aspose.Slides ile geliştirildi" title="PPTX Dosyalarını Çevrimiçi Karartma" description="Ücretsiz Aspose.Slides Redaction uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPTX dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Redaction uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın metni nasıl bulup değiştirdiğini görün.
- PPTX dosyanızdaki metni, normal ifadeler dahil, bulun ve değiştirin.
- Karartılmış dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Karartma İçin Desteklenen Diğer Biçimler" subTitle="C# ile aşağıdaki biçimleri de karartabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
