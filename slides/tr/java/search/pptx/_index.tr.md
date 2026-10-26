---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java ile PPTX Sunum Dosyalarında Metin Arama
url: /tr/java/search/pptx/
description: Aspose.Slides for Java ile Java'da PPTX sunumlarında metin arayın.
keywords: PPTX içinde kelime arama, PPTX içinde metin arama, PPTX sunum metninde arama
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java ile PPTX İçinde Metin Arama" h2="Sunucu tarafı API'lerle sunum dosyalarında metin arayan Java uygulamaları oluşturun." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java ile Bir PPTX Sunumunda Metin Arama" variant="code" %}}

[Aspose.Slides for Java](/slides/tr/java/) ile PPTX sunumlarında metin arayabilirsiniz. Metin çerçevelerini toplamak için `SlideUtil.getAllTextBoxes` yöntemini kullanın, ardından `ITextFrame`, `IParagraph` ve `IPortion` nesnelerini inceleyin.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java Kullanarak Bir PPTX Sunumunda Metin Arama" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java ile PPTX İçinde Metin Nasıl Aranır" intro="Bir PPTX sunumunda metin aramak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX dosyasını `Presentation` sınıfıyla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Her slayttaki metin çerçevelerini toplamak için `SlideUtil.getAllTextBoxes` yöntemini çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Eşleşen metni bulmak için `ITextFrame`, `IParagraph` ve `IPortion` nesnelerini inceleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides ile geliştirildi" title="PPTX Dosyalarında Çevrimiçi Metin Arama" description="Ücretsiz Aspose.Slides Search uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Java](https://products.aspose.com/slides/tr/java/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPTX dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Search uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın metni nasıl bulduğunu görün.
- PPTX dosyanızda düz metin veya normal ifadelerle arama yapın.
- Eşleşmeleri metin dosyası olarak indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Arama İçin Desteklenen Diğer Biçimler" subTitle="Java ile aşağıdaki biçimlerde de metin arayabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/java/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
