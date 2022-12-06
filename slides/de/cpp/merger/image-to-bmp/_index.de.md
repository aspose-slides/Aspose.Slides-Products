---
title: Bild zu BMP in C++ zusammenführen
url: /de/cpp/merger/image-to-bmp/
keywords: Bild zu BMP, Bild zu BMP zusammenführen, Bild zu BMP verbinden, Bilder kombinieren, Bild, BMP, C++ API, C++ Bibliothek
description: Bild zu BMP in C++ zusammenführen. Verwenden Sie die C++-Bibliotheks-API, um Bilder zu kombinieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Bild zu BMP in C++ zusammenführen" h2="Hochgeschwindigkeits- und plattformübergreifende C++-Bibliothek zum Zusammenführen von Bildern mit BMP-Dateien unter Verwendung von C++-Code" >}}

{{% blocks/products/pf/feature-page-section h2="Bild mit Aspose.Slides in BMP zusammenführen" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/de/cpp/) ist eine leistungsstarke C++-Bibliothek zum Erstellen, Konvertieren, Zusammenführen und Bearbeiten von Präsentationen, PDFs, Bildern und anderem Dateien. Wenn Sie Bilder mit BMP zusammenführen, kombinieren Sie effektiv Bilder, um eine einzelne BMP-Datei zu erhalten.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Bild zu BMP in C++ zusammenführen" %}}
Mit [**Aspose.Slides for C++**](https://products.aspose.com/slides/de/cpp/) können Sie Bilder mit nur wenigen Codezeilen schnell in BMP zusammenführen

{{% blocks/products/pf/agp/code-block title="C++-Code zum Zusammenführen von Image mit BMP" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();
        
auto image1 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image1.png"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 100.0f, 100.0f, image1);
auto image2 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image2.png"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 200.0f, 100.0f, 100.0f, image2);

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    auto fileName = String::Format(u"slide_{0}.bmp", index);
    slide->GetThumbnail()->Save(fileName, ImageFormat::get_Bmp());
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Wie man ein Bild in C++ mit BMP zusammenführt" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie **Aspose.Slides für C++**. Siehe [**Installation**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie die Bibliothek als Referenz in Ihrem Projekt hinzu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Erstellen Sie eine Instanz der Presentation-Klasse.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie die Bilder, die Sie zusammenfügen möchten, als Bilderrahmen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Speichern Sie die resultierende BMP-Datei.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Andere Dateien zusammenführen" subTitle="Sie können auch Dateien in anderen Formaten kombinieren, um eine einzige Datei zu erhalten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}