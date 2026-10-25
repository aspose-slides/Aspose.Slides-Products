---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3070
title: Text aus ODP-Dateien mit .NET extrahieren
url: /de/net/parser/odp/ 
description: C#-Quellcode zum Extrahieren von Text aus ODP-Dateien mit .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ODP-Dateien mit C# parsen" h2="Text aus ODP-Dateien extrahieren und die Textformatierung mit serverseitigen .NET-APIs auslesen."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ODP-Datei mit C# parsen" %}}

Mit [Aspose.Slides for .NET](/slides/de/net/) extrahieren Sie Text aus ODP-Präsentationen. Installieren Sie das Paket über [NuGet](https://www.nuget.org/packages/aspose.slides.net) oder führen Sie den folgenden Befehl in der Paket-Manager-Konsole aus.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Befehl" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP-Dateien parsen – C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="So parsen Sie ODP-Dateien in C#" intro="Für das einfache Parsen von Dokumenten mit der API [Aspose.Slides for .NET](/slides/de/net/) genügen wenige Codezeilen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die ODP-Datei mit `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die Textrahmen mit `SlideUtil.GetAllTextFrames` ab.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Durchlaufen Sie Textrahmen, Absätze und Textabschnitte.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lesen Sie bei Bedarf die Eigenschaften `Text`, `FontHeight` und `LatinFont.FontName`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systemanforderungen" intro="Erforderlich sind eine unterstützte .NET-Laufzeitumgebung und ein Paketverweis auf Aspose.Slides for .NET. Sie können Visual Studio oder eine andere kompatible C#-Entwicklungsumgebung verwenden." %}}

- .NET Framework, .NET, Mono oder eine Xamarin-kompatible Umgebung
- Eine C#-Entwicklungsumgebung wie Visual Studio
- Aspose.Slides for .NET, installiert über NuGet

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Entwickelt mit Aspose.Slides" title="Text und Bilder online extrahieren" description="Die kostenlose App Aspose.Slides Parser basiert auf [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen ODP-Dateien leisten kann." button="Aspose.Slides Parser öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Ihre Dateien liest, bevor Sie Code schreiben.
- Laden Sie eine ODP-Datei hoch und erhalten Sie ihren Text und ihre Bilder.
- Laden Sie alles als ein ZIP-Archiv herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

ODP files use the OpenDocument Presentation format. A presentation contains slides with text, images, formatting, animations, and other media. Applications that support the OpenDocument format, such as OpenOffice and StarOffice, can open ODP files.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate zum Parsen" subTitle="Mit C# können Sie auch die folgenden Formate parsen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/parser/ppt/" name="PPT" description="PowerPoint 97–2003-Präsentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/net/parser/pptx/" name="PPTX" description="PowerPoint-Open-XML-Präsentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
