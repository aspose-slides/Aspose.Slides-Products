---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tekst zoeken in ODP-presentatiebestanden met .NET
url: /nl/net/search/odp/
description: C#-broncode om tekst in ODP-presentaties te zoeken.
keywords: Tekst zoeken in ODP, tekst vinden in ODP, tekst in ODP-presentatie zoeken
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tekst zoeken in ODP-bestanden met C#" h2="Bouw .NET-apps die tekst in presentaties vinden met server-side API's." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tekst zoeken in een ODP-presentatie met C#" variant="code" %}}

Met [Aspose.Slides for .NET](/slides/nl/net/) kunt u tekst zoeken in een ODP-presentatie. Haal de tekstkaders van een dia op met `SlideUtil.GetAllTextBoxes` en controleer daarna hun `Text`-waarden op de gewenste zin.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tekst zoeken in een ODP-presentatie met C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Tekst zoeken in een ODP-presentatie met C# – zo werkt het" intro="Volg deze stappen om tekst in een ODP-presentatie te zoeken." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het ODP-bestand met `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Haal de gewenste dia op uit `Presentation.Slides` en wijs deze toe aan een variabele.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Haal de tekstkaders ervan op met [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Controleer of de `Text`-waarde van elk kader de gewenste zin bevat.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Gebouwd met Aspose.Slides" title="Tekst zoeken in ODP-bestanden online" description="De gratis app Aspose.Slides Search is gebouwd met [Aspose.Slides for .NET](https://products.aspose.com/slides/nl/net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen ODP-bestanden." button="Aspose.Slides Search openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides tekst vindt voordat u code schrijft.
- Doorzoek uw ODP-bestand op gewone tekst of reguliere expressies.
- Download de resultaten als tekstbestand.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten voor zoeken" subTitle="Met C# kunt u ook tekst zoeken in de volgende formaten." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
