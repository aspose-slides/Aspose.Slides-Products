---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-presentatiebestanden beveiligen met Python
url: /nl/python-net/protect/odp/
description: Versleutel ODP-presentaties of stel schrijfbeveiliging in met Python.
keywords: ODP-schrijfbeveiliging, ODP versleutelen met Python, ODP-presentatie vergrendelen, ODP beveiligen met Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP-presentaties beveiligen met Python" h2="Bouw Python-toepassingen die presentaties versleutelen of schrijfbeveiliging instellen met Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Een ODP-presentatie beveiligen met Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/nl/python-net/) biedt twee afzonderlijke beveiligingsmechanismen. Roep `ProtectionManager.encrypt` aan om een ODP-presentatie te versleutelen, zodat er een wachtwoord nodig is om die te openen. U kunt ook `ProtectionManager.set_write_protection` aanroepen om wijzigingen te ontmoedigen zonder het bestand te versleutelen. Een gebruiker kan een schrijfbeveiligde presentatie nog steeds openen en wijzigingen in een ander bestand opslaan.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Een ODP-presentatie versleutelen – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schrijfbeveiliging instellen voor een ODP-presentatie – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="ODP beveiligen met Python" intro="Volg deze stappen om een ODP-bestand te beveiligen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open het ODP-bestand met `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gebruik `ProtectionManager.encrypt` om een wachtwoord te vereisen bij het openen, of `ProtectionManager.set_write_protection` om wijzigingen te ontmoedigen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla de beveiligde presentatie op als ODP met `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Gebouwd met Aspose.Slides" title="ODP-bestanden online met een wachtwoord beveiligen" description="De gratis app Aspose.Slides Lock is gebouwd met [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/nl/python-net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen ODP-bestanden." button="Aspose.Slides Lock openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides presentaties beveiligt voordat u code schrijft.
- Stel een wachtwoord in om uw ODP-bestand te openen of te bewerken.
- Download het beveiligde bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor beveiliging" subTitle="Gebruik Python om andere ondersteunde presentatieformaten te beveiligen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
