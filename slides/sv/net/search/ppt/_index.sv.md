---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Sök efter text i PPT-presentationsfiler med .NET
url: /sv/net/search/ppt/
description: C#-källkod för att söka efter text i PPT-presentationer.
keywords: Sök efter text i PPT, hitta text i PPT, sök i PPT-presentationstext
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Sök efter text i PPT-filer med C#" h2="Bygg .NET-appar som hittar text i presentationer med API:er på serversidan." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sök efter text i en PPT-presentation med C#" variant="code" %}}

Med [Aspose.Slides for .NET](/slides/sv/net/) kan du söka efter text i en PPT-presentation. Hämta textramarna på en bild med `SlideUtil.GetAllTextBoxes` och kontrollera sedan om deras `Text`-värden innehåller den önskade frasen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Sök efter text i en PPT-presentation med C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så söker du efter text i en PPT-presentation med C#" intro="Följ de här stegen för att söka efter text i en PPT-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in PPT-filen med `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hämta den önskade bilden från `Presentation.Slides` och tilldela den till en variabel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hämta bildens textramar med [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kontrollera om `Text`-värdet för varje ram innehåller den önskade frasen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Byggd med Aspose.Slides" title="Sök efter text i PPT-filer online" description="Den kostnadsfria appen Aspose.Slides Search är byggd med [Aspose.Slides for .NET](https://products.aspose.com/slides/sv/net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPT-filer." button="Öppna Aspose.Slides Search" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides hittar text innan du skriver kod.
- Sök efter vanlig text eller reguljära uttryck i din PPT-fil.
- Ladda ned träffarna som en textfil.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för sökning" subTitle="Med C# kan du även söka efter text i följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
