---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET ile PPT Sunum Dosyalarını Koruma
url: /tr/net/protect/ppt/
description: PPT sunumlarını parolayla korumak için C# kaynak kodu.
keywords: PPT yazma koruması, PPT şifreleme, PPT sunumunu kilitleme, PPT koruma
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# ile PPT Dosyalarını Kilitleme veya Parolayla Koruma" h2="Sunucu tarafı API'lerle sunumları şifreleyen ve değişiklikleri kısıtlayan .NET uygulamaları geliştirin." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# ile PPT Sunumunu Koruma" variant="code" %}}

[Aspose.Slides for .NET](/slides/tr/net/) ile bir PPT sunumunu şifreleyebilir veya parolayla değiştirilmesini kısıtlayabilirsiniz. `ProtectionManager.Encrypt` ile şifrelenen bir sunumu açmak için parola gerekir. Sunumun açılmasına izin verip değişiklikleri kısıtlamak için `ProtectionManager.SetWriteProtection` kullanın.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# ile PPT Sunumunu Şifreleme" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C# ile PPT Sunumuna Yazma Koruması Ayarlama" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# ile PPT Sunumunu Parolayla Koruma" intro="Bir PPT sunumunu parolayla korumak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT dosyasını `Presentation` ile yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sunumu `ProtectionManager.Encrypt` ile şifreleyin veya değişiklikleri `ProtectionManager.SetWriteProtection` ile kısıtlayın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Korunan dosyayı `SaveFormat.Ppt` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides ile geliştirildi" title="PPT Dosyalarını Çevrimiçi Parolayla Koruma" description="Ücretsiz Aspose.Slides Lock uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPT dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Lock uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın sunumları nasıl koruduğunu görün.
- PPT dosyanızı açmak veya düzenlemek için bir parola belirleyin.
- Korunan dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Koruma İçin Desteklenen Diğer Biçimler" subTitle="C# ile aşağıdaki biçimleri de koruyabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
