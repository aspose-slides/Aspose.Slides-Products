---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java ile PPT Sunum Dosyalarını Koruma
url: /tr/java/protect/ppt/
description: Java'da PPT sunumlarını koruyun. Sunum dosyalarını şifrelemek ve yazma koruması ayarlamak için Aspose.Slides for Java kullanın.
keywords: PPT yazma koruması, bir PPT şifreleme, PPT sunumunu kilitleme, PPT koruma
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java ile PPT Kilitleme veya Parolayla Koruma" h2="Sunum dosyalarını sunucu tarafı API'lerle koruyan Java uygulamaları geliştirin." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java ile PPT Sunumunu Koruma" variant="code" %}}

[Aspose.Slides for Java](/slides/tr/java/) ile bir parola belirleyerek PPT sunumunu açılmaya veya değiştirilmeye karşı koruyabilirsiniz. `encrypt` ve `setWriteProtection` gibi yöntemleri çağırmak için `Presentation` sınıfındaki `ProtectionManager` nesnesini kullanın.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java ile PPT Sunumunu Şifreleme" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Java ile PPT Sunumuna Yazma Koruması Ayarlama" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java ile PPT Parolayla Nasıl Korunur" intro="Bir PPT sunumunu korumak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT dosyasını `Presentation` sınıfıyla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ProtectionManager` nesnesinin `encrypt` yöntemini veya `setWriteProtection` yöntemini çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Korunan dosyayı `SaveFormat.Ppt` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides ile geliştirildi" title="PPT Dosyalarını Çevrimiçi Parolayla Koruma" description="Ücretsiz Aspose.Slides Lock uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Java](https://products.aspose.com/slides/tr/java/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPT dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Lock uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın sunumları nasıl koruduğunu görün.
- PPT dosyanızı açmak veya düzenlemek için bir parola belirleyin.
- Korunan dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Koruma İçin Desteklenen Diğer Biçimler" subTitle="Java ile aşağıdaki biçimleri de koruyabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/java/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
