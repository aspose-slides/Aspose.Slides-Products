---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3630
title: Java ile PPT ek açıklamalarını kaldırma
url: /tr/java/annotation/ppt/ 
description: Aspose.Slides for Java ile Java'da PPT sunumlarından yorumları ve yorum yazarlarını kaldırın.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java ile PPT dosyasından yorumları ve yorum yazarlarını kaldırma" h2="Sunum dosyalarından yorumları ve yorum yazarlarını kaldırmak için Aspose.Slides for Java kullanın." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java ile PPT dosyasından yorumları kaldırma" variant="code" %}}

Aspose.Slides for Java, PPT sunumlarından yorumları ve yorum yazarlarını kaldırmanıza olanak tanır. Bir dosyayı `Presentation` sınıfıyla yükleyin, `getCommentAuthors` içindeki `ICommentAuthor` nesnelerinde dolaşın, yorumlarını temizleyin ve güncellenen sunumu kaydedin.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT dosyasından ek açıklamaları silme – Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java ile PPT dosyasından yorumlar nasıl kaldırılır" intro="Bir PPT sunumundan yorumları ve yorum yazarlarını kaldırmak için bu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aspose.Slides for Java'yı yükleyin. Bkz. [Kurulum](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT dosyasını `Presentation` sınıfıyla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`getCommentAuthors` içindeki `ICommentAuthor` nesnelerinde dolaşın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Her yazarın yorumlarını `getComments().clear()` ile temizleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Yorum yazarı koleksiyonunu temizleyin ve güncellenen PPT dosyasını kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides ile geliştirildi" title="PPT yorumlarını çevrimiçi kaldırma" description="Ücretsiz Aspose.Slides Annotation uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Java](https://products.aspose.com/slides/tr/java/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPT dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Annotation uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın yorumları nasıl kaldırdığını görün.
- PPT dosyanızdaki tüm yorumları kaldırın.
- Temizlenen dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Ek açıklamalar için desteklenen diğer biçimler" subTitle="Java ile diğer biçimlerden de ek açıklamaları kaldırabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
