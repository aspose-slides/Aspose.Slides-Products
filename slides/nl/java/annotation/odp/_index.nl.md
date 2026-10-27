---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1790
title: ODP-aantekeningen verwijderen met Java
url: /nl/java/annotation/odp/ 
description: Verwijder opmerkingen en opmerkingauteurs uit ODP-presentaties in Java met Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Opmerkingen en opmerkingauteurs verwijderen uit ODP in Java" h2="Gebruik Aspose.Slides for Java om opmerkingen en opmerkingauteurs uit presentatiebestanden te verwijderen." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Opmerkingen verwijderen uit ODP via Java" variant="code" %}}

Met Aspose.Slides for Java verwijdert u opmerkingen en opmerkingauteurs uit ODP-presentaties. Laad een bestand met de klasse `Presentation`, doorloop de `ICommentAuthor`-objecten uit `getCommentAuthors`, wis hun opmerkingen en sla de bijgewerkte presentatie op.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Aantekeningen verwijderen uit ODP – Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Opmerkingen verwijderen uit ODP via Java – zo werkt het" intro="Volg deze stappen om opmerkingen en opmerkingauteurs uit een ODP-presentatie te verwijderen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer Aspose.Slides for Java. Zie [Installatie](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het ODP-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Doorloop de `ICommentAuthor`-objecten uit `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wis de opmerkingen van elke auteur met `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Maak de verzameling opmerkingauteurs leeg en sla het bijgewerkte ODP-bestand op.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Gebouwd met Aspose.Slides" title="ODP-opmerkingen online verwijderen" description="De gratis app Aspose.Slides Annotation is gebouwd met [Aspose.Slides for Java](https://products.aspose.com/slides/nl/java/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen ODP-bestanden." button="Aspose.Slides Annotation openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides opmerkingen verwijdert voordat u code schrijft.
- Verwijder alle opmerkingen uit uw ODP-bestand.
- Download het opgeschoonde bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor aantekeningen" subTitle="Met Java kunt u ook aantekeningen uit andere formaten verwijderen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
