---
title: Converti PPT in Word in C++
url: /it/cpp/conversion/ppt-to-word/
keywords: Converti PPT in Word, PPT in Word, PPT in DOC, PowerPoint in Word, API C++, Libreria C++, CPP
description: Converti PPT in Word in C++. Usa l'API della libreria C++ per convertire PowerPoint in Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti PPT in Word in C++" h2="Potente API C++ multipiattaforma per convertire PowerPoint in Word utilizzando il codice C++ senza Microsoft PowerPoint o Office" >}}

{{% blocks/products/pf/feature-page-section h2="Converti PowerPoint in Word utilizzando Aspose.Slides e Aspose.Words" %}}

[**Aspose.Slides per C++**](https://products.aspose.com/slides/it/cpp/) e [**Aspose.Words per C++**](https://products.aspose.com/ words/cpp/) sono potenti librerie C++ utilizzate per manipolare e convertire presentazioni PowerPoint, documenti Word e altri file. Quando converti PowerPoint in Word, stai essenzialmente spostando il contenuto delle diapositive di una presentazione nelle pagine di un documento Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Converti PowerPoint in Word in C++" %}}
Puoi convertire rapidamente PPT in Word con poche righe di codice

{{% blocks/products/pf/agp/code-block title="Codice C++ per convertire PowerPoint in Word" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Come convertire PPT in Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installa **Aspose.Slides per C++** e **Aspose.Words per C++** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea un'istanza della classe Presentation e della classe Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica la presentazione PPT che desideri convertire in Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Genera immagini e testi basati sui contenuti delle diapositive.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il documento Word risultante.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertitore online gratuito" sectionDescription="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire PowerPoint in file in altri formati" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}