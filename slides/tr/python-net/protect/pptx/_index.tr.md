---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python ile PPTX Sunum Dosyalarını Koruma
url: /tr/python-net/protect/pptx/
description: Python ile PPTX sunumlarını şifreleyin veya yazma koruması ayarlayın.
keywords: PPTX yazma koruması, Python ile PPTX şifreleme, PPTX sunumunu kilitleme, Python ile PPTX koruma
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python ile PPTX Sunumlarını Koruma" h2="Aspose.Slides ile sunumları şifreleyen veya yazma koruması ayarlayan Python uygulamaları geliştirin." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python ile PPTX Sunumunu Koruma" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/tr/python-net/) iki ayrı koruma mekanizması sunar. Bir PPTX sunumunu şifrelemek ve açmak için parola istemek üzere `ProtectionManager.encrypt` çağırın. Alternatif olarak, dosyayı şifrelemeden değişiklikleri caydırmak için `ProtectionManager.set_write_protection` çağırın. Kullanıcı yazma korumalı bir sunumu yine de açabilir ve değişiklikleri başka bir dosyaya kaydedebilir.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX Sunumunu Şifreleme – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX Sunumuna Yazma Koruması Ayarlama – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python ile PPTX Nasıl Korunur" intro="Bir PPTX dosyasını korumak için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX dosyasını `Presentation` ile açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Açarken parola istemek için `ProtectionManager.encrypt`, değişiklikleri caydırmak için `ProtectionManager.set_write_protection` kullanın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Korunan sunumu `SaveFormat.PPTX` ile PPTX olarak kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides ile geliştirildi" title="PPTX Dosyalarını Çevrimiçi Parolayla Koruma" description="Ücretsiz Aspose.Slides Lock uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/tr/python-net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPTX dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Lock uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın sunumları nasıl koruduğunu görün.
- PPTX dosyanızı açmak veya düzenlemek için bir parola belirleyin.
- Korunan dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Koruma İçin Desteklenen Diğer Biçimler" subTitle="Desteklenen diğer sunum biçimlerini korumak için Python kullanın." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
