---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java ile PPT Sunum Dosyalarında Metin Arama
url: /tr/java/search/ppt/
description: Aspose.Slides for Java ile Java'da PPT sunumlarında metin arayın.
keywords: PPT içinde kelime arama, PPT içinde metin arama, PPT sunum metninde arama
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java ile PPT İçinde Metin Arama" h2="Sunucu tarafı API'lerle sunum dosyalarında metin arayan Java uygulamaları oluşturun." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java ile Bir PPT Sunumunda Metin Arama" variant="code" %}}

[Aspose.Slides for Java](/slides/tr/java/) ile PPT sunumlarında metin arayabilirsiniz. Metin çerçevelerini toplamak için `SlideUtil.getAllTextBoxes` yöntemini kullanın, ardından `ITextFrame`, `IParagraph` ve `IPortion` nesnelerini inceleyin.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java Kullanarak Bir PPT Sunumunda Metin Arama" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java ile PPT İçinde Metin Nasıl Aranır" intro="Bir PPT sunumunda metin aramak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT dosyasını `Presentation` sınıfıyla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Her slayttaki metin çerçevelerini toplamak için `SlideUtil.getAllTextBoxes` yöntemini çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Eşleşen metni bulmak için `ITextFrame`, `IParagraph` ve `IPortion` nesnelerini inceleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides ile geliştirildi" title="PPT Dosyalarında Çevrimiçi Metin Arama" description="Ücretsiz Aspose.Slides Search uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Java](https://products.aspose.com/slides/tr/java/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPT dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Search uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın metni nasıl bulduğunu görün.
- PPT dosyanızda düz metin veya normal ifadelerle arama yapın.
- Eşleşmeleri metin dosyası olarak indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Arama İçin Desteklenen Diğer Biçimler" subTitle="Java ile aşağıdaki biçimlerde de metin arayabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
