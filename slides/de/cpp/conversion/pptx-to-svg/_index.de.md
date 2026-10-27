---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie PPTX über eine C++-Anwendung in SVG
weight: 880
url: /de/cpp/conversion/pptx-to-svg/ 
description: Beispiel-C++-Konvertierungscode für ein PPTX-Dokument in das SVG-Format. Verwenden Sie Beispielcode für die Batch-Umwandlung von PPTX in SVG in einer beliebigen C++-Anwendung.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie PPTX über C++ in SVG" h2="Leistungsstarke PPTX-zu-SVG-Konvertierung mithilfe der C++-Bibliothek ohne die Notwendigkeit einer Microsoft PowerPoint-Installation."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="So konvertieren Sie PPTX in SVG mit C++" %}}

Um PPTX in SVG zu konvertieren, verwenden wir
 [Aspose.Folien für C++](https://products.aspose.com/slides/de/cpp/)
 API, die eine funktionsreiche, leistungsstarke und einfach zu verwendende API zur Dokumentenbearbeitung und -konvertierung für die C++-Plattform ist. Sie können die neueste Version direkt herunterladen, einfach öffnen
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 Paketmanager, suche nach
 Aspose.Slides.Cpp
 und installieren. Sie können auch den folgenden Befehl in der Paket-Manager-Konsole verwenden.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Befehl" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX-zu-SVG-C++-Konvertierungsquellcode" >}}
```cs
// Load the PPTX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.pptx");
// Save in SVG format.
for (int32_t index = 0; index < prs->get_Slides()->get_Count(); index++)
{
    auto fileName = String::Format(u"slide-{0}.svg", index);
    auto fileStream = System::MakeObject<FileStream>(fileName, FileMode::Create, FileAccess::Write);

    auto slide = prs->get_Slides()->idx_get(index);
    slide->WriteAsSvg(fileStream);
}

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Schritte zum Konvertieren von PPTX in SVG über C++" intro="C++-Entwickler können PPTX-Dateien in nur wenigen Codezeilen problemlos in SVG konvertieren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX-Datei mit Aspose.Slides für C++-Präsentationsobjekt laden.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die Methode Save() auf.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Übergeben Sie den Ausgabedateipfad mit der Dateierweiterung (SVG).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Die SVG-Datei wird unter dem angegebenen Pfad gespeichert.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die SVG-Datei in einem kompatiblen Programm.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Anforderungen" intro="Stellen Sie vor dem Ausführen des Beispielcodes für die C++-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind." %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit C++ Runtime Environment für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.
- Aspose.Slides für C++-DLL, auf die in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Entwickelt mit Aspose.Slides" title="PPTX online in SVG konvertieren" description="Die kostenlose App Aspose.Slides Conversion basiert auf [Aspose.Slides for C++](https://products.aspose.com/slides/de/cpp/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Conversion öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" upload="Datei ablegen oder hochladen" saveAs="Speichern als" convert="Konvertieren" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Dateien konvertiert, bevor Sie Code schreiben.
- Laden Sie PPTX-Dateien hoch und speichern Sie sie als SVG.
- Laden Sie das Ergebnis herunter oder konvertieren Sie weitere Dateien.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere unterstützte Konvertierungen" subTitle="Sie können PPTX auch in viele andere Dateiformate konvertieren, darunter einige, die unten aufgeführt sind." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Bitmap-Bild" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" description="Verbessertes Metafile-Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Grafisches Austauschformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" description="Hypertext-Auszeichnungssprache" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="JPEG-Bild" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument-Präsentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument-Standardformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Portables Dokumentenformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" description="Portable Netzwerkgrafiken" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-pot/" name="PPTX TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-pps/" name="PPTX TO PPS" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Makrofähige Diashow" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Makrofähige Präsentationsdatei" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Markiertes Bildformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-xml/" name="PPTX TO XML" description="Erweiterbare Auszeichnungssprache" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML-Papierspezifikationen" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
