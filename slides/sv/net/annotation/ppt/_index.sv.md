---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Ta bort PPT-anteckningar med .NET
url: /sv/net/annotation/ppt/ 
description: Ta bort kommentarer och kommentarsförfattare från PPT-presentationer i C#.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ta bort kommentarer och kommentarsförfattare från PPT i C#" h2="Bygg .NET-program som hanterar kommentarer och författare i presentationsfiler med API:er på serversidan." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ta bort kommentarer från PPT via C#" variant="code" %}}

Använd [Aspose.Slides for .NET](/slides/sv/net/) för att ta bort kommentarer och kommentarsförfattare från PPT-presentationsfiler. Exemplet nedan tömmer varje författares `Comments`-samling och sedan presentationens `CommentAuthors`-samling.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Radera anteckningar från PPT – C#" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så tar du bort kommentarer från PPT via C#" intro="Följ de här stegen för att ta bort kommentarer och kommentarsförfattare från en PPT-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera Aspose.Slides for .NET. Se [Installation](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in PPT-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gå igenom samlingen `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töm `Comments`-samlingen för varje kommentarsförfattare.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töm samlingen `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den uppdaterade presentationen med `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Byggd med Aspose.Slides" title="Ta bort PPT-kommentarer online" description="Den kostnadsfria appen Aspose.Slides Annotation är byggd med [Aspose.Slides for .NET](https://products.aspose.com/slides/sv/net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPT-filer." button="Öppna Aspose.Slides Annotation" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides tar bort kommentarer innan du skriver kod.
- Ta bort alla kommentarer från din PPT-fil.
- Ladda ned den rensade filen.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för anteckningar" subTitle="Med C# kan du även ta bort anteckningar från andra format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
