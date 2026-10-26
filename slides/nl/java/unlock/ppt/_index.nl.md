---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPT-presentatiebestanden ontgrendelen met Java
url: /nl/java/unlock/ppt/
description: Verwijder wachtwoorden en schrijfbeveiliging van PPT-presentaties in Java met Aspose.Slides for Java.
keywords: Schrijfbeveiliging PPT verwijderen, PPT ontsleutelen, PPT-presentatie ontgrendelen, beveiliging van PPT opheffen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPT ontgrendelen met Java" h2="Bouw Java-toepassingen die wachtwoorden en schrijfbeveiliging van presentatiebestanden verwijderen met server-side API's." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Beveiliging van een PPT-presentatie verwijderen met Java" variant="code" %}}

Met [Aspose.Slides for Java](/slides/nl/java/) kunt u de versleuteling of schrijfbeveiliging van een PPT-presentatie verwijderen. Gebruik `LoadOptions.setPassword` om een versleutelde presentatie te openen en de `ProtectionManager`-methoden `removeEncryption` en `removeWriteProtection` om beveiligingsinstellingen te verwijderen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Wachtwoordbeveiliging van PPT verwijderen met Java" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.ppt", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schrijfbeveiliging van een PPT-presentatie verwijderen met Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Een wachtwoord van PPT verwijderen met Java" intro="Volg deze stappen om de beveiliging van een PPT-presentatie te verwijderen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het PPT-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gebruik `LoadOptions.setPassword` als de presentatie versleuteld is.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep `removeEncryption` of `removeWriteProtection` van het object `ProtectionManager` aan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla de ontgrendelde presentatie op met `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Gebouwd met Aspose.Slides" title="PPT-bestanden online ontgrendelen" description="De gratis app Aspose.Slides Unlock is gebouwd met [Aspose.Slides for Java](https://products.aspose.com/slides/nl/java/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPT-bestanden." button="Aspose.Slides Unlock openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides beveiliging verwijdert voordat u code schrijft.
- Verwijder het wachtwoord of de schrijfbeveiliging uit uw PPT-bestand.
- Download het ontgrendelde bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor ontgrendelen" subTitle="Met Java kunt u ook de beveiliging van de volgende formaten verwijderen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
