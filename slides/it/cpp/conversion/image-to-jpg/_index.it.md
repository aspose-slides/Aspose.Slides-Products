---
title: Converti Image in JPG in C++
url: /it/cpp/conversion/image-to-jpg/
keywords: Image in JPG, conversione di Image in JPG, API C++, libreria C++, Image, JPG
description: Converti Image in JPG in C++. Utilizza l'API della libreria C++ per convertire i file Image in JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti Image in JPG in C++" h2="Libreria C++ ad alta velocità e multipiattaforma che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converti Image in JPG in C++" %}}

[**Aspose.Slides per C++**](https://products.aspose.com/slides/it/cpp/) è una potente libreria C++ per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per convertire Image in JPG. Utilizzando **Aspose.Slides per C++**, qualsiasi sviluppatore o applicazione può convertire i file Image in JPG con poche righe di codice C++.

Come moderna API per l'elaborazione dei documenti, Aspose.Slides per C++ esporta rapidamente file Image in formati di file JPG. La libreria Aspose PowerPoint ti consente di convertire Image in JPG se molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti Image in JPG utilizzando C++" %}}
Per convertire Image in JPG, dovrai creare una presentazione dal file Image e salvarla come JPG.

{{% blocks/products/pf/agp/code-block title="Codice C++ per convertire Image in JPG" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
for (int32_t i = 0; i < pres->get_Slides()->get_Count(); i++)
{
    // Control hidden slides (do not render hidden slides)
    if (pres->get_Slides()->idx_get(i)->get_Hidden())
    {
        continue;
    }
    
    // Convert slide to a Bitmap object
    System::SharedPtr<Bitmap> bmp = pres->get_Slides()->idx_get(i)->GetThumbnail(2.f, 2.f);

    // Create file name for an image
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".jpg");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Jpeg());
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come convertire Image in JPG utilizzando Aspose.Slides per l'API C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per convertire Image in JPG in C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides per C++**](https://products.aspose.com/slides/it/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file di origine Image in C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertitore online gratuito" sectionDescription="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti Image in altri formati supportati" subTitle="Puoi anche convertire Image e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}