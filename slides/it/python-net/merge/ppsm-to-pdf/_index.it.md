---
title: Unisci file PPSM a PDF usando Python
url: /it/python-net/merge/ppsm-to-pdf/
keywords: Unisci PPSM a PDF, Unisci PPSM a PDF, Combina PPSM a PDF, PowerPoint, Presentazione, PDF, Python, Aspose
description: Unisci più file PPSM in Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Unisci i file PPSM a PDF insieme in Python" h2="API Python ad alta velocità e multipiattaforma che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Unisci PPSM a PDF in Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/it/python-net/) è una potente libreria Python per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per combinare più presentazioni PPSM. Quando unisci una presentazione a un'altra, combini efficacemente le loro diapositive in un'unica presentazione per ottenere un file. Aspose.Slides ti consente di unire due presentazioni in modi diversi. Puoi unire le presentazioni con tutte le loro forme, stili, testi, formattazione, commenti, animazioni, ecc. senza doversi preoccupare della perdita di qualità o dati.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Unisci i file PPSM a PDF usando Python" %}}
Per unire le presentazioni PowerPoint, dovrai clonare le diapositive da una presentazione all'altra.

{{% blocks/products/pf/agp/code-block title="Codice Python per unire più PPSM in un singolo file PDF" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.ppsm") as pres1:
    with slides.Presentation("presentation2.ppsm") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.pdf", slides.export.SaveFormat.PDF)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come unire PPSM a PDF usando Aspose.Slides per l'API Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per unire due file PPSM e salvare il risultato come PDF in Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/it/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto Python.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file di origine PPSM in Python.
```
pres1 = slides.Presentation('pres1.ppsm')
pres2 = slides.Presentation('pres2.ppsm')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combina i file PPSM usando il metodo [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva la presentazione e ottieni il risultato come singolo file PDF.
```
pres1.save("presentation.pdf", slides.export.SaveFormat.PDF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Esporta PPSM in altri formati supportati" subTitle="Puoi anche combinare PPSM e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-pptx/" name="PPSM TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-ppt/" name="PPSM TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-html/" name="PPSM TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-png/" name="PPSM TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-bmp/" name="PPSM TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-jpg/" name="PPSM TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-fodp/" name="PPSM TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-gif/" name="PPSM TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-odp/" name="PPSM TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-otp/" name="PPSM TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-pot/" name="PPSM TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-potm/" name="PPSM TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-potx/" name="PPSM TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-pps/" name="PPSM TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-pptm/" name="PPSM TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-svg/" name="PPSM TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-tiff/" name="PPSM TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/ppsm-to-xps/" name="PPSM TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}