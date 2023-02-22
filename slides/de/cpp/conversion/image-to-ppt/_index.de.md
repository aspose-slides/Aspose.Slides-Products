---
title: Bild in PPT in C++ konvertieren
url: /de/cpp/conversion/image-to-ppt/
keywords: Bild in PPT, Bild in PPT konvertieren, C++-API, C++-Bibliothek, Bild, PPT
description: Bild in PPT in C++ konvertieren. Verwenden Sie die C++-Bibliotheks-API, um Bilddateien in PDFs zu konvertieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Bild in PPT in C++ konvertieren" h2="Hochgeschwindigkeits- und plattformübergreifende C++-Bibliothek, die bei der Entwicklung von Anwendungen mit der Fähigkeit hilft, Microsoft PowerPoint- und OpenOffice-Präsentationsdateien ohne die Verwendung von Software wie Microsoft oder Open Office, Adobe PDF zu erstellen, zusammenzuführen, zu überprüfen oder zu konvertieren." >}}

{{% blocks/products/pf/feature-page-section h2="Bild in PPT in C++ konvertieren" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/de/cpp/) ist eine leistungsstarke C++-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten, Bilder in PPT zu konvertieren. Mit **Aspose.Slides for C++** kann jeder Entwickler oder jede Anwendung Bilder mit nur wenigen Zeilen C++-Code in PPT-Dateien konvertieren.

Als moderne Dokumentverarbeitungs-API exportiert Aspose.Slides für C++ Bilddateien schnell in PPT-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie Bilder in PDFs und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie Bilder mit C++ in PPT" %}}
Um das Bild in PPT zu konvertieren, müssen Sie eine Präsentation aus einer Bilddatei erstellen und als PPT speichern.

{{% blocks/products/pf/agp/code-block title="C++-Code zum Konvertieren von Bild in PPT" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);
pres->Save(u"presentation.ppt", SaveFormat::Ppt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So konvertieren Sie Bilder mit Aspose.Slides für die C++-API in PPT" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Konvertieren von Bild in PPT in C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie [**Aspose.Slides für C++**](https://products.aspose.com/slides/de/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Ihrem C++-Projekt einen Bibliotheksverweis hinzu (Importieren Sie die Bibliothek).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öffnen Sie die Quellbilddateien in C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis als PPT-Datei speichern.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Bild in andere unterstützte Formate konvertieren" subTitle="Sie können Bilder auch konvertieren und in anderen Dateiformaten speichern. Siehe unten alle unterstützten Formate" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}