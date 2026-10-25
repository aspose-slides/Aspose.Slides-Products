---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Zobrazení a úprava metadat POTM v Pythonu
url: /cs/python-net/metadata/potm/
description: Zobrazujte a upravujte vestavěné i vlastní vlastnosti metadat v souborech POTM v Pythonu.
keywords: úprava metadat POTM, zobrazení metadat POTM, úprava vlastností POTM, zobrazení vlastností POTM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Zobrazení a úprava metadat POTM v Pythonu – příklad" h2="Vytvářejte aplikace v Pythonu, které pomocí Aspose.Slides čtou a mění vestavěné i vlastní vlastnosti prezentací." related="FODP,ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Zobrazení a změna metadat POTM v Pythonu" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/cs/python-net/) umožňuje číst a aktualizovat vestavěná metadata a přidávat, aktualizovat či odebírat vlastní vlastnosti dokumentu v prezentacích POTM. Přes `Presentation.document_properties` získejte objekt [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/), upravte jej a uložte prezentaci ve formátu POTM.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Aktualizace vestavěných vlastností POTM – Python" >}}
```python
with slides.Presentation("presentation.potm") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.potm", slides.export.SaveFormat.POTM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Přidání a odebrání vlastních vlastností POTM – Python" >}}
```python
with slides.Presentation("presentation.potm") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.potm", slides.export.SaveFormat.POTM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak upravit metadata POTM v Pythonu" intro="Pomocí těchto kroků upravíte metadata souboru POTM." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete soubor POTM pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Získejte jeho objekt `IDocumentProperties` přes `Presentation.document_properties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aktualizujte vestavěné vlastnosti nebo pro vlastní vlastnosti použijte `set_custom_property_value` a `remove_custom_property`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte prezentaci pomocí `Presentation.save` a `SaveFormat.POTM`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Vytvořeno pomocí Aspose.Slides" title="Zobrazení a úprava metadat POTM online" description="Bezplatná aplikace Aspose.Slides Metadata je vytvořena pomocí [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/cs/python-net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory POTM." button="Otevřít Aspose.Slides Metadata" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides čte a zapisuje vlastnosti, ještě než napíšete kód.
- Zobrazte a upravte vestavěné i vlastní vlastnosti svého souboru POTM.
- Uložte a stáhněte aktualizovaný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty metadat" subTitle="V Pythonu můžete spravovat také metadata dalších podporovaných formátů prezentací." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
