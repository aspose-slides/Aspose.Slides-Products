---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: PPT-aantekeningen verwijderen met .NET
url: /nl/net/annotation/ppt/ 
description: Verwijder opmerkingen en opmerkingauteurs uit PPT-presentaties in C#.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Opmerkingen en opmerkingauteurs verwijderen uit PPT in C#" h2="Bouw .NET-toepassingen die opmerkingen en auteurs in presentatiebestanden bewerken met server-side API's." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Opmerkingen verwijderen uit PPT via C#" variant="code" %}}

Gebruik [Aspose.Slides for .NET](/slides/nl/net/) om opmerkingen en opmerkingauteurs uit PPT-presentatiebestanden te verwijderen. Het onderstaande voorbeeld maakt de `Comments`-verzameling van elke auteur leeg en daarna de `CommentAuthors`-verzameling van de presentatie.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Aantekeningen verwijderen uit PPT – C#" >}}
```cs
using var presentation = new Presentation("example.ppt");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Opmerkingen verwijderen uit PPT via C# – zo werkt het" intro="Volg deze stappen om opmerkingen en opmerkingauteurs uit een PPT-presentatie te verwijderen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer Aspose.Slides for .NET. Zie [Installatie](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het PPT-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Doorloop de verzameling `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Maak de `Comments`-verzameling van elke opmerkingauteur leeg.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Maak de verzameling `CommentAuthors` leeg.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla de bijgewerkte presentatie op met `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Gebouwd met Aspose.Slides" title="PPT-opmerkingen online verwijderen" description="De gratis app Aspose.Slides Annotation is gebouwd met [Aspose.Slides for .NET](https://products.aspose.com/slides/nl/net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPT-bestanden." button="Aspose.Slides Annotation openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides opmerkingen verwijdert voordat u code schrijft.
- Verwijder alle opmerkingen uit uw PPT-bestand.
- Download het opgeschoonde bestand.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor aantekeningen" subTitle="Met C# kunt u ook aantekeningen uit andere formaten verwijderen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
