---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python ile ODP Sunumlarının Kilidini Açma
url: /tr/python-net/unlock/odp/
description: Python ile ODP sunumlarından şifrelemeyi ve yazma korumasını kaldırın.
keywords: ODP kilidini açma, ODP dosyasından parola kaldırma, ODP şifrelemesini kaldırma, ODP yazma korumasını kaldırma
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python ile ODP Sunumlarının Kilidini Açma" h2="Aspose.Slides ile ODP sunumlarından açma parolalarını ve yazma koruması ayarlarını kaldıran Python uygulamaları geliştirin." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python ile ODP Dosyasından Şifrelemeyi ve Yazma Korumasını Kaldırma" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/tr/python-net/) ile bir ODP sunumunu açmak için parola gerektiren şifrelemeyi kaldırabilir veya yazma koruması ayarını temizleyebilirsiniz. Şifreli bir dosyayı açmak için geçerli parolayı `LoadOptions` aracılığıyla belirtin.

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP Sunumundan Şifrelemeyi Kaldırma – Python" >}}
```python
load_options = slides.LoadOptions()
load_options.password = "current_password"

with slides.Presentation("encrypted-presentation.odp", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("decrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP Sunumundan Yazma Korumasını Kaldırma – Python" >}}
```python
with slides.Presentation("write-protected-presentation.odp") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python ile ODP Dosyasından Koruma Nasıl Kaldırılır" intro="Bir ODP sunumundan korumayı kaldırmak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Şifreli bir ODP dosyası için geçerli parolayı `LoadOptions` içinde ayarlayın, ardından dosyayı `Presentation` ile açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Açma parolasını kaldırmak için `ProtectionManager.remove_encryption`, yazma korumasını temizlemek için `ProtectionManager.remove_write_protection` çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Elde edilen sunumu `SaveFormat.ODP` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Aspose.Slides ile geliştirildi" title="ODP Dosyalarının Kilidini Çevrimiçi Açma" description="Ücretsiz Aspose.Slides Unlock uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/tr/python-net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi ODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Unlock uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın korumayı nasıl kaldırdığını görün.
- ODP dosyanızdan parolayı veya yazma korumasını kaldırın.
- Kilidi açılan dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Kilit Açma İçin Desteklenen Diğer Biçimler" subTitle="Desteklenen diğer sunum biçimlerinden korumayı kaldırmak için Python kullanın." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
