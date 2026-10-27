---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPSM-Dateien über .NET zusammenführen
weight: 3860
url: /de/net/merger/ppsm/ 
description: C#-Quellcode zum Kombinieren von PPSM-Dokumenten auf .NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPSM-Formate in C# zusammenführen" h2="Native und leistungsstarke PPSM-Dokumentenzusammenführung mit serverseitigen Aspose.Slides für .NET-APIs, ohne die Verwendung von Software wie Microsoft oder Open Office, Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="So führen Sie PPSM-Dateien mit C# zusammen" %}}

Um die PPSM-Datei zusammenzuführen, verwenden wir
 [Aspose.Slides für .NET](https://products.aspose.com/slides/de/net)
 API, die eine funktionsreiche, leistungsstarke und einfach zu verwendende API zur Dokumentenbearbeitung und -zusammenführung für die C#-Plattform ist. Offen
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 Paketmanager, suche nach
 **Aspose.Folien**
 und installieren. Sie können auch den folgenden Befehl in der Paket-Manager-Konsole verwenden.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Befehl" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSM-Dateien zusammenführen – C#" >}}
```cs
var ps1 = new Presentation("presen1.ppsm");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first PPSM presentation is added with its own styles.
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Schritte zum Zusammenführen von PPSM-Dateien in C#" intro="Ein grundlegendes Zusammenführen und Verketten von Dokumenten mit [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net) APIs kann mit nur wenigen Codezeilen durchgeführt werden." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie alle PPSM-Dateien mit vollständigem Pfad.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Erstellen Sie ein Dokument als Basisdatei{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die relevante Methode zum Verketten und Zusammenführen von Dateien einzeln auf.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die Save()-Methode auf und übergeben Sie den Dateinamen (vollständiger Pfad) und das Format (PPSM) als Parameter.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Jetzt können Sie die PPSM-Datei in Microsoft Office, Adobe PDF oder einem anderen kompatiblen Programm öffnen und verwenden.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Anforderungen" intro="Unsere APIs werden auf allen wichtigen Plattformen und Betriebssystemen unterstützt. Bevor Sie den folgenden Code ausführen, stellen Sie bitte sicher, dass die folgenden Voraussetzungen auf Ihrem System erfüllt sind." %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Windows Azure, Mono oder Xamarin-Plattformen
- Entwicklungsumgebung wie Microsoft Visual Studio
- Aspose.Slides für .NET-DLL, auf die in Ihrem Projekt verwiesen wird - Installieren Sie von NuGet mithilfe der Download-Schaltfläche oben

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Entwickelt mit Aspose.Slides" title="PPSM-Dateien online zusammenführen" description="Die kostenlose App Aspose.Slides Merger basiert auf [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPSM-Dateien leisten kann." button="Aspose.Slides Merger öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Dateien zusammenführt, bevor Sie Code schreiben.
- Laden Sie mehrere PPSM-Dateien hoch und führen Sie sie zu einer zusammen.
- Laden Sie das zusammengeführte Ergebnis als eine Datei herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSM" readMoreLink="https://docs.fileformat.com/presentation/ppsm/" %}}

Dateien mit der Erweiterung PPSM sind Bildschirmpräsentationen mit Makrounterstützung, die mit Microsoft PowerPoint 2007 eingeführt wurden. Anders als PPTM öffnet sich PPSM standardmäßig in der Bildschirmpräsentationsansicht. Dieser Standardmodus ist kein Dateischutz: Eine PPSM-Datei lässt sich auch in Microsoft PowerPoint zur Bearbeitung öffnen.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere unterstützte Zusammenführungsformate" subTitle="Mit C# kann One auch viele andere Dateiformate zusammenführen, einschließlich." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/merger/odp/" name="ODP" description="OpenDocument-Präsentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/merger/otp/" name="OTP" description="OpenDocument-Standardformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/merger/pot/" name="POT" description="Microsoft PowerPoint-Vorlagendateien" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/merger/potm/" name="POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/merger/potx/" name="POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/merger/pps/" name="PPS" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/merger/ppsx/" name="PPSX" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/merger/pptm/" name="PPTM" description="Makrofähige Präsentationsdatei" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/merger/pptx/" name="PPTX" description="Offenes XML-Präsentationsformat" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
