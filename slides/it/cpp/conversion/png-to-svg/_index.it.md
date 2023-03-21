---
title: Converti PNG in SVG in C++
url: /it/cpp/conversion/png-to-svg/
keywords: PNG in SVG, conversione di PNG in SVG, API C++, libreria C++, PNG, SVG
description: Converti PNG in SVG in C++. Utilizza l'API della libreria C++ per convertire i file PNG in SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti PNG in SVG in C++" h2="Libreria C++ ad alta velocità e multipiattaforma che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converti PNG in SVG in C++" %}}

[**Aspose.Slides per C++**](https://products.aspose.com/slides/it/cpp/) è una potente libreria C++ per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per convertire PNG in SVG. Utilizzando **Aspose.Slides per C++**, qualsiasi sviluppatore o applicazione può convertire i file PNG in SVG con poche righe di codice C++.

Come moderna API per l'elaborazione dei documenti, Aspose.Slides per C++ esporta rapidamente file PNG in formati di file SVG. La libreria Aspose PowerPoint ti consente di convertire PNG in SVG se molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti PNG in SVG utilizzando C++" %}}
Per convertire PNG in SVG, dovrai creare una presentazione dal file PNG e salvarla come SVG.

{{% blocks/products/pf/agp/code-block title="Codice C++ per convertire PNG in SVG" offSpacer="true" %}}

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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come convertire PNG in SVG utilizzando Aspose.Slides per l'API C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per convertire PNG in SVG in C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides per C++**](https://products.aspose.com/slides/it/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file di origine PNG in C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertitore online gratuito" sectionDescription="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti PNG in altri formati supportati" subTitle="Puoi anche convertire PNG e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/png-to-pdf/" name="PNG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}