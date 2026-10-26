---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET ile PPT Sunum Dosyalarının Kilidini Açma
url: /tr/net/unlock/ppt/
description: PPT sunumlarından parola korumasını kaldırmak için C# kaynak kodu.
keywords: PPT yazma korumasını kaldırma, PPT şifresini çözme, PPT sunumunun kilidini açma, PPT korumasını kaldırma
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# ile PPT Dosyalarının Kilidini Açma" h2="Sunucu tarafı API'lerle sunumlardan şifrelemeyi ve yazma korumasını kaldıran .NET uygulamaları geliştirin." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# ile PPT Sunumundan Korumayı Kaldırma" variant="code" %}}

[Aspose.Slides for .NET](/slides/tr/net/) ile bir PPT sunumundan şifrelemeyi veya yazma korumasını kaldırabilirsiniz. Şifrelemeyi kaldırmak için sunumu doğru parolayla yükleyin ve `ProtectionManager.RemoveEncryption` çağırın. Yazma korumasını kaldırmak için `ProtectionManager.RemoveWriteProtection` çağırın.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# ile PPT Sunumundan Şifrelemeyi Kaldırma" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.ppt", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C# ile PPT Sunumundan Yazma Korumasını Kaldırma" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.ppt");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# ile PPT Sunumundan Koruma Nasıl Kaldırılır" intro="Bir PPT sunumundan korumayı kaldırmak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT dosyasını `Presentation` ile yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Şifreli bir dosya için, yüklemeden önce parolayı `LoadOptions.Password` aracılığıyla belirtin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uygulanan korumaya göre `ProtectionManager.RemoveEncryption` veya `ProtectionManager.RemoveWriteProtection` çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kilidi açılan sunumu `SaveFormat.Ppt` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Aspose.Slides ile geliştirildi" title="PPT Dosyalarının Kilidini Çevrimiçi Açma" description="Ücretsiz Aspose.Slides Unlock uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPT dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Unlock uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın korumayı nasıl kaldırdığını görün.
- PPT dosyanızdan parolayı veya yazma korumasını kaldırın.
- Kilidi açılan dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Kilit Açma İçin Desteklenen Diğer Biçimler" subTitle="C# ile aşağıdaki biçimlerden de korumayı kaldırabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
