---
title: Converti HTML in XML in Python
url: /it/python-net/conversion/html-to-xml/
keywords: HTML in XML, conversione di HTML in XML, API Python, libreria Python, HTML, XML
description: Converti HTML in XML in Python. Usa l'API della libreria Python per convertire i file HTML in XML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti HTML in XML in Python" h2="Libreria Python ad alta velocità e multipiattaforma che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converti HTML in XML in Python" %}}

[**Aspose.Slides per Python tramite .NET**](https://products.aspose.com/slides/it/python-net/) è una potente libreria Python per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per convertire HTML in XML. Utilizzando **Aspose.Slides per Python tramite .NET**, qualsiasi sviluppatore o applicazione può convertire i file HTML in XML con poche righe di codice Python.

Come moderna API di elaborazione dei documenti, Aspose.Slides per Python esporta rapidamente file HTML in formati di file XML. La libreria Aspose PowerPoint ti consente di convertire HTML in XML se molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti HTML in XML usando Python" %}}
Per convertire HTML in XML, dovrai creare una presentazione dal file HTML e salvarla come XML.

{{% blocks/products/pf/agp/code-block title="Codice Python per convertire HTML in XML" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open(dataDir + "file.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)
    for index in range(pres.slides.length):
        slide = pres.slides[index]

        with open("slide-{index}.xml".format(index = index), "wb") as file:
            slide.write_as_svg(file)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come convertire HTML in XML utilizzando Aspose.Slides per l'API Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per convertire HTML in XML in Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/it/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file di origine HTML in Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file XML.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertitore online gratuito" sectionDescription="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti HTML in altri formati supportati" subTitle="Puoi anche convertire HTML e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/conversion/html-to-tiff/" name="HTML TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}