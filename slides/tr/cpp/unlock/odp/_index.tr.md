---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ ile ODP Sunumlarının Kilidini Açma
url: /tr/cpp/unlock/odp/
description: C++'ta ODP sunumlarının kilidini açın. Sunum dosyalarından şifrelemeyi ve yazma korumasını kaldırmak için Aspose.Slides for C++ kullanın.
keywords: ODP yazma korumasını kaldırma, ODP şifresini çözme, ODP sunumunun kilidini açma, ODP korumasını kaldırma
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ ile ODP Kilidini Açma" h2="Microsoft PowerPoint olmadan sunum dosyalarından şifrelemeyi ve yazma korumasını kaldırmak için Aspose.Slides for C++ kullanın." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ ile ODP Sunumundan Korumayı Kaldırma" variant="code" %}}

Aspose.Slides for C++, ODP sunumlarından şifrelemeyi veya yazma korumasını kaldırmanızı sağlar. Şifreli bir dosyayı açmak için `LoadOptions` kullanın, ardından `RemoveEncryption` veya `RemoveWriteProtection` çağırmak için `Presentation` sınıfındaki `ProtectionManager` nesnesini kullanın.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ ile ODP Dosyasından Parola Korumasını Kaldırma" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.odp", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ ile ODP Sunumundan Yazma Korumasını Kaldırma" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.odp");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ ile ODP Dosyasından Parola Nasıl Kaldırılır" intro="Bir ODP sunumundan korumayı kaldırmak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP dosyasını `Presentation` sınıfıyla, parola gerekiyorsa `LoadOptions` ile birlikte yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Korumayı kaldırmak için `ProtectionManager` nesnesini kullanın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Şifreli dosyalar için `RemoveEncryption`, yazma korumalı dosyalar için `RemoveWriteProtection` çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kilidi açılan dosyayı `SaveFormat::Odp` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Aspose.Slides ile geliştirildi" title="ODP Dosyalarının Kilidini Çevrimiçi Açma" description="Ücretsiz Aspose.Slides Unlock uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi ODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Unlock uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın korumayı nasıl kaldırdığını görün.
- ODP dosyanızdan parolayı veya yazma korumasını kaldırın.
- Kilidi açılan dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Kilit Açma İçin Desteklenen Diğer Biçimler" subTitle="C++ ile aşağıdaki biçimlerden de korumayı kaldırabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/cpp/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/cpp/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
