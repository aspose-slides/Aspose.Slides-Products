---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie PPS über C# in BMP
weight: 1980
url: /de/net/conversion/pps-to-bmp/ 
description: Beispielcode für die Konvertierung von PPS in BMP C#. Verwenden Sie den API-Beispielcode für die Batch-Konvertierung von PPS-Dateien in BMP innerhalb von VB.NET, Asp.NET oder einer beliebigen .NET-basierten Anwendung.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie PPS über C# in BMP" h2="Exportieren Sie PowerPoint® PPS-Dateien in BMP auf .NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="So konvertieren Sie PPS in BMP mit C#" %}}

Um PPS in BMP umzuwandeln, verwenden wir
 [Aspose.Slides für .NET](https://products.aspose.com/slides/de/net)
 API, die eine funktionsreiche, leistungsstarke und einfach zu verwendende API zur Dokumentenbearbeitung und -konvertierung für die C#-Plattform ist. Offen
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 Paketmanager, suche nach
 Aspose.Folien
 und installieren. Sie können auch den folgenden Befehl in der Paket-Manager-Konsole verwenden.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Paket-Manager-Konsolenbefehl" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Dieser Beispielcode zeigt die PPS-zu-BMP-C#-Konvertierung" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Schritte zum Konvertieren von PPS in BMP über C#" intro=".NET-Entwickler können mit nur wenigen Codezeilen problemlos PPS-Dateien in BMP laden und konvertieren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie eine PPS-Datei mit einer Instanz der Präsentationsklasse{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Durchlaufen Sie jede Folie in der Präsentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Erstellen Sie bei jeder Iteration ein Bild in voller Größe als Bitmap{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die Bitmap.Save-Methode mit der BMP-Dateierweiterung und ImageFormat.Bmp als Parameter auf{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Anforderungen" intro="Stellen Sie vor dem Ausführen des Beispielquellcodes für die .NET-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind." %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Windows Azure, Mono oder Xamarin-Plattformen.
- Entwicklungsumgebung wie Microsoft Visual Studio.
- Aspose.Slides für .NET-DLL, auf die in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Kostenlose App, um PPS in BMP zu konvertieren"
  description="[Versuchen Sie unsere kostenlose App, um PPT in BMP konvertieren zu können](https://products.aspose.app/slides/conversion/ppt-to-bmp)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere unterstützte Konvertierungen" subTitle="Sie können PPS auch in viele andere Dateiformate konvertieren, darunter einige, die unten aufgeführt sind." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-emf/" name="PPS TO EMF" description="Verbessertes Metafile-Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-gif/" name="PPS TO GIF" description="Grafisches Austauschformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-html/" name="PPS TO HTML" description="Hypertext-Auszeichnungssprache" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-jpeg/" name="PPS TO JPEG" description="JPEG-Bild" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-odp/" name="PPS TO ODP" description="OpenDocument-Präsentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-otp/" name="PPS TO OTP" description="OpenDocument-Standardformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-pdf/" name="PPS TO PDF" description="Portables Dokumentenformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-png/" name="PPS TO PNG" description="Portable Netzwerkgrafiken" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-pot/" name="PPS TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-potm/" name="PPS TO POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-potx/" name="PPS TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Makrofähige Diashow" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-pptm/" name="PPS TO PPTM" description="Makrofähige Präsentationsdatei" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Offenes XML-Präsentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-svg/" name="PPS TO SVG" description="Skalierbare Vektorgrafiken" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-swf/" name="PPS TO SWF" description="SWF-Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Markiertes Bildformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/pps-to-xps/" name="PPS TO XPS" description="XML-Papierspezifikationen" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
