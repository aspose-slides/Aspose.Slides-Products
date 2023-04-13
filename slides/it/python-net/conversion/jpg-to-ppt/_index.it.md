---
title: Converti JPG in PPT in Python
url: /it/python-net/conversion/jpg-to-ppt/
keywords: Converti JPG in PPT, JPG in PPT, PowerPoint, JPG, PPT, API Python, Libreria Python
description: Converti JPG in PPT in Python. Usa l'API della libreria Python per convertire le immagini JPG in PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti JPG in PPT in Python" h2="Potente API Python multipiattaforma per la conversione di JPG in PPT utilizzando il codice Python" >}}

{{% blocks/products/pf/feature-page-section h2="Converti JPG in PPT usando Aspose.Slides" %}}

[**Aspose.Slides per Python tramite .NET**](https://products.aspose.com/slides/it/python-net/) è una potente libreria Python utilizzata per creare, convertire e manipolare presentazioni PowerPoint, PDF, Documenti HTML e altri file. Quando converti JPG in PPT, stai essenzialmente creando una presentazione PowerPoint che contiene diapositive basate su immagini JPG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Converti JPG in PPT in Python" %}}
Utilizzando [**Aspose.Slides per Python tramite .NET**](https://products.aspose.com/slides/it/python-net/), puoi convertire un'immagine JPG in una presentazione PowerPoint con poche righe di codice:

{{% blocks/products/pf/agp/code-block title="Codice Python per convertire JPG in PPT" offSpacer="true" %}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.jpg", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.ppt", slides.export.SaveFormat.PPT)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Come convertire JPG in PPT in Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi la libreria come riferimento nel tuo progetto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea un'istanza della classe Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica l'immagine JPG che vuoi convertire in PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il file risultante come presentazione PPT.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertitore online gratuito" sectionDescription="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni di PowerPoint supportate" subTitle="Puoi anche convertire file in altri formati in PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}