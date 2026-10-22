---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Bewerk OTP-bestanden via .NET
url: /nl/net/editor/otp/ 
description: C#-broncode om OTP-document te bewerken op .NET Framework, .NET Core, Windows Azure, Mono of Xamarin Platforms.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bewerk OTP-indelingen in C#" h2="Native en hoogwaardige OTP-documentbewerking met Aspose.Slides aan de serverzijde voor .NET API's, zonder het gebruik van software zoals Microsoft of Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,PDF,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hoe OTP-bestand te bewerken met C#" %}}

Om het OTP-bestand te bewerken, gebruiken we <a href="https://products.aspose.com/slides/nl/net">Aspose.Slides for .NET</a> API, een veelzijdige, krachtige en eenvoudig te gebruiken API voor C#-platform voor elke editor. Open <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a>-pakketbeheerder, zoek naar <b>Aspose.Slides</b> en installeer. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Opdracht" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="OTP-bestanden bewerken - C#" >}}
```cs
using var presentation = new Presentation("document.otp");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.otp", SaveFormat.Otp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Stappen voor het bewerken van OTP-bestanden in C#" intro="Een eenvoudige documentbewerking met [Aspose.Slides voor .NET](https://products.aspose.com/slides/nl/net) API's kunnen worden gedaan met slechts een paar regels code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het OTP-bestand met een `Presentation`-object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open de gewenste dia en vorm via variabelen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Werk de tekst bij via `TextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla de bewerkte presentatie op met `SaveFormat.Otp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="systeem vereisten" intro="Onze API's worden ondersteund op alle belangrijke platforms en besturingssystemen. Voordat u de onderstaande code uitvoert, moet u ervoor zorgen dat u de volgende vereisten op uw systeem hebt." %}}

- Microsoft Windows of een compatibel besturingssysteem met .NET Framework, .NET Core, Windows Azure, Mono of Xamarin Platforms
- Ontwikkelomgeving zoals Microsoft Visual Studio
- Aspose.Slides voor .NET DLL waarnaar in uw project wordt verwezen - Installeer vanaf NuGet met behulp van de downloadknop hierboven

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="OTP" readMoreLink="https://docs.fileformat.com/presentation/otp/" %}}

Files with .OTP extension represent presentation template files created by applications in OASIS OpenDocument standard format. The contents of such a file include presentation information in the form of slides with text, images, shapes, multimedia content, transition effects and other slide elements. These template files are used for creating new presentations quickly based on the styling information stored in the template itself. OTP files can be created and saved with several different applications such as Impress that comes with OpenOffice suite and Microsoft PowerPoint. The OTP file format is similar to Microsoft PowerPoint template files .POT and .POTX.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
