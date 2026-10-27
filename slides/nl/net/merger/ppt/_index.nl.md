---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPT-bestanden samenvoegen via .NET
weight: 7610
url: /nl/net/merger/ppt/ 
description: C#-broncode om PPT-documenten te combineren op .NET Framework, .NET Core, Windows Azure, Mono of Xamarin Platforms.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPT-indelingen samenvoegen in C#" h2="Native en hoogwaardige PPT-documentfusie met Aspose.Slides aan de serverzijde voor .NET API's, zonder het gebruik van software zoals Microsoft of Open Office, Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hoe PPT-bestand samen te voegen met behulp van C#" %}}

Om het PPT-bestand samen te voegen, gebruiken we
 [Aspose.Slides voor .NET](https://products.aspose.com/slides/nl/net)
 API, een veelzijdige, krachtige en gebruiksvriendelijke API voor documentmanipulatie en samenvoeging voor het C#-platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 pakketbeheerder, zoek naar
 **Aspose.Dia's**
 en installeren. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Opdracht" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT-bestanden samenvoegen - C#" >}}
```cs
var ps1 = new Presentation("presen1.ppt");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first PPT presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Stappen voor het samenvoegen van PPT-bestanden in C#" intro="Een basisdocument dat kan worden samengevoegd en samengevoegd met [Aspose.Slides for .NET](https://products.aspose.com/slides/nl/net) API's kan worden gedaan met slechts enkele regels code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad alle PPT-bestanden met het volledige pad.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Maak één document als basisbestand{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de relevante methode aan om bestanden één voor één samen te voegen en samen te voegen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Roep de methode Save() aan en geef de bestandsnaam (volledig pad) en formaat (PPT) door als parameter.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nu kunt u het PPT-bestand openen en gebruiken in Microsoft Office, Adobe PDF of een ander compatibel programma.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="systeem vereisten" intro="Onze API's worden ondersteund op alle belangrijke platforms en besturingssystemen. Voordat u de onderstaande code uitvoert, moet u ervoor zorgen dat u de volgende vereisten op uw systeem hebt." %}}

- Microsoft Windows of een compatibel besturingssysteem met .NET Framework, .NET Core, Windows Azure, Mono of Xamarin Platforms
- Ontwikkelomgeving zoals Microsoft Visual Studio
- Aspose.Slides voor .NET DLL waarnaar in uw project wordt verwezen - Installeer vanaf NuGet met behulp van de downloadknop hierboven

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="PDF-bestanden online samenvoegen"
  description="[PDF samenvoegen in Python](https://products.aspose.com/slides/nl/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

Een bestand met de extensie .ppt is een PowerPoint-presentatie met een verzameling dia's voor een diavoorstelling. Het gebruikt het binaire bestandsformaat dat door Microsoft PowerPoint 97–2003 wordt ondersteund. Een PPT-bestand kan verschillende soorten inhoud bevatten, zoals tekst, opsommingen, afbeeldingen, multimedia en andere ingesloten OLE-objecten. Vanaf PowerPoint 2007 introduceerde Microsoft het nieuwere PPTX-formaat, dat op Office Open XML is gebaseerd in plaats van op dit binaire formaat. Ook andere toepassingen, zoals OpenOffice Impress en Apple Keynote, kunnen PPT-bestanden maken.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde samenvoegindelingen" subTitle="Met behulp van C# kan men ook vele andere bestandsindelingen samenvoegen, waaronder." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/odp/" name="ODP" description="OpenDocument-presentatie-indeling" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/otp/" name="OTP" description="Standaardformaat OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/pot/" name="POT" description="Microsoft PowerPoint-sjabloonbestanden" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/potm/" name="POTM" description="Microsoft PowerPoint-sjabloonbestand" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/potx/" name="POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/pps/" name="PPS" description="PowerPoint-diavoorstelling" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/ppsm/" name="PPSM" description="Diavoorstelling met macro's" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/ppsx/" name="PPSX" description="PowerPoint-diavoorstelling" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/pptm/" name="PPTM" description="Presentatiebestand met macro's" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/merger/pptx/" name="PPTX" description="Open XML-presentatie-indeling" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
