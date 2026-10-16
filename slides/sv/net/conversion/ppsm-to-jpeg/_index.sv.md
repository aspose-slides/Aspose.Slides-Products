---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera PPSM till JPEG via C#
weight: 8340
url: /sv/net/conversion/ppsm-to-jpeg/ 
description: Exempelkod för PPSM till JPEG C#-konvertering. Använd API-exempelkod för batch PPSM-filer till JPEG-konvertering inom VB.NET, Asp.NET eller någon .NET-baserad applikation.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera PPSM till JPEG via C#" h2="Exportera PowerPoint® PPSM-filer till JPEG på .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hur man konverterar PPSM till JPEG med C#" %}}

För att konvertera PPSM till JPEG kommer vi att använda
 [Aspose.Slides för .NET](https://products.aspose.com/slides/sv/net)
 API som är ett funktionsrikt, kraftfullt och lättanvänt API för dokumentmanipulation och konvertering för C#-plattformen. Öppen
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 pakethanterare, sök efter
 Aspose.Slides
 och installera. Du kan också använda följande kommando från Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Pakethanterarens konsolkommando" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Denna exempelkod visar PPSM till JPEG C#-konvertering" >}}
```cs
using (var presentation = new Presentation("template.ppsm"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in JPEG format
        bitmap.Save(string.Format("Slide_{0}.jpeg", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steg för att konvertera PPSM till JPEG via C#" intro=".NET-utvecklare kan enkelt ladda och konvertera PPSM-filer till JPEG på bara några rader kod." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda PPSM-fil med en instans av presentationsklassen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterera genom varje bild i presentationen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skapa en fullskalig bild som en bitmapp med varje iteration{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ring Bitmap.Save-metoden med JPEG-filtillägg och ImageFormat.Jpeg som parametrar{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systemkrav" intro="Innan du kör källkoden för .NET-omvandlingen, se till att du har följande förutsättningar." %}}

- Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar.
- Utvecklingsmiljö som Microsoft Visual Studio.
- Aspose.Slides för .NET DLL som refereras till i ditt projekt.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis app att konvertera PPSM till JPEG"
  description="[Prova vår gratis app att konvertera PPT till JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera PPSM till många andra filformat, inklusive några som anges nedan." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Bitmappsbild" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="Förbättrat metafilformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Grafiskt utbytesformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="OpenDocument presentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="OpenDocument standardformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Portabelt dokumentformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-png/" name="PPSM TO PNG" description="Bärbar nätverksgrafik" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Microsoft PowerPoint-mallfiler" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Microsoft PowerPoint-mallfil" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Presentation av Microsoft PowerPoint-mall" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Makroaktiverad presentationsfil" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Öppna XML-presentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Skalbar vektorgrafik" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="SWF-format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Taggad bildformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="XML-pappersspecifikationer" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
