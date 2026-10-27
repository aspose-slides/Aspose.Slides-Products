---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: OTP bekijken in C#
keywords: OTP bekijken, OTP openen, OTP-viewer, OTP, C# API, .NET-bibliotheek
weight: 6830
url: /nl/net/viewer/otp/ 
description: Bekijk OTP-bestanden in C#. Gebruik Aspose.Slides for .NET om presentatiebestanden te openen en als HTML op te slaan.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="OTP bekijken in C#" h2="C#-API voor het openen van OTP-bestanden en het opslaan ervan als responsieve HTML."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="OTP bekijken met Aspose.Slides" %}}

Gebruik voor het bekijken van OTP-bestanden de API [Aspose.Slides for .NET](https://products.aspose.com/slides/nl/net/), een krachtige, veelzijdige en gebruiksvriendelijke API voor C#. Open de pakketbeheerder [NuGet](https://www.nuget.org/packages/aspose.slides.net), zoek naar **Aspose.Slides** en installeer het pakket. U kunt ook de volgende opdracht uitvoeren in de Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Opdracht voor de Package Manager Console" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Met [**Aspose.Slides for .NET**](/slides/nl/net/) kunt u een OTP-bestand laden en met een paar regels code opslaan als responsieve HTML.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C#-code om OTP te bekijken" >}}
```cs
using var presentation = new Presentation("presentation.otp");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="OTP bekijken in C#: zo werkt het" intro="Met Aspose.Slides bekijken ontwikkelaars OTP-bestanden met slechts een paar regels code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer **Aspose.Slides for .NET**. Zie [**Installatie**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg de bibliotheek als referentie toe aan uw project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het `OTP`-bestand met de klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Maak een `ResponsiveHtmlController`-object voor responsieve HTML-uitvoer.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Maak een `HtmlOptions`-object en stel de eigenschap `HtmlFormatter` in.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla het OTP-bestand op als HTML met `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systeemvereisten" intro="Aspose.Slides for .NET ondersteunt alle gangbare besturingssystemen. Zorg dat u aan de volgende voorwaarden voldoet." %}}

- Microsoft Windows of een compatibel besturingssysteem met .NET Framework, .NET Core, Windows Azure, Mono of Xamarin
- Een ontwikkelomgeving zoals Microsoft Visual Studio
- Een verwijzing naar Aspose.Slides for .NET in uw project

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Gebouwd met Aspose.Slides" title="OTP-bestanden online bekijken" description="De gratis app Aspose.Slides Viewer is gebouwd met [Aspose.Slides for .NET](https://products.aspose.com/slides/nl/net/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen OTP-bestanden." button="Aspose.Slides Viewer openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Zie hoe Aspose.Slides uw bestanden weergeeft voordat u code schrijft.
- Upload uw OTP-bestand en bekijk de dia's direct.
- Werkt op desktop en mobiel, zonder PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="OTP" readMoreLink="https://docs.fileformat.com/presentation/otp/" %}}

Bestanden met de extensie `.OTP` zijn OpenDocument-presentatiesjablonen. Ze slaan herbruikbare indelingen, stijlen, opmaak, achtergronden en andere inhoud op om nieuwe presentaties met een consistent ontwerp te maken. OTP-bestanden kunnen worden gemaakt en geopend met toepassingen die OpenDocument Format (ODF) ondersteunen. Het formaat is vergelijkbaar met de Microsoft PowerPoint-sjabloonformaten POT en POTX.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere bestanden bekijken" subTitle="U kunt ook presentaties in andere formaten openen en bekijken." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/viewer/odp/" name="ODP" description="OpenDocument-presentatie" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/viewer/pot/" name="POT" description="PowerPoint 97-2003-sjabloon" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/viewer/potm/" name="POTM" description="PowerPoint-sjabloon met macro's" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/viewer/potx/" name="POTX" description="PowerPoint-sjabloon" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/viewer/pps/" name="PPS" description="PowerPoint 97-2003-diavoorstelling" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/viewer/ppsm/" name="PPSM" description="PowerPoint-diavoorstelling met macro's" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/viewer/ppsx/" name="PPSX" description="PowerPoint-diavoorstelling" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/viewer/ppt/" name="PPT" description="PowerPoint 97-2003-presentatie" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/viewer/pptm/" name="PPTM" description="PowerPoint-presentatie met macro's" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/viewer/pptx/" name="PPTX" description="PowerPoint-presentatie" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
