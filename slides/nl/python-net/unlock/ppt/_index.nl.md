---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPT-presentaties ontgrendelen met Python
url: /nl/python-net/unlock/ppt/
description: Verwijder versleuteling en schrijfbeveiliging van PPT-presentaties met Python.
keywords: PPT ontgrendelen, wachtwoord van PPT verwijderen, PPT-versleuteling verwijderen, schrijfbeveiliging van PPT verwijderen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPT-presentaties ontgrendelen met Python" h2="Bouw Python-toepassingen die openingswachtwoorden en schrijfbeveiliging van PPT-presentaties verwijderen met Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Versleuteling en schrijfbeveiliging van PPT verwijderen met Python" variant="code" %}}

Met [Aspose.Slides for Python via .NET](/slides/nl/python-net/) kunt u de versleuteling verwijderen waardoor een wachtwoord nodig is om een PPT-presentatie te openen, of de schrijfbeveiliging ervan opheffen. Geef het huidige wachtwoord op via `LoadOptions` om een versleuteld bestand te openen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Versleuteling van een PPT-presentatie verwijderen – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.ppt", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schrijfbeveiliging van een PPT-presentatie verwijderen – Python" >}}
```py
with slides.Presentation("write-protected-presentation.ppt") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Beveiliging van PPT verwijderen met Python" intro="Volg deze stappen om de beveiliging van een PPT-presentatie te verwijderen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Stel bij een versleuteld PPT-bestand het huidige wachtwoord in `LoadOptions` in en open het bestand vervolgens met `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep `ProtectionManager.remove_encryption` aan om het openingswachtwoord te verwijderen, of `ProtectionManager.remove_write_protection` om de schrijfbeveiliging op te heffen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla de resulterende presentatie op met `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Gebouwd met Aspose.Slides" title="PPT-bestanden online ontgrendelen" description="De gratis app Aspose.Slides Unlock is gebouwd met [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/nl/python-net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPT-bestanden." button="Aspose.Slides Unlock openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides beveiliging verwijdert voordat u code schrijft.
- Verwijder het wachtwoord of de schrijfbeveiliging uit uw PPT-bestand.
- Download het ontgrendelde bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor ontgrendelen" subTitle="Gebruik Python om de beveiliging van andere ondersteunde presentatieformaten te verwijderen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
