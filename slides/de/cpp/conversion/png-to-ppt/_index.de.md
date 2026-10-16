---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie PNG in PPT in C++
url: /de/cpp/conversion/png-to-ppt/
keywords: Konvertieren Sie PNG in PPT, PNG in PPT, PowerPoint, PNG, PPT, C++ API, C++ Bibliothek
description: Konvertieren Sie PNG in PPT in C++. Verwenden Sie die C++-Bibliotheks-API, um PNG-Bilder in PowerPoint zu konvertieren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie PNG in PPT in C++" h2="Leistungsstarke plattformübergreifende C++-API zum Konvertieren von PNG in PPT mithilfe von C++-Code" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie PNG in PPT in C++" variant="code" %}}

Mit [**Aspose.Slides for C++**](https://products.aspose.com/slides/de/cpp/) können Sie mit nur wenigen Codezeilen ein PNG-Bild in eine PowerPoint-Präsentation konvertieren:

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++-Code zum Konvertieren von PNG in PPT" >}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie PNG in PPT mit Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/de/cpp/) ist eine leistungsstarke C++-Bibliothek zum Erstellen, Konvertieren und Bearbeiten von PowerPoint-Präsentationen, PDFs, HTML-Dokumenten und anderen Dateien. Wenn Sie PNG in PPT konvertieren, erstellen Sie im Wesentlichen eine PowerPoint-Präsentation, die Folien enthält, die auf PNG-Bildern basieren.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie PNG in PPT in C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie **Aspose.Slides für C++**. Siehe [**Installation**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie die Bibliothek als Referenz in Ihrem Projekt hinzu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Erstellen Sie eine Instanz der Presentation-Klasse.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie das PNG-Bild, das Sie in PPT konvertieren möchten.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die resultierende Datei als PPT-Präsentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Kostenloser Online-Konverter"
  description="[So konvertieren Sie PPT in HTML in Python](https://products.aspose.com/slides/de/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere unterstützte PowerPoint-Konvertierungen" subTitle="Sie können auch Dateien in anderen Formaten in PowerPoint konvertieren" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
