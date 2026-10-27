---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Visa POTM i C#
keywords: Visa POTM, Öppna POTM, POTM-visare, POTM, PowerPoint, C# API, .NET-bibliotek
weight: 3310
url: /sv/net/viewer/potm/ 
description: Visa POTM-filer i C#. Använd Aspose.Slides for .NET för att öppna presentationsfiler och spara dem som HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Visa POTM i C#" h2="C#-API för att öppna POTM-filer och spara dem som responsiv HTML."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Visa POTM med Aspose.Slides" %}}

Använd API:et [Aspose.Slides for .NET](https://products.aspose.com/slides/sv/net/) för att visa POTM-filer – ett kraftfullt, funktionsrikt och lättanvänt API för C#. Öppna pakethanteraren [NuGet](https://www.nuget.org/packages/aspose.slides.net), sök efter **Aspose.Slides** och installera paketet. Du kan också köra följande kommando i Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Kommando för Package Manager Console" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Med [**Aspose.Slides for .NET**](/slides/sv/net/) kan du läsa in en POTM-fil och spara den som responsiv HTML med några få rader kod.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C#-kod för att visa POTM" >}}
```cs
using var presentation = new Presentation("presentation.potm");

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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så visar du POTM i C#" intro="Med Aspose.Slides kan utvecklare visa POTM-filer med bara några få rader kod." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera **Aspose.Slides for .NET**. Se [**Installation**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till biblioteket som en referens i ditt projekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in `POTM`-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skapa ett `ResponsiveHtmlController`-objekt för responsiv HTML-utdata.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skapa ett `HtmlOptions`-objekt och ange egenskapen `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara POTM-filen som HTML med `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systemkrav" intro="Aspose.Slides for .NET stöder alla större operativsystem. Kontrollera att följande förutsättningar är uppfyllda." %}}

- Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin
- En utvecklingsmiljö som Microsoft Visual Studio
- En referens till Aspose.Slides for .NET i ditt projekt

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Byggd med Aspose.Slides" title="Visa POTM-filer online" description="Den kostnadsfria appen Aspose.Slides Viewer är byggd med [Aspose.Slides for .NET](https://products.aspose.com/slides/sv/net/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna POTM-filer." button="Öppna Aspose.Slides Viewer" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides återger dina filer innan du skriver kod.
- Ladda upp din POTM-fil och visa dess bilder direkt.
- Fungerar på dator och mobil, utan PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTM" readMoreLink="https://docs.fileformat.com/presentation/potm/" %}}

Filer med filändelsen `.POTM` är Microsoft PowerPoint-mallar med stöd för makron som introducerades med PowerPoint 2007. De kan lagra återanvändbara presentationsinställningar som layouter, format, bakgrunder, färgpaletter, teckensnitt, standardformatering och VBA-makron. PowerPoint 2007 och senare kan öppna och redigera POTM-filer.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Visa andra filer" subTitle="Du kan också öppna och visa presentationer i andra format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/odp/" name="ODP" description="OpenDocument-presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/otp/" name="OTP" description="OpenDocument-presentationsmall" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/pot/" name="POT" description="PowerPoint 97–2003-mall" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/potx/" name="POTX" description="PowerPoint-mall" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/pps/" name="PPS" description="PowerPoint 97–2003-bildspel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/ppsm/" name="PPSM" description="PowerPoint-bildspel med makron" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/ppsx/" name="PPSX" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/ppt/" name="PPT" description="PowerPoint 97–2003-presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/pptm/" name="PPTM" description="PowerPoint-presentation med makron" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/viewer/pptx/" name="PPTX" description="PowerPoint-presentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
