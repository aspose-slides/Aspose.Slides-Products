---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPSM in C# anzeigen
keywords: PPSM anzeigen, PPSM öffnen, PPSM-Viewer, PPSM, PowerPoint, C#-API, .NET-Bibliothek
weight: 4780
url: /de/net/viewer/ppsm/ 
description: PPSM-Dateien in C# anzeigen. Öffnen Sie Präsentationsdateien mit Aspose.Slides for .NET und speichern Sie sie als HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPSM in C# anzeigen" h2="C#-API zum Öffnen von PPSM-Dateien und Speichern als responsives HTML."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPSM mit Aspose.Slides anzeigen" %}}

Um PPSM-Dateien anzuzeigen, verwenden Sie die API [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), eine leistungsstarke, funktionsreiche und einfach zu verwendende API für C#. Öffnen Sie den Paket-Manager [NuGet](https://www.nuget.org/packages/aspose.slides.net), suchen Sie nach **Aspose.Slides** und installieren Sie das Paket. Sie können auch den folgenden Befehl in der Paket-Manager-Konsole ausführen.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Befehl für die Paket-Manager-Konsole" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Mit [**Aspose.Slides for .NET**](/slides/de/net/) können Sie eine PPSM-Datei laden und mit wenigen Codezeilen als responsives HTML speichern.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C#-Code zum Anzeigen von PPSM" >}}
```cs
using var presentation = new Presentation("presentation.ppsm");

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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="So zeigen Sie PPSM in C# an" intro="Mit Aspose.Slides zeigen Entwickler PPSM-Dateien mit nur wenigen Codezeilen an." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie **Aspose.Slides for .NET**. Siehe [**Installation**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie die Bibliothek als Referenz zu Ihrem Projekt hinzu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die `PPSM`-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Erstellen Sie ein `ResponsiveHtmlController`-Objekt für eine responsive HTML-Ausgabe.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Erstellen Sie ein `HtmlOptions`-Objekt und legen Sie die Eigenschaft `HtmlFormatter` fest.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die PPSM-Datei mit `SaveFormat.Html` als HTML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systemanforderungen" intro="Aspose.Slides for .NET unterstützt alle gängigen Betriebssysteme. Stellen Sie sicher, dass die folgenden Voraussetzungen erfüllt sind." %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Windows Azure, Mono oder Xamarin
- Eine Entwicklungsumgebung wie Microsoft Visual Studio
- Ein Verweis auf Aspose.Slides for .NET in Ihrem Projekt

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Entwickelt mit Aspose.Slides" title="PPSM-Dateien online anzeigen" description="Die kostenlose App Aspose.Slides Viewer basiert auf [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPSM-Dateien leisten kann." button="Aspose.Slides Viewer öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Ihre Dateien darstellt, bevor Sie Code schreiben.
- Laden Sie Ihre PPSM-Datei hoch und sehen Sie sich die Folien sofort an.
- Funktioniert auf Desktop und Mobilgeräten, ohne PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSM" readMoreLink="https://docs.fileformat.com/presentation/ppsm/" %}}

Dateien mit der Erweiterung PPSM sind Bildschirmpräsentationen mit Makrounterstützung, die mit Microsoft PowerPoint 2007 eingeführt wurden. Anders als PPTM öffnet sich PPSM standardmäßig in der Bildschirmpräsentationsansicht. Dieser Standardmodus ist kein Dateischutz: Eine PPSM-Datei lässt sich auch in Microsoft PowerPoint zur Bearbeitung öffnen.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere Dateien anzeigen" subTitle="Sie können auch Präsentationen in anderen Formaten öffnen und anzeigen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/viewer/odp/" name="ODP" description="OpenDocument-Präsentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/viewer/otp/" name="OTP" description="OpenDocument-Präsentationsvorlage" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/viewer/pot/" name="POT" description="PowerPoint 97–2003-Vorlage" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/viewer/potm/" name="POTM" description="PowerPoint-Vorlage mit Makros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/viewer/potx/" name="POTX" description="PowerPoint-Vorlage" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/viewer/pps/" name="PPS" description="PowerPoint 97–2003-Bildschirmpräsentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/viewer/ppsx/" name="PPSX" description="PowerPoint-Bildschirmpräsentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/viewer/ppt/" name="PPT" description="PowerPoint 97–2003-Präsentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/viewer/pptm/" name="PPTM" description="PowerPoint-Präsentation mit Makros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/viewer/pptx/" name="PPTX" description="PowerPoint-Präsentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
