---
title: Unisci file ODP a POT usando Python
url: /it/python-net/merge/odp-to-pot/
keywords: Unisci ODP a POT, Unisci ODP a POT, Combina ODP a POT, PowerPoint, Presentazione, POT, Python, Aspose
description: Unisci più file ODP in Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Unisci i file ODP a POT insieme in Python" h2="API Python ad alta velocità e multipiattaforma che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Unisci ODP a POT in Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/it/python-net/) è una potente libreria Python per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per combinare più presentazioni ODP. Quando unisci una presentazione a un'altra, combini efficacemente le loro diapositive in un'unica presentazione per ottenere un file. Aspose.Slides ti consente di unire due presentazioni in modi diversi. Puoi unire le presentazioni con tutte le loro forme, stili, testi, formattazione, commenti, animazioni, ecc. senza doversi preoccupare della perdita di qualità o dati.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Unisci i file ODP a POT usando Python" %}}
Per unire le presentazioni PowerPoint, dovrai clonare le diapositive da una presentazione all'altra.

{{% blocks/products/pf/agp/code-block title="Codice Python per unire più ODP in un singolo file POT" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.odp") as pres1:
    with slides.Presentation("presentation2.odp") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.pot", slides.export.SaveFormat.POT)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come unire ODP a POT usando Aspose.Slides per l'API Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per unire due file ODP e salvare il risultato come POT in Python." >}}

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
Apri i file di origine ODP in Python.
```
pres1 = slides.Presentation('pres1.odp')
pres2 = slides.Presentation('pres2.odp')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combina i file ODP usando il metodo [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva la presentazione e ottieni il risultato come singolo file POT.
```
pres1.save("presentation.pot", slides.export.SaveFormat.POT)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Esporta ODP in altri formati supportati" subTitle="Puoi anche combinare ODP e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-pptx/" name="ODP TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-ppt/" name="ODP TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-pdf/" name="ODP TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-html/" name="ODP TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-png/" name="ODP TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-bmp/" name="ODP TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-jpg/" name="ODP TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-fodp/" name="ODP TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-gif/" name="ODP TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-otp/" name="ODP TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-potm/" name="ODP TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-potx/" name="ODP TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-pps/" name="ODP TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-ppsm/" name="ODP TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-ppsx/" name="ODP TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-pptm/" name="ODP TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-svg/" name="ODP TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-tiff/" name="ODP TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/merge/odp-to-xps/" name="ODP TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}