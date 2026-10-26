---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET ile ODP Sunum Dosyalarını Koruma
url: /tr/net/protect/odp/
description: ODP sunumlarını parolayla korumak için C# kaynak kodu.
keywords: ODP yazma koruması, ODP şifreleme, ODP sunumunu kilitleme, ODP koruma
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# ile ODP Dosyalarını Kilitleme veya Parolayla Koruma" h2="Sunucu tarafı API'lerle sunumları şifreleyen ve değişiklikleri kısıtlayan .NET uygulamaları geliştirin." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# ile ODP Sunumunu Koruma" variant="code" %}}

[Aspose.Slides for .NET](/slides/tr/net/) ile bir ODP sunumunu şifreleyebilir veya parolayla değiştirilmesini kısıtlayabilirsiniz. `ProtectionManager.Encrypt` ile şifrelenen bir sunumu açmak için parola gerekir. Sunumun açılmasına izin verip değişiklikleri kısıtlamak için `ProtectionManager.SetWriteProtection` kullanın.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# ile ODP Sunumunu Şifreleme" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C# ile ODP Sunumuna Yazma Koruması Ayarlama" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# ile ODP Sunumunu Parolayla Koruma" intro="Bir ODP sunumunu parolayla korumak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP dosyasını `Presentation` ile yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sunumu `ProtectionManager.Encrypt` ile şifreleyin veya değişiklikleri `ProtectionManager.SetWriteProtection` ile kısıtlayın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Korunan dosyayı `SaveFormat.Odp` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides ile geliştirildi" title="ODP Dosyalarını Çevrimiçi Parolayla Koruma" description="Ücretsiz Aspose.Slides Lock uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi ODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Lock uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın sunumları nasıl koruduğunu görün.
- ODP dosyanızı açmak veya düzenlemek için bir parola belirleyin.
- Korunan dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Koruma İçin Desteklenen Diğer Biçimler" subTitle="C# ile aşağıdaki biçimleri de koruyabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
