---
title: Unisci SVG a PNG in C++
url: /it/cpp/merger/svg-to-png/
keywords: Unisci SVG a PNG, SVG a PNG, Unisci SVG a PNG, Combina SVG a PNG, API C++, Libreria C++
description: Unisci SVG a PNG in C++. Utilizza l'API della libreria C++ per combinare file SVG e PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Unisci SVG a PNG in C++" h2="Libreria C++ ad alta velocità e multipiattaforma per unire immagini SVG a PNG utilizzando il codice C++" >}}

{{% blocks/products/pf/feature-page-section h2="Unisci SVG a PNG usando Aspose.Slides" %}}

[**Aspose.Slides per C++**](https://products.aspose.com/slides/it/cpp/) è una potente libreria C++ utilizzata per unire e manipolare presentazioni, immagini e altri file. Quando unisci SVG a PNG, stai effettivamente combinando immagini SVG per ottenere un'immagine PNG.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Unisci SVG a PNG in C++" %}}
Utilizzando [**Aspose.Slides per C++**](https://products.aspose.com/slides/it/cpp/), puoi unire rapidamente i file SVG a PNG con poche righe di codice

{{% blocks/products/pf/agp/code-block title="Codice C++ per unire SVG a PNG" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();
String svgContent = IO::File::ReadAllText(svgPath);
	SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(svgContent);
	SharedPtr<IPPImage> ppImage = pres->get_Images()->AddImage(svgImage);
	pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, static_cast<float>(ppImage->get_Width()), static_cast<float>(ppImage->get_Height()), ppImage);

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    auto fileName = String::Format(u"slide_{0}.png", index);
    slide->GetThumbnail()->Save(fileName, ImageFormat::get_Png());
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Come unire SVG a PNG in C++" >}}


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
Carica i file SVG che vuoi unire insieme.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva l'immagine PNG risultante.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Unisci altri file" subTitle="Puoi anche combinare file in altri formati per ottenere un unico file" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}