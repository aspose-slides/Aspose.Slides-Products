---
title: Converti PNG in SVG in Python
url: /it/python-net/conversion/png-to-svg/
keywords: PNG in SVG, conversione di PNG in SVG, API Python, libreria Python, PNG, SVG
description: Converti PNG in SVG in Python. Usa l'API della libreria Python per convertire i file PNG in SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti PNG in SVG in Python" h2="Libreria Python ad alta velocità e multipiattaforma che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converti PNG in SVG in Python" %}}

[**Aspose.Slides per Python tramite .NET**](https://products.aspose.com/slides/it/python-net/) è una potente libreria Python per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per convertire PNG in SVG. Utilizzando **Aspose.Slides per Python tramite .NET**, qualsiasi sviluppatore o applicazione può convertire i file PNG in SVG con poche righe di codice Python.

Come moderna API di elaborazione dei documenti, Aspose.Slides per Python esporta rapidamente file PNG in formati di file SVG. La libreria Aspose PowerPoint ti consente di convertire PNG in SVG se molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti PNG in SVG usando Python" %}}
Per convertire PNG in SVG, dovrai creare una presentazione dal file PNG e salvarla come SVG.

{{% blocks/products/pf/agp/code-block title="Codice Python per convertire PNG in SVG" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for index in range(pres.slides.length):
        slide = pres.slides[index]

        with open("slide-{index}.svg".format(index = index), "wb") as file:
            slide.write_as_svg(file)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come convertire PNG in SVG utilizzando Aspose.Slides per l'API Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per convertire PNG in SVG in Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/it/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file di origine PNG in Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertitore online gratuito" sectionDescription="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti PNG in altri formati supportati" subTitle="Puoi anche convertire PNG e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/png-to-pdf/" name="PNG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}