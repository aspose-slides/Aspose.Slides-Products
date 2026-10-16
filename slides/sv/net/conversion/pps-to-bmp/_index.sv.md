---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera PPS till BMP via C#
weight: 1980
url: /sv/net/conversion/pps-to-bmp/ 
description: Exempelkod för konvertering av PPS till BMP C#. Använd API-exempelkod för batch-PPS-filer till BMP-konvertering inom VB.NET, Asp.NET eller någon .NET-baserad applikation.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera PPS till BMP via C#" h2="Exportera PowerPoint® PPS-filer till BMP på .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hur man konverterar PPS till BMP med C#" %}}

För att konvertera PPS till BMP kommer vi att använda
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Denna exempelkod visar PPS till BMP C#-konvertering" >}}
```cs
using (var presentation = new Presentation("template.pps"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in BMP format
        bitmap.Save(string.Format("Slide_{0}.bmp", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Bmp);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steg för att konvertera PPS till BMP via C#" intro=".NET-utvecklare kan enkelt ladda och konvertera PPS-filer till BMP på bara några rader kod." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda PPS-fil med en instans av presentationsklassen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterera genom varje bild i presentationen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skapa en fullskalig bild som en bitmapp med varje iteration{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ring Bitmap.Save-metoden med BMP-filtillägg & ImageFormat.Bmp som parametrar{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systemkrav" intro="Innan du kör källkoden för .NET-omvandlingen, se till att du har följande förutsättningar." %}}

- Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar.
- Utvecklingsmiljö som Microsoft Visual Studio.
- Aspose.Slides för .NET DLL som refereras till i ditt projekt.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis app att konvertera PPS till BMP"
  description="[Prova vår gratis app att konvertera PPT till BMP](https://products.aspose.app/slides/conversion/ppt-to-bmp)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera PPS till många andra filformat inklusive några som anges nedan." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-emf/" name="PPS TO EMF" description="Förbättrat metafilformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-gif/" name="PPS TO GIF" description="Grafiskt utbytesformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-html/" name="PPS TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-jpeg/" name="PPS TO JPEG" description="JPEG-bild" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-odp/" name="PPS TO ODP" description="OpenDocument presentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-otp/" name="PPS TO OTP" description="OpenDocument standardformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-pdf/" name="PPS TO PDF" description="Portabelt dokumentformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-png/" name="PPS TO PNG" description="Bärbar nätverksgrafik" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-pot/" name="PPS TO POT" description="Microsoft PowerPoint-mallfiler" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-potm/" name="PPS TO POTM" description="Microsoft PowerPoint-mallfil" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-potx/" name="PPS TO POTX" description="Presentation av Microsoft PowerPoint-mall" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Makroaktiverat bildspel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-pptm/" name="PPS TO PPTM" description="Makroaktiverad presentationsfil" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Öppna XML-presentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-svg/" name="PPS TO SVG" description="Skalbar vektorgrafik" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-swf/" name="PPS TO SWF" description="SWF-format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Taggad bildformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/net/conversion/pps-to-xps/" name="PPS TO XPS" description="XML-pappersspecifikationer" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
