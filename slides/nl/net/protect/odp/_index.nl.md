---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-presentatiebestanden beveiligen met .NET
url: /nl/net/protect/odp/
description: C#-broncode om ODP-presentaties met een wachtwoord te beveiligen.
keywords: ODP-schrijfbeveiliging, ODP versleutelen, ODP-presentatie vergrendelen, ODP beveiligen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP-bestanden vergrendelen of met een wachtwoord beveiligen met C#" h2="Bouw .NET-apps die presentaties versleutelen en wijzigingen beperken met server-side API's." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Een ODP-presentatie beveiligen met C#" variant="code" %}}

Met [Aspose.Slides for .NET](/slides/nl/net/) kunt u een ODP-presentatie versleutelen of het wijzigen ervan met een wachtwoord beperken. Voor het openen van een presentatie die met `ProtectionManager.Encrypt` is versleuteld, is het wachtwoord nodig. Gebruik `ProtectionManager.SetWriteProtection` om de presentatie te laten openen en tegelijk wijzigingen te beperken.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Een ODP-presentatie versleutelen met C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schrijfbeveiliging instellen voor een ODP-presentatie met C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Een ODP-presentatie met een wachtwoord beveiligen met C#" intro="Volg deze stappen om een ODP-presentatie met een wachtwoord te beveiligen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het ODP-bestand met `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Versleutel de presentatie met `ProtectionManager.Encrypt` of beperk wijzigingen met `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla het beveiligde bestand op met `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Gebouwd met Aspose.Slides" title="ODP-bestanden online met een wachtwoord beveiligen" description="De gratis app Aspose.Slides Lock is gebouwd met [Aspose.Slides for .NET](https://products.aspose.com/slides/nl/net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen ODP-bestanden." button="Aspose.Slides Lock openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides presentaties beveiligt voordat u code schrijft.
- Stel een wachtwoord in om uw ODP-bestand te openen of te bewerken.
- Download het beveiligde bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor beveiliging" subTitle="Met C# kunt u ook de volgende formaten beveiligen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
