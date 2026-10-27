---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Ta bort ODP-anteckningar med .NET
url: /sv/net/annotation/odp/ 
description: Ta bort kommentarer och kommentarsförfattare från ODP-presentationer i C#.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ta bort kommentarer och kommentarsförfattare från ODP i C#" h2="Bygg .NET-program som hanterar kommentarer och författare i presentationsfiler med API:er på serversidan." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ta bort kommentarer från ODP via C#" variant="code" %}}

Använd [Aspose.Slides for .NET](/slides/sv/net/) för att ta bort kommentarer och kommentarsförfattare från ODP-presentationsfiler. Exemplet nedan tömmer varje författares `Comments`-samling och sedan presentationens `CommentAuthors`-samling.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Radera anteckningar från ODP – C#" >}}
```cs
using var presentation = new Presentation("example.odp");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så tar du bort kommentarer från ODP via C#" intro="Följ de här stegen för att ta bort kommentarer och kommentarsförfattare från en ODP-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera Aspose.Slides for .NET. Se [Installation](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in ODP-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gå igenom samlingen `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töm `Comments`-samlingen för varje kommentarsförfattare.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töm samlingen `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den uppdaterade presentationen med `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Byggd med Aspose.Slides" title="Ta bort ODP-kommentarer online" description="Den kostnadsfria appen Aspose.Slides Annotation är byggd med [Aspose.Slides for .NET](https://products.aspose.com/slides/sv/net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna ODP-filer." button="Öppna Aspose.Slides Annotation" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides tar bort kommentarer innan du skriver kod.
- Ta bort alla kommentarer från din ODP-fil.
- Ladda ned den rensade filen.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för anteckningar" subTitle="Med C# kan du även ta bort anteckningar från andra format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/net/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
