---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python ile PPTM meta verilerini görüntüleme veya düzenleme
url: /tr/python-net/metadata/pptm/
description: Python ile PPTM dosyalarındaki yerleşik ve özel meta veri özelliklerini görüntüleyin ve düzenleyin.
keywords: PPTM meta verilerini düzenle, PPTM meta verilerini görüntüle, PPTM özelliklerini düzenle, PPTM özelliklerini görüntüle
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python ile PPTM meta verilerini görüntüleme ve düzenleme" h2="Aspose.Slides ile sunuların yerleşik ve özel özelliklerini okuyan ve değiştiren Python uygulamaları geliştirin." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python ile PPTM meta verilerini görüntüleme ve değiştirme" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/tr/python-net/), PPTM sunularında yerleşik meta verileri okumanıza ve güncellemenize, özel belge özelliklerini eklemenize, güncellemenize veya kaldırmanıza olanak tanır. `Presentation.document_properties` üzerinden bir [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/) nesnesine erişin, değiştirin ve sunuyu PPTM biçiminde kaydedin.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTM yerleşik özelliklerini güncelleme – Python" >}}
```python
with slides.Presentation("presentation.pptm") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.pptm", slides.export.SaveFormat.PPTM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTM özel özelliklerini ekleme ve kaldırma – Python" >}}
```python
with slides.Presentation("presentation.pptm") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.pptm", slides.export.SaveFormat.PPTM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python ile PPTM meta verileri nasıl düzenlenir" intro="Bir PPTM dosyasının meta verilerini düzenlemek için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTM dosyasını `Presentation` ile açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`IDocumentProperties` nesnesine `Presentation.document_properties` üzerinden erişin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Yerleşik özellikleri güncelleyin veya özel özellikler için `set_custom_property_value` ve `remove_custom_property` kullanın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sunuyu `Presentation.save` ve `SaveFormat.PPTM` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Aspose.Slides ile geliştirildi" title="PPTM meta verilerini çevrimiçi görüntüleyin ve düzenleyin" description="Ücretsiz Aspose.Slides Metadata uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/tr/python-net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPTM dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Metadata uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın özellikleri nasıl okuyup yazdığını görün.
- PPTM dosyanızın yerleşik ve özel özelliklerini görüntüleyin ve düzenleyin.
- Güncellenen dosyayı kaydedin ve indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen diğer meta veri biçimleri" subTitle="Python ile desteklenen diğer sunu biçimlerinin meta verilerini de yönetebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
