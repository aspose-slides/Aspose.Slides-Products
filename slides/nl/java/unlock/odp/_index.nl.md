---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-presentatiebestanden ontgrendelen met Java
url: /nl/java/unlock/odp/
description: Verwijder wachtwoorden en schrijfbeveiliging van ODP-presentaties in Java met Aspose.Slides for Java.
keywords: Schrijfbeveiliging ODP verwijderen, ODP ontsleutelen, ODP-presentatie ontgrendelen, beveiliging van ODP opheffen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP ontgrendelen met Java" h2="Bouw Java-toepassingen die wachtwoorden en schrijfbeveiliging van presentatiebestanden verwijderen met server-side API's." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Beveiliging van een ODP-presentatie verwijderen met Java" variant="code" %}}

Met [Aspose.Slides for Java](/slides/nl/java/) kunt u de versleuteling of schrijfbeveiliging van een ODP-presentatie verwijderen. Gebruik `LoadOptions.setPassword` om een versleutelde presentatie te openen en de `ProtectionManager`-methoden `removeEncryption` en `removeWriteProtection` om beveiligingsinstellingen te verwijderen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Wachtwoordbeveiliging van ODP verwijderen met Java" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.odp", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schrijfbeveiliging van een ODP-presentatie verwijderen met Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Een wachtwoord van ODP verwijderen met Java" intro="Volg deze stappen om de beveiliging van een ODP-presentatie te verwijderen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het ODP-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gebruik `LoadOptions.setPassword` als de presentatie versleuteld is.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep `removeEncryption` of `removeWriteProtection` van het object `ProtectionManager` aan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla de ontgrendelde presentatie op met `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Gebouwd met Aspose.Slides" title="ODP-bestanden online ontgrendelen" description="De gratis app Aspose.Slides Unlock is gebouwd met [Aspose.Slides for Java](https://products.aspose.com/slides/nl/java/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen ODP-bestanden." button="Aspose.Slides Unlock openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides beveiliging verwijdert voordat u code schrijft.
- Verwijder het wachtwoord of de schrijfbeveiliging uit uw ODP-bestand.
- Download het ontgrendelde bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor ontgrendelen" subTitle="Met Java kunt u ook de beveiliging van de volgende formaten verwijderen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
