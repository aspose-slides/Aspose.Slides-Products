---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ ile PPT Sunumlarını Koruma
url: /tr/cpp/protect/ppt/
description: C++'ta PPT sunumlarını koruyun. Dosyaları şifrelemek ve yazma koruması ayarlamak için Aspose.Slides for C++ kullanın.
keywords: PPT yazma koruması, PPT şifreleme, PPT sunumunu kilitleme, PPT koruma
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ ile PPT Kilitleme veya Parolayla Koruma" h2="Microsoft PowerPoint olmadan sunumları şifrelemek ve yazma koruması ayarlamak için Aspose.Slides for C++ kullanın." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ ile PPT Sunumunu Koruma" variant="code" %}}

Aspose.Slides for C++, PPT sunumlarını açılmaya veya değiştirilmeye karşı korumanızı sağlar. Bir dosyayı `Encrypt` ile şifrelemek veya düzenlemeyi `SetWriteProtection` ile kısıtlamak için `Presentation` sınıfındaki `ProtectionManager` nesnesini kullanın.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ ile PPT Sunumunu Şifreleme" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ ile PPT Sunumuna Yazma Koruması Ayarlama" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ ile PPT Parolayla Nasıl Korunur" intro="Bir PPT sunumunu korumak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT dosyasını `Presentation` sınıfıyla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sunumu `ProtectionManager` nesnesiyle koruyun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Parola koruması için `Encrypt`, yazma koruması için `SetWriteProtection` kullanın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Korunan dosyayı `SaveFormat::Ppt` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides ile geliştirildi" title="PPT Dosyalarını Çevrimiçi Parolayla Koruma" description="Ücretsiz Aspose.Slides Lock uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPT dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Lock uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın sunumları nasıl koruduğunu görün.
- PPT dosyanızı açmak veya düzenlemek için bir parola belirleyin.
- Korunan dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Koruma İçin Desteklenen Diğer Biçimler" subTitle="C++ ile aşağıdaki biçimleri de koruyabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/cpp/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
