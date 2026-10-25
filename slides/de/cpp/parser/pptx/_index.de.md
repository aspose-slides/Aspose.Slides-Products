---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 2290
title: Text aus PPTX-Präsentationen mit C++ extrahieren
url: /de/cpp/parser/pptx/ 
description: Text aus PPTX-Präsentationen in C++ extrahieren. Mit Aspose.Slides for C++ parsen Sie Folien, Textrahmen, Absätze und Textabschnitte.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX-Präsentationen in C++ parsen" h2="Mit Aspose.Slides for C++ extrahieren Sie Text aus Präsentationsfolien – ohne Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPTX-Datei mit C++ parsen" %}}

Mit Aspose.Slides for C++ parsen Sie PPTX-Präsentationsdateien und extrahieren Text aus Folien. Die API stellt den Folientext über `SlideUtil::GetAllTextBoxes`, `ITextFrame`, `IParagraph` und `IPortion` bereit, sodass Sie Textinhalte ohne Automatisierung von Microsoft PowerPoint lesen können. Installieren Sie das Paket [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) über NuGet oder verwenden Sie den folgenden Befehl in der Paket-Manager-Konsole.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Befehl" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX-Dateien parsen – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="So parsen Sie PPTX-Dateien in C++" intro="Extrahieren Sie Text aus PPTX-Dateien mit Aspose.Slides for C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die PPTX-Datei mit der Klasse `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die `ITextFrame`-Objekte der ersten Folie mit `SlideUtil::GetAllTextBoxes` ab.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Durchlaufen Sie die `ITextFrame`-Objekte.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Durchlaufen Sie die `IParagraph`-Objekte in jedem `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Durchlaufen Sie die `IPortion`-Objekte in jedem `IParagraph`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lesen Sie den Text mit `get_Text`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systemanforderungen" intro="Aspose.Slides for C++ unterstützt gängige Desktop- und Serverplattformen. Stellen Sie sicher, dass Ihr Projekt die folgenden Voraussetzungen erfüllt." %}}

-  Microsoft Windows, Linux, macOS oder ein anderes kompatibles Betriebssystem mit der unterstützten C++-Laufzeitumgebung.
-  Die Bibliothek Aspose.Slides for C++, referenziert in Ihrem Projekt.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Entwickelt mit Aspose.Slides" title="Text und Bilder online extrahieren" description="Die kostenlose App Aspose.Slides Parser basiert auf [Aspose.Slides for C++](https://products.aspose.com/slides/de/cpp/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Parser öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Ihre Dateien liest, bevor Sie Code schreiben.
- Laden Sie eine PPTX-Datei hoch und erhalten Sie ihren Text und ihre Bilder.
- Laden Sie alles als ein ZIP-Archiv herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

A PPTX file is a Microsoft PowerPoint Open XML presentation file. It stores slides, text, images, formatting, animations, and other presentation content in a zipped XML-based package.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Weitere unterstützte Formate zum Parsen" subTitle="Mit C++ können Sie auch andere Präsentationsformate parsen." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/parser/odp/" name="ODP" description="OpenDocument-Präsentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/de/cpp/parser/ppt/" name="PPT" description="PowerPoint 97–2003-Präsentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
