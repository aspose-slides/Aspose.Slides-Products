---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3630
title: Ta bort PPT-anteckningar med Java
url: /sv/java/annotation/ppt/ 
description: Ta bort kommentarer och kommentarsförfattare från PPT-presentationer i Java med Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ta bort kommentarer och kommentarsförfattare från PPT i Java" h2="Använd Aspose.Slides for Java för att ta bort kommentarer och kommentarsförfattare från presentationsfiler." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ta bort kommentarer från PPT via Java" variant="code" %}}

Med Aspose.Slides for Java kan du ta bort kommentarer och kommentarsförfattare från PPT-presentationer. Läs in en fil med klassen `Presentation`, gå igenom `ICommentAuthor`-objekten från `getCommentAuthors`, rensa deras kommentarer och spara den uppdaterade presentationen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Radera anteckningar från PPT – Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så tar du bort kommentarer från PPT via Java" intro="Följ de här stegen för att ta bort kommentarer och kommentarsförfattare från en PPT-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera Aspose.Slides for Java. Se [Installation](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in PPT-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gå igenom `ICommentAuthor`-objekten från `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rensa varje författares kommentarer med `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töm samlingen med kommentarsförfattare och spara den uppdaterade PPT-filen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Byggd med Aspose.Slides" title="Ta bort PPT-kommentarer online" description="Den kostnadsfria appen Aspose.Slides Annotation är byggd med [Aspose.Slides for Java](https://products.aspose.com/slides/sv/java/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPT-filer." button="Öppna Aspose.Slides Annotation" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides tar bort kommentarer innan du skriver kod.
- Ta bort alla kommentarer från din PPT-fil.
- Ladda ned den rensade filen.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för anteckningar" subTitle="Med Java kan du även ta bort anteckningar från andra format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
