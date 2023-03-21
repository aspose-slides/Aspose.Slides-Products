---
title: Converti Image in PDF in Python
url: /it/python-net/conversion/image-to-pdf/
keywords: Image in PDF, conversione di Image in PDF, API Python, libreria Python, Image, PDF
description: Converti Image in PDF in Python. Usa l'API della libreria Python per convertire i file Image in PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti Image in PDF in Python" h2="Libreria Python ad alta velocità e multipiattaforma che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converti Image in PDF in Python" %}}

[**Aspose.Slides per Python tramite .NET**](https://products.aspose.com/slides/it/python-net/) è una potente libreria Python per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per convertire Image in PDF. Utilizzando **Aspose.Slides per Python tramite .NET**, qualsiasi sviluppatore o applicazione può convertire i file Image in PDF con poche righe di codice Python.

Come moderna API di elaborazione dei documenti, Aspose.Slides per Python esporta rapidamente file Image in formati di file PDF. La libreria Aspose PowerPoint ti consente di convertire Image in PDF se molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti Image in PDF usando Python" %}}
Per convertire Image in PDF, dovrai creare una presentazione dal file Image e salvarla come PDF.

{{% blocks/products/pf/agp/code-block title="Codice Python per convertire Image in PDF" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    pres.save("index.pdf", slides.export.SaveFormat.PDF)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come convertire Image in PDF utilizzando Aspose.Slides per l'API Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per convertire Image in PDF in Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/it/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file di origine Image in Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertitore online gratuito" sectionDescription="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti Image in altri formati supportati" subTitle="Puoi anche convertire Image e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}