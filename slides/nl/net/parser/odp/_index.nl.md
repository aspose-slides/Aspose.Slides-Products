---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3070
title: Tekst uit ODP-bestanden extraheren met .NET
url: /nl/net/parser/odp/ 
description: C#-broncode om tekst uit ODP-bestanden te extraheren met .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP-bestanden parseren met C#" h2="Extraheer tekst en bekijk de tekstopmaak in ODP-bestanden met server-side .NET-API's."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ODP-bestand parseren met C#" %}}

Gebruik [Aspose.Slides for .NET](/slides/nl/net/) om tekst uit ODP-presentaties te extraheren. Installeer het pakket via [NuGet](https://www.nuget.org/packages/aspose.slides.net) of voer de volgende opdracht uit in de Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Opdracht" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP-bestanden parseren – C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="ODP-bestanden parseren in C#" intro="Eenvoudig documenten parseren met de API [Aspose.Slides for .NET](/slides/nl/net/) vraagt maar een paar regels code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het ODP-bestand met `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Haal de tekstkaders op met `SlideUtil.GetAllTextFrames`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Doorloop de tekstkaders, alinea's en tekstdelen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lees naar behoefte de eigenschappen `Text`, `FontHeight` en `LatinFont.FontName`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systeemvereisten" intro="U hebt een ondersteunde .NET-runtime en een pakketverwijzing naar Aspose.Slides for .NET nodig. U kunt Visual Studio of een andere compatibele C#-ontwikkelomgeving gebruiken." %}}

- .NET Framework, .NET, Mono of een Xamarin-compatibele omgeving
- Een C#-ontwikkelomgeving zoals Visual Studio
- Aspose.Slides for .NET, geïnstalleerd via NuGet

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Gebouwd met Aspose.Slides" title="Tekst en afbeeldingen online extraheren" description="De gratis app Aspose.Slides Parser is gebouwd met [Aspose.Slides for .NET](https://products.aspose.com/slides/nl/net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen ODP-bestanden." button="Aspose.Slides Parser openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Zie hoe Aspose.Slides uw bestanden leest voordat u code schrijft.
- Upload een ODP-bestand en krijg de tekst en afbeeldingen.
- Download alles als één ZIP-archief.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

ODP files use the OpenDocument Presentation format. A presentation contains slides with text, images, formatting, animations, and other media. Applications that support the OpenDocument format, such as OpenOffice and StarOffice, can open ODP files.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten om te parseren" subTitle="Met C# kunt u ook de volgende formaten parseren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/parser/ppt/" name="PPT" description="PowerPoint 97-2003-presentatie" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/parser/pptx/" name="PPTX" description="PowerPoint Open XML-presentatie" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
