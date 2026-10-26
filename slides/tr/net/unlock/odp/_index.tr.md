---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET ile ODP Sunum Dosyalarının Kilidini Açma
url: /tr/net/unlock/odp/
description: ODP sunumlarından parola korumasını kaldırmak için C# kaynak kodu.
keywords: ODP yazma korumasını kaldırma, ODP şifresini çözme, ODP sunumunun kilidini açma, ODP korumasını kaldırma
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# ile ODP Dosyalarının Kilidini Açma" h2="Sunucu tarafı API'lerle sunumlardan şifrelemeyi ve yazma korumasını kaldıran .NET uygulamaları geliştirin." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# ile ODP Sunumundan Korumayı Kaldırma" variant="code" %}}

[Aspose.Slides for .NET](/slides/tr/net/) ile bir ODP sunumundan şifrelemeyi veya yazma korumasını kaldırabilirsiniz. Şifrelemeyi kaldırmak için sunumu doğru parolayla yükleyin ve `ProtectionManager.RemoveEncryption` çağırın. Yazma korumasını kaldırmak için `ProtectionManager.RemoveWriteProtection` çağırın.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# ile ODP Sunumundan Şifrelemeyi Kaldırma" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.odp", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C# ile ODP Sunumundan Yazma Korumasını Kaldırma" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.odp");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# ile ODP Sunumundan Koruma Nasıl Kaldırılır" intro="Bir ODP sunumundan korumayı kaldırmak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP dosyasını `Presentation` ile yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Şifreli bir dosya için, yüklemeden önce parolayı `LoadOptions.Password` aracılığıyla belirtin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uygulanan korumaya göre `ProtectionManager.RemoveEncryption` veya `ProtectionManager.RemoveWriteProtection` çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kilidi açılan sunumu `SaveFormat.Odp` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Aspose.Slides ile geliştirildi" title="ODP Dosyalarının Kilidini Çevrimiçi Açma" description="Ücretsiz Aspose.Slides Unlock uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi ODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Unlock uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın korumayı nasıl kaldırdığını görün.
- ODP dosyanızdan parolayı veya yazma korumasını kaldırın.
- Kilidi açılan dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Kilit Açma İçin Desteklenen Diğer Biçimler" subTitle="C# ile aşağıdaki biçimlerden de korumayı kaldırabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
