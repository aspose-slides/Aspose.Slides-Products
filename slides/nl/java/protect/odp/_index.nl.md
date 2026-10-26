---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ODP-presentatiebestanden beveiligen met Java
url: /nl/java/protect/odp/
description: Beveilig ODP-presentaties in Java. Gebruik Aspose.Slides for Java om presentatiebestanden te versleutelen en schrijfbeveiliging in te stellen.
keywords: Schrijfbeveiliging ODP, een ODP versleutelen, ODP-presentatie vergrendelen, ODP beveiligen
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP vergrendelen of met een wachtwoord beveiligen met Java" h2="Bouw Java-toepassingen die presentatiebestanden beveiligen met server-side API's." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Een ODP-presentatie beveiligen met Java" variant="code" %}}

Met [Aspose.Slides for Java](/slides/nl/java/) kunt u een ODP-presentatie met een wachtwoord beveiligen tegen openen of wijzigen. Gebruik het object `ProtectionManager` van de klasse `Presentation` om methoden als `encrypt` en `setWriteProtection` aan te roepen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Een ODP-presentatie versleutelen met Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Schrijfbeveiliging instellen voor een ODP-presentatie met Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="ODP met een wachtwoord beveiligen met Java" intro="Volg deze stappen om een ODP-presentatie te beveiligen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het ODP-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de methode `encrypt` of de methode `setWriteProtection` van het object `ProtectionManager` aan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla het beveiligde bestand op met `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Gebouwd met Aspose.Slides" title="ODP-bestanden online met een wachtwoord beveiligen" description="De gratis app Aspose.Slides Lock is gebouwd met [Aspose.Slides for Java](https://products.aspose.com/slides/nl/java/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen ODP-bestanden." button="Aspose.Slides Lock openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides presentaties beveiligt voordat u code schrijft.
- Stel een wachtwoord in om uw ODP-bestand te openen of te bewerken.
- Download het beveiligde bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor beveiliging" subTitle="Met Java kunt u ook de volgende formaten beveiligen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
