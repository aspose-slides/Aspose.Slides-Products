---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie PNG in SVG in C++
url: /de/cpp/conversion/png-to-svg/
keywords: PNG in SVG, Konvertiere PNG in SVG, C++-API, C++-Bibliothek, PNG, SVG
description: Konvertieren Sie PNG in SVG in C++. Verwenden Sie die C++-Bibliotheks-API, um PNG-Dateien in SVGs zu konvertieren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie PNG in SVG in C++" h2="Hochgeschwindigkeits- und plattformübergreifende C++-Bibliothek, die bei der Entwicklung von Anwendungen mit der Fähigkeit hilft, Microsoft PowerPoint- und OpenOffice-Präsentationsdateien ohne die Verwendung von Software wie Microsoft oder Open Office, Adobe PDF zu erstellen, zusammenzuführen, zu überprüfen oder zu konvertieren." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie PNG in SVG mit C++" variant="code" %}}

Um das PNG in SVG zu konvertieren, müssen Sie eine Präsentation aus der PNG-Datei erstellen und sie als SVG speichern.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++-Code zum Konvertieren von PNG in SVG" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto fileName = String::Format(u"slide-{0}.svg", index);
    auto fileStream = System::MakeObject<FileStream>(fileName, FileMode::Create, FileAccess::Write);

    auto slide = pres->get_Slides()->idx_get(index);
    slide->WriteAsSvg(fileStream);
}

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie PNG in SVG in C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/de/cpp/) ist eine leistungsstarke C++-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten, PNG in SVG zu konvertieren. Mit **Aspose.Slides for C++** kann jeder Entwickler oder jede Anwendung PNG-Dateien mit nur wenigen Zeilen C++-Code in SVG-Dateien konvertieren.

Als moderne Dokumentverarbeitungs-API exportiert Aspose.Slides für C++ schnell PNG-Dateien in SVG-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie PNG in SVGs und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie PNG in SVG mit Aspose.Slides für die C++-API" intro="Dies sind die Schritte zum Konvertieren von PNG in SVG in C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie [**Aspose.Slides für C++**](https://products.aspose.com/slides/de/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie Ihrem C++-Projekt einen Bibliotheksverweis hinzu (Importieren Sie die Bibliothek).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die Quelldateien PNG in C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ergebnis als SVG-Datei speichern.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Kostenloser Online-Konverter"
  description="[So konvertieren Sie PPT in HTML in Python](https://products.aspose.com/slides/de/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konvertieren Sie PNG in andere unterstützte Formate" subTitle="Sie können PNG auch konvertieren und in anderen Dateiformaten speichern. Siehe unten alle unterstützten Formate" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
