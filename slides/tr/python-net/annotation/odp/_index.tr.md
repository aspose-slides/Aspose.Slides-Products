---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Python ile ODP dosyasından yorumları kaldırma
url: /tr/python-net/annotation/odp/ 
description: Aspose.Slides for Python via .NET ile Python'da ODP sunumlarından yorumları ve yorum yazarlarını kaldırın.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python ile ODP dosyasından yorumları ve yorum yazarlarını kaldırma" h2="Sunum yorumlarını ve ilişkili yazarlarını kaldırmak için Aspose.Slides for Python via .NET kullanın." related="PPTX,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python ile ODP dosyasından yorumları kaldırma" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/tr/python-net/), bir ODP sunumunda saklanan yorumlara ve yorum yazarlarına erişim sağlar. Dosyayı `Presentation` ile yükleyin, her yazarın `comments` koleksiyonunu temizleyin, `comment_authors` koleksiyonunu temizleyin ve sonucu ODP biçiminde kaydedin.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python ile ODP dosyasından yorumları kaldırma" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python ile ODP dosyasından yorumlar nasıl kaldırılır" intro="Bir ODP sunumundan tüm yorumları ve yorum yazarlarını kaldırmak için bu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/) paketini yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP dosyasını `Presentation` ile açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`comment_authors` içinde dolaşın ve her yazarın `comments` koleksiyonunu temizleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`comment_authors` koleksiyonunu temizleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Güncellenen ODP sunumunu yazmak için `save` yöntemini `SaveFormat.ODP` ile çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides ile geliştirildi" title="ODP yorumlarını çevrimiçi kaldırma" description="Ücretsiz Aspose.Slides Annotation uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/tr/python-net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi ODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Annotation uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın yorumları nasıl kaldırdığını görün.
- ODP dosyanızdaki tüm yorumları kaldırın.
- Temizlenen dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Ek açıklamalar için desteklenen diğer biçimler" subTitle="Python ile diğer biçimlerden de ek açıklamaları kaldırabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
