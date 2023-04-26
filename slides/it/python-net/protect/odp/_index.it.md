---
title: Proteggi i file di presentazione ODP utilizzando Python
url: /it/python-net/protect/odp/
keywords: Protezione da scrittura ODP, crittografia di una presentazione ODP, blocco ODP, protezione ODP
description: Python codice sorgente per proteggere la presentazione ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Blocca o proteggi con password ODP utilizzando Python" h2="Crea le tue app Python per proteggere i file di presentazione utilizzando le API lato server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Protezione di una presentazione ODP tramite Python" %}}
Utilizzando Aspose.Slides for Python via .NET, puoi proteggere la tua presentazione ODP dall'apertura o dalla modifica impostando una password. Quindi, per aprire o modificare la presentazione bloccata, un utente deve fornire la password.
{{% blocks/products/pf/agp/code-block title="Crittografia di una presentazione ODP utilizzando Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.odp") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Impostazione della protezione da scrittura su una presentazione ODP utilizzando Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.odp") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come proteggere con password ODP tramite Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per proteggere i file ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica ODP con un'istanza di Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Proteggi la presentazione usando la classe ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato nel formato ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di protezione supportati" subTitle="Utilizzando Python, puoi anche proteggere i seguenti formati:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}