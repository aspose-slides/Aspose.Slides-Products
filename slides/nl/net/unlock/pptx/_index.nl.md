---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX-presentatiebestanden ontgrendelen met .NET
url: /nl/net/unlock/pptx/
description: C#-broncode om de wachtwoordbeveiliging van PPTX-presentaties te verwijderen.
keywords: PPTX-schrijfbeveiliging verwijderen, PPTX ontsleutelen, PPTX-presentatie ontgrendelen, beveiliging van PPTX opheffen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX-bestanden ontgrendelen met C#" h2="Bouw .NET-apps die versleuteling en schrijfbeveiliging van presentaties verwijderen met server-side API's." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Beveiliging van een PPTX-presentatie verwijderen met C#" variant="code" %}}

Met [Aspose.Slides for .NET](/slides/nl/net/) kunt u de versleuteling of schrijfbeveiliging van een PPTX-presentatie verwijderen. Om de versleuteling te verwijderen, laadt u de presentatie met het juiste wachtwoord en roept u `ProtectionManager.RemoveEncryption` aan. Om de schrijfbeveiliging te verwijderen, roept u `ProtectionManager.RemoveWriteProtection` aan.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Versleuteling van een PPTX-presentatie verwijderen met C#" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.pptx", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schrijfbeveiliging van een PPTX-presentatie verwijderen met C#" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.pptx");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="De beveiliging van een PPTX-presentatie verwijderen met C#" intro="Volg deze stappen om de beveiliging van een PPTX-presentatie te verwijderen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het PPTX-bestand met `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Geef bij een versleuteld bestand vóór het laden het wachtwoord op via `LoadOptions.Password`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep `ProtectionManager.RemoveEncryption` of `ProtectionManager.RemoveWriteProtection` aan, afhankelijk van de toegepaste beveiliging.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla de ontgrendelde presentatie op met `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Gebouwd met Aspose.Slides" title="PPTX-bestanden online ontgrendelen" description="De gratis app Aspose.Slides Unlock is gebouwd met [Aspose.Slides for .NET](https://products.aspose.com/slides/nl/net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPTX-bestanden." button="Aspose.Slides Unlock openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides beveiliging verwijdert voordat u code schrijft.
- Verwijder het wachtwoord of de schrijfbeveiliging uit uw PPTX-bestand.
- Download het ontgrendelde bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor ontgrendelen" subTitle="Met C# kunt u ook de beveiliging van de volgende formaten verwijderen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
