---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-presentatiebestanden beveiligen met .NET
url: /nl/net/protect/pptx/
description: C#-broncode om PPTX-presentaties met een wachtwoord te beveiligen.
keywords: PPTX-schrijfbeveiliging, PPTX versleutelen, PPTX-presentatie vergrendelen, PPTX beveiligen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX-bestanden vergrendelen of met een wachtwoord beveiligen met C#" h2="Bouw .NET-apps die presentaties versleutelen en wijzigingen beperken met server-side API's." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Een PPTX-presentatie beveiligen met C#" variant="code" %}}

Met [Aspose.Slides for .NET](/slides/nl/net/) kunt u een PPTX-presentatie versleutelen of het wijzigen ervan met een wachtwoord beperken. Voor het openen van een presentatie die met `ProtectionManager.Encrypt` is versleuteld, is het wachtwoord nodig. Gebruik `ProtectionManager.SetWriteProtection` om de presentatie te laten openen en tegelijk wijzigingen te beperken.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Een PPTX-presentatie versleutelen met C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schrijfbeveiliging instellen voor een PPTX-presentatie met C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Een PPTX-presentatie met een wachtwoord beveiligen met C#" intro="Volg deze stappen om een PPTX-presentatie met een wachtwoord te beveiligen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het PPTX-bestand met `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Versleutel de presentatie met `ProtectionManager.Encrypt` of beperk wijzigingen met `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla het beveiligde bestand op met `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Gebouwd met Aspose.Slides" title="PPTX-bestanden online met een wachtwoord beveiligen" description="De gratis app Aspose.Slides Lock is gebouwd met [Aspose.Slides for .NET](https://products.aspose.com/slides/nl/net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPTX-bestanden." button="Aspose.Slides Lock openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides presentaties beveiligt voordat u code schrijft.
- Stel een wachtwoord in om uw PPTX-bestand te openen of te bewerken.
- Download het beveiligde bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor beveiliging" subTitle="Met C# kunt u ook de volgende formaten beveiligen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
