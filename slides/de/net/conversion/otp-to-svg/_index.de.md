---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie OTP über C# in SVG
weight: 1700
url: /de/net/conversion/otp-to-svg/ 
description: Beispielcode für die Konvertierung von OTP in SVG C#. Verwenden Sie den API-Beispielcode für die Batch-Konvertierung von OTP-Dateien in SVG innerhalb von VB.NET, Asp.NET oder einer beliebigen .NET-basierten Anwendung.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie OTP über C# in SVG" h2="Exportieren Sie PowerPoint®-OTP-Dateien in SVG auf .NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="So konvertieren Sie OTP in SVG mit C#" %}}

Um OTP in SVG zu konvertieren, verwenden wir
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Dieser Beispielcode zeigt die C#-Konvertierung von OTP in SVG" >}}
```cs
using (Presentation pres = new Presentation("template.otp"))
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Schritte zum Konvertieren von OTP in SVG über C#" intro=".NET-Entwickler können OTP-Dateien in nur wenigen Codezeilen einfach laden und in SVG konvertieren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die OTP-Datei mit einer Instanz der Präsentationsklasse{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die Save-Methode auf, während Sie den Ausgabedateipfad und SaveFormat.Svg als Parameter angeben{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Die SVG-Datei wird unter dem angegebenen Pfad gespeichert{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Anforderungen" intro="Stellen Sie vor dem Ausführen des Beispielquellcodes für die .NET-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind." %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Windows Azure, Mono oder Xamarin-Plattformen.
- Entwicklungsumgebung wie Microsoft Visual Studio.
- Aspose.Slides für .NET-DLL, auf die in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Entwickelt mit Aspose.Slides" title="OTP online in SVG konvertieren" description="Die kostenlose App Aspose.Slides Conversion basiert auf [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen OTP-Dateien leisten kann." button="Aspose.Slides Conversion öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" upload="Datei ablegen oder hochladen" saveAs="Speichern als" convert="Konvertieren" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Dateien konvertiert, bevor Sie Code schreiben.
- Laden Sie OTP-Dateien hoch und speichern Sie sie als SVG.
- Laden Sie das Ergebnis herunter oder konvertieren Sie weitere Dateien.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere unterstützte Konvertierungen" subTitle="Sie können OTP auch in viele andere Dateiformate konvertieren, darunter einige, die unten aufgeführt sind." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-bmp/" name="OTP TO BMP" description="Bitmap-Bild" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-emf/" name="OTP TO EMF" description="Verbessertes Metafile-Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-gif/" name="OTP TO GIF" description="Grafisches Austauschformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-html/" name="OTP TO HTML" description="Hypertext-Auszeichnungssprache" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-jpeg/" name="OTP TO JPEG" description="JPEG-Bild" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-odp/" name="OTP TO ODP" description="OpenDocument-Präsentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-pdf/" name="OTP TO PDF" description="Portables Dokumentenformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-png/" name="OTP TO PNG" description="Portable Netzwerkgrafiken" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-pot/" name="OTP TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-potm/" name="OTP TO POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-potx/" name="OTP TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-pps/" name="OTP TO PPS" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="Makrofähige Diashow" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-ppt/" name="OTP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-pptm/" name="OTP TO PPTM" description="Makrofähige Präsentationsdatei" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-pptx/" name="OTP TO PPTX" description="Offenes XML-Präsentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-swf/" name="OTP TO SWF" description="SWF-Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-tiff/" name="OTP TO TIFF" description="Markiertes Bildformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/conversion/otp-to-xps/" name="OTP TO XPS" description="XML-Papierspezifikationen" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
