---
title: Rimuovi l'annotazione PPTX usando Python
weight: 4380
url: /it/python-net/annotation/pptx/ 
description: Codice sorgente Python per rimuovere i commenti di presentazione PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Rimuovi commenti e autori di commenti da PPTX in Python" h2="Crea i tuoi script Python per manipolare commenti e autori nei file di documenti utilizzando le API lato server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Rimuovi commenti da PPTX tramite Python" %}}
Per rimuovere le annotazioni dal file PPTX, utilizzeremo l'API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/it/python-net/) che è ricca di funzionalità, API di manipolazione dei documenti potente e facile da usare per la piattaforma Python.
{{% blocks/products/pf/agp/code-block title="Elimina annotazioni da PPTX - Python" offSpacer="true" %}}

```python

import aspose.slides as slides

with slides.Presentation("example.pptx") as presentation:
    # Deletes all comments from the presentation
    for author in presentation.comment_authors:
        author.comments.clear()

    # Deletes all authors
    presentation.comment_authors.clear()

    presentation.save("example_out.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Come rimuovere i commenti da PPTX tramite Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica PPTX con un'istanza della classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Itera su tutti gli autori del PPTX caricato
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Rimuovi tutti i commenti di un autore
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Rimuovi tutti gli autori alla fine
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di annotazione supportati" subTitle="Usando Python, si possono facilmente annotare altri formati inclusi." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}