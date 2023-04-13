---
title: Konvertieren Sie PPT in C++ in Word
url: /de/cpp/conversion/ppt-to-word/
keywords: Konvertieren Sie PPT in Word, PPT in Word, PPT in DOC, PowerPoint in Word, C++-API, C++-Bibliothek, CPP
description: Konvertieren Sie PPT in C++ in Word. Verwenden Sie die C++-Bibliotheks-API, um PowerPoint in Word zu konvertieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie PPT in C++ in Word" h2="Leistungsstarke plattformübergreifende C++-API zum Konvertieren von PowerPoint in Word mithilfe von C++-Code ohne Microsoft PowerPoint oder Office" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie PowerPoint mit Aspose.Slides und Aspose.Words in Word" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/de/cpp/) und [**Aspose.Words for C++**](https://products.aspose.com/ words/cpp/) sind leistungsstarke C++-Bibliotheken zum Bearbeiten und Konvertieren von PowerPoint-Präsentationen, Word-Dokumenten und anderen Dateien. Wenn Sie PowerPoint in Word konvertieren, verschieben Sie im Wesentlichen die Inhalte der Folien einer Präsentation auf Seiten in einem Word-Dokument.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PowerPoint in Word in C++" %}}
Mit nur wenigen Codezeilen können Sie PPT schnell in Word konvertieren

{{% blocks/products/pf/agp/code-block title="C++-Code zum Konvertieren von PowerPoint in Word" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="So konvertieren Sie PPT in Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie **Aspose.Slides für C++** und **Aspose.Words für C++** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Erstellen Sie eine Instanz der Presentation-Klasse und der Doc-Klasse.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie die PPT-Präsentation, die Sie in Word konvertieren möchten.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Generieren Sie Bilder und Texte basierend auf den Inhalten der Folien.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Speichern Sie das resultierende Word-Dokument.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Kostenloser Online-Konverter" sectionDescription="[So konvertieren Sie PPT in HTML in Python](https://products.aspose.com/slides/de/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können PowerPoint auch in Dateien in anderen Formaten konvertieren" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}