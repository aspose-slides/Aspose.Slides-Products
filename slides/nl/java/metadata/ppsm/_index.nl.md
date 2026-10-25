---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Metadata van PPSM-bestanden bekijken of bewerken met Java
url: /nl/java/metadata/ppsm/
description: Bekijk en bewerk PPSM-metadata in Java. Gebruik Aspose.Slides for Java om ingebouwde en aangepaste presentatie-eigenschappen bij te werken.
keywords: PPSM-metadata bewerken, PPSM-metadata bekijken, PPSM-eigenschappen bewerken, PPSM-eigenschappen bekijken
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPSM-eigenschappen bewerken met Java" h2="Bouw Java-toepassingen die ingebouwde en aangepaste eigenschappen in presentatiebestanden wijzigen met server-side API's." related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPSM-eigenschappen wijzigen via Java" variant="code" %}}

Met [Aspose.Slides for Java](/slides/nl/java/) kunnen ontwikkelaars ingebouwde en aangepaste presentatie-eigenschappen openen en wijzigen. Gebruik de methode `getDocumentProperties` van een `Presentation`-object om het `IDocumentProperties`-object van het presentatiebestand te openen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ingebouwde PPSM-eigenschappen wijzigen – Java" >}}
```java
Presentation presentation = new Presentation("Presentation.ppsm");
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.setAuthor("Aspose.Slides for Java");
    documentProperties.setTitle("Modifying Presentation Properties");
    documentProperties.setSubject("Aspose Subject");
    documentProperties.setComments("Aspose Description");
    documentProperties.setManager("Aspose Manager");

    presentation.save("DocProps.ppsm", SaveFormat.Ppsm);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Aangepaste eigenschappen toevoegen aan PPSM – Java" >}}
```java
Presentation presentation = new Presentation();
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.set_Item("New Custom", 12);
    documentProperties.set_Item("My Name", "Aspose Metadata Editor");
    documentProperties.set_Item("Custom", 124);

    String customPropertyName = documentProperties.getCustomPropertyName(2);
    documentProperties.removeCustomProperty(customPropertyName);

    presentation.save("CustomDemo.ppsm", SaveFormat.Ppsm);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPSM-metadata bekijken of bewerken in Java" intro="Volg deze stappen om PPSM-metadata te bekijken of te bewerken." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het `PPSM`-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de methode `getDocumentProperties` aan om het `IDocumentProperties`-object op te halen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lees of wijzig ingebouwde eigenschappen zoals `Author`, `Title`, `Subject` en `Comments`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open en wijzig aangepaste eigenschappen met `set_Item`, `getCustomPropertyName` en `removeCustomProperty`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Gebouwd met Aspose.Slides" title="PPSM-metadata online bekijken en bewerken" description="De gratis app Aspose.Slides Metadata is gebouwd met [Aspose.Slides for Java](https://products.aspose.com/slides/nl/java/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPSM-bestanden." button="Aspose.Slides Metadata openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Zie hoe Aspose.Slides eigenschappen leest en schrijft voordat u code schrijft.
- Bekijk en bewerk de ingebouwde en aangepaste eigenschappen van uw PPSM-bestand.
- Sla het bijgewerkte bestand op en download het.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde metadataformaten" subTitle="Met Java kunt u ook de metadata van de volgende formaten beheren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
