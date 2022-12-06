---
title: Unisci l'HTML all'immagine in C++
url: /it/cpp/merger/html-to-image/
keywords: Unisci HTML a immagine, HTML a immagine, Unisci HTML, Combina HTML, Immagine, API C++, Libreria C++
description: Unisci l'HTML all'immagine in C++. Usa l'API della libreria C++ per combinare l'HTML con l'immagine
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Unisci immagine in C++" h2="Libreria C++ ad alta velocità e multipiattaforma per unire HTML a immagini utilizzando il codice C++" >}}

{{% blocks/products/pf/feature-page-section h2="Unisci HTML all'immagine usando Aspose.Slides" %}}

[**Aspose.Slides per C++**](https://products.aspose.com/slides/it/cpp/) è una potente libreria C++ utilizzata per unire e manipolare presentazioni, documenti HTML e altri file. Quando unisci l'HTML all'immagine, combini effettivamente i contenuti nei documenti HTML per ottenere un'unica immagine. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Unisci HTML all'immagine in C++" %}}
Usando [**Aspose.Slides per C++**](https://products.aspose.com/slides/it/cpp/), puoi unire rapidamente i file immagine con poche righe di codice

{{% blocks/products/pf/agp/code-block title="Codice C++ per unire l'HTML all'immagine" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromHtml(htmlText1);
pres->get_Slides()->AddFromHtml(htmlText2);

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    auto fileName = String::Format(u"slide_{0}.png", index);
    slide->GetThumbnail()->Save(fileName, ImageFormat::get_Png());
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Come unire l'HTML all'immagine in C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installa **Aspose.Slides per C++**. Vedi [**Installazione**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi la libreria come riferimento nel tuo progetto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea un'istanza della classe Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica i documenti HTML che vuoi unire insieme.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva l'immagine risultante.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Unisci altri file" subTitle="Puoi anche combinare file in altri formati per ottenere un unico file" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
    
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}