---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Bearbeiten Sie PPTX-Dateien über .NET
url: /de/net/editor/pptx/ 
description: C#-Quellcode zum Bearbeiten von PPTX-Dokumenten auf .NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX-Formate in C# bearbeiten" h2="Native und leistungsstarke Bearbeitung von PPTX-Dokumenten mit serverseitigen Aspose.Slides für .NET-APIs, ohne Verwendung von Software wie Microsoft oder Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="So bearbeiten Sie eine PPTX-Datei mit C#" %}}

Um die PPTX-Datei zu bearbeiten, verwenden wir die API <a href="https://products.aspose.com/slides/de/net">Aspose.Slides for .NET</a>, die funktionsreich und leistungsstark ist und benutzerfreundliche API für die C#-Plattform für jeden Editor. Öffnen Sie den <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a>-Paketmanager, suchen Sie nach <b>Aspose.Slides</b> und installieren Sie es. Sie können auch den folgenden Befehl in der Paket-Manager-Konsole verwenden.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Befehl" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX-Dateien bearbeiten – C#" >}}
```cs
using var presentation = new Presentation("document.pptx");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Schritte zum Bearbeiten von PPTX-Dateien in C#" intro="Eine grundlegende Dokumentenbearbeitung mit [Aspose.Slides für .NET](https://products.aspose.com/slides/de/net) APIs können mit nur wenigen Codezeilen erstellt werden." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die PPTX-Datei mit einem `Presentation`-Objekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Greifen Sie über Variablen auf die gewünschte Folie und Form zu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aktualisieren Sie den Text über `TextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die bearbeitete Präsentation mit `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Anforderungen" intro="Unsere APIs werden auf allen wichtigen Plattformen und Betriebssystemen unterstützt. Bevor Sie den folgenden Code ausführen, stellen Sie bitte sicher, dass die folgenden Voraussetzungen auf Ihrem System erfüllt sind." %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Windows Azure, Mono oder Xamarin-Plattformen
- Entwicklungsumgebung wie Microsoft Visual Studio
- Aspose.Slides für .NET-DLL, auf die in Ihrem Projekt verwiesen wird - Installieren Sie von NuGet mithilfe der Download-Schaltfläche oben

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Entwickelt mit Aspose.Slides" title="PPTX-Dateien online bearbeiten" description="Die kostenlose App Aspose.Slides Editor basiert auf [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Editor öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Ihre Dateien verarbeitet, bevor Sie Code schreiben.
- Laden Sie Ihre PPTX-Dateien hoch und bearbeiten Sie sie sofort.
- Speichern Sie die bearbeitete Datei und laden Sie sie herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
