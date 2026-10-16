---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer PPSX naar SVG via C#
weight: 1930
url: /nl/net/conversion/ppsx-to-svg/ 
description: Voorbeeldcode voor conversie van PPSX naar SVG C#. Gebruik API-voorbeeldcode voor batch-PPSX-bestanden naar SVG-conversie binnen VB.NET, Asp.NET of een op .NET gebaseerde toepassing.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer PPSX naar SVG via C#" h2="Exporteer PowerPoint® PPSX-bestanden naar SVG op .NET Framework, .NET Core, Windows Azure, Mono of Xamarin Platforms"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hoe PPSX naar SVG te converteren met C#" %}}

Om PPSX naar SVG te converteren, gebruiken we
 [Aspose.Slides voor .NET](https://products.aspose.com/slides/nl/net)
 API, een veelzijdige, krachtige en gebruiksvriendelijke API voor documentmanipulatie en -conversie voor het C#-platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 pakketbeheerder, zoek naar
 Aspose.Dia's
 en installeren. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Pakketbeheer Console-opdracht" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Deze voorbeeldcode toont PPSX naar SVG C#-conversie" >}}
```cs
using (Presentation pres = new Presentation("template.ppsx"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];

        using (FileStream fileStream = new FileStream($"slide-{index}.svg", FileMode.Create, FileAccess.Write))
        {
            slide.WriteAsSvg(fileStream);   
        }
    }
} 
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Stappen om PPSX naar SVG te converteren via C#" intro=".NET-ontwikkelaars kunnen PPSX-bestanden gemakkelijk laden en converteren naar SVG in slechts een paar regels code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad PPSX-bestand met een instantie van de klasse Presentatie{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de methode Opslaan aan terwijl u het pad van het uitvoerbestand & SaveFormat.Svg als parameters opgeeft{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}SVG-bestand wordt opgeslagen op het opgegeven pad{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="systeem vereisten" intro="Voordat u de broncode van het .NET-conversievoorbeeld uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet." %}}

- Microsoft Windows of een compatibel besturingssysteem met .NET Framework, .NET Core, Windows Azure, Mono of Xamarin Platforms.
- Ontwikkelomgeving zoals Microsoft Visual Studio.
- Aspose.Slides voor .NET DLL waarnaar in uw project wordt verwezen.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis app om PPSX te converteren naar SVG"
  description="[Probeer onze gratis Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde conversies" subTitle="U kunt PPSX ook converteren naar vele andere bestandsindelingen, waaronder enkele die hieronder worden vermeld." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Bitmap afbeelding" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="Verbeterde metabestandsindeling" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Grafisch uitwisselingsformaat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Hypertekst-opmaaktaal" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="JPEG-afbeelding" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument-presentatie-indeling" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Standaardformaat OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Draagbaar documentformaat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Draagbare netwerkgrafieken" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Microsoft PowerPoint-sjabloonbestanden" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Microsoft PowerPoint-sjabloonbestand" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="PowerPoint-diavoorstelling" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Diavoorstelling met macro's" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Presentatiebestand met macro's" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Open XML-presentatie-indeling" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="SWF-formaat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Gelabelde afbeeldingsindeling" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="XML-papierspecificaties" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
