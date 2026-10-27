---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Visa PPS i C#
keywords: Visa PPS, Öppna PPS, PPS-visare, PPS, PowerPoint, C# API, .NET-bibliotek
weight: 7110
url: /sv/net/viewer/pps/ 
description: Visa PPS-filer i C#. Använd Aspose.Slides for .NET för att öppna presentationsfiler och spara dem som HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Visa PPS i C#" h2="C#-API för att öppna PPS-filer och spara dem som responsiv HTML."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Visa PPS med Aspose.Slides" %}}

Använd API:et [Aspose.Slides for .NET](https://products.aspose.com/slides/sv/net/) för att visa PPS-filer – ett kraftfullt, funktionsrikt och lättanvänt API för C#. Öppna pakethanteraren [NuGet](https://www.nuget.org/packages/aspose.slides.net), sök efter **Aspose.Slides** och installera paketet. Du kan också köra följande kommando i Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Kommando för Package Manager Console" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Med [**Aspose.Slides for .NET**](/slides/sv/net/) kan du läsa in en PPS-fil och spara den som responsiv HTML med några få rader kod.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C#-kod för att visa PPS" >}}
```cs
using var presentation = new Presentation("presentation.pps");

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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så visar du PPS i C#" intro="Med Aspose.Slides kan utvecklare visa PPS-filer med bara några få rader kod." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera **Aspose.Slides for .NET**. Se [**Installation**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till biblioteket som en referens i ditt projekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in `PPS`-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skapa ett `ResponsiveHtmlController`-objekt för responsiv HTML-utdata.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skapa ett `HtmlOptions`-objekt och ange egenskapen `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara PPS-filen som HTML med `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systemkrav" intro="Aspose.Slides for .NET stöder alla större operativsystem. Kontrollera att följande förutsättningar är uppfyllda." %}}

- Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin
- En utvecklingsmiljö som Microsoft Visual Studio
- En referens till Aspose.Slides for .NET i ditt projekt

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Byggd med Aspose.Slides" title="Visa PPS-filer online" description="Den kostnadsfria appen Aspose.Slides Viewer är byggd med [Aspose.Slides for .NET](https://products.aspose.com/slides/sv/net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPS-filer." button="Öppna Aspose.Slides Viewer" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides återger dina filer innan du skriver kod.
- Ladda upp din PPS-fil och visa dess bilder direkt.
- Fungerar på dator och mobil, utan PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPS" readMoreLink="https://docs.fileformat.com/presentation/pps/" %}}

PPS (PowerPoint-bildspel) är det binära bildspelsformat som används av PowerPoint 97–2003. PPSX är det nyare bildspelsformatet som bygger på standarden Office Open XML. Aktuella versioner av PowerPoint kan öppna PPS-filer och kan fortfarande spara presentationer i PPS-format. Vid normal öppning startar en PPS-fil i bildspelsläge, medan en PPT-fil öppnas i redigeringsläge.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Visa andra filer" subTitle="Du kan också öppna och visa presentationer i andra format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/odp/" name="ODP" description="OpenDocument-presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/otp/" name="OTP" description="OpenDocument-presentationsmall" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/pot/" name="POT" description="PowerPoint 97–2003-mall" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/potm/" name="POTM" description="PowerPoint-mall med makron" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/potx/" name="POTX" description="PowerPoint-mall" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/ppsm/" name="PPSM" description="PowerPoint-bildspel med makron" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/ppsx/" name="PPSX" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/ppt/" name="PPT" description="PowerPoint 97–2003-presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/pptm/" name="PPTM" description="PowerPoint-presentation med makron" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/pptx/" name="PPTX" description="PowerPoint-presentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
