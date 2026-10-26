---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java ile PPT Sunum Dosyalarını Karartma
url: /tr/java/redaction/ppt/
description: Aspose.Slides for Java ile Java'da PPT sunumlarında metin bulun ve değiştirin.
keywords: PPT karartma, PPT içinde metin bulma ve değiştirme, PPT sunumunu güncelleme
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java ile PPT Karartma" h2="Sunucu tarafı API'lerle sunum dosyalarında metin bulan ve değiştiren Java uygulamaları oluşturun." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java ile PPT Sunumunu Karartma" variant="code" %}}

[Aspose.Slides for Java](/slides/tr/java/) ile PPT sunumlarında metin bulup değiştirebilirsiniz. Sunumda arama yapmak ve eşleşen metni yeni bir değerle değiştirmek için `SlideUtil.findAndReplaceText` yöntemini kullanın.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java Kullanarak PPT Sunumunu Karartma" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java ile PPT Nasıl Karartılır" intro="Bir PPT sunumunu karartmak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT dosyasını `Presentation` sınıfıyla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Metin bulup değiştirmek için `SlideUtil.findAndReplaceText` yöntemini çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Güncellenen sunumu `SaveFormat.Ppt` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Aspose.Slides ile geliştirildi" title="PPT Dosyalarını Çevrimiçi Karartma" description="Ücretsiz Aspose.Slides Redaction uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Java](https://products.aspose.com/slides/tr/java/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPT dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Redaction uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın metni nasıl bulup değiştirdiğini görün.
- PPT dosyanızdaki metni, normal ifadeler dahil, bulun ve değiştirin.
- Karartılmış dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Karartma İçin Desteklenen Diğer Biçimler" subTitle="Java ile aşağıdaki biçimleri de karartabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/java/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
