---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 70
title: Tekst uit PPT-bestanden extraheren met .NET
url: /nl/net/parser/ppt/ 
description: C#-broncode om tekst uit PPT-bestanden te extraheren met .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPT-bestanden parseren met C#" h2="Extraheer tekst en bekijk de tekstopmaak in PPT-bestanden met server-side .NET-API's."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPT-bestand parseren met C#" %}}

Gebruik [Aspose.Slides for .NET](/slides/nl/net/) om tekst uit PPT-presentaties te extraheren. Installeer het pakket via [NuGet](https://www.nuget.org/packages/aspose.slides.net) of voer de volgende opdracht uit in de Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Opdracht" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT-bestanden parseren – C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPT-bestanden parseren in C#" intro="Eenvoudig documenten parseren met de API [Aspose.Slides for .NET](/slides/nl/net/) vraagt maar een paar regels code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het PPT-bestand met `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Gebouwd met Aspose.Slides" title="Tekst en afbeeldingen online extraheren" description="De gratis app Aspose.Slides Parser is gebouwd met [Aspose.Slides for .NET](https://products.aspose.com/slides/nl/net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPT-bestanden." button="Aspose.Slides Parser openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Zie hoe Aspose.Slides uw bestanden leest voordat u code schrijft.
- Upload een PPT-bestand en krijg de tekst en afbeeldingen.
- Download alles als één ZIP-archief.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

Een PPT-bestand is een Microsoft PowerPoint 97-2003-presentatie in het binaire bestandsformaat. Het bevat dia's met tekst, opsommingen, afbeeldingen, multimedia en ingesloten OLE-objecten. Nieuwere PowerPoint-versies gebruiken het op Office Open XML gebaseerde PPTX-formaat. Ook toepassingen zoals OpenOffice Impress en Apple Keynote kunnen PPT-bestanden maken.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde formaten om te parseren" subTitle="Met C# kunt u ook de volgende formaten parseren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/parser/odp/" name="ODP" description="OpenDocument-presentatie" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/nl/net/parser/pptx/" name="PPTX" description="PowerPoint Open XML-presentatie" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
