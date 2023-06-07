---
title: Sblocca i file di presentazione PPT utilizzando Python
url: /it/python-net/unlock/ppt/
keywords: Rimuovi la protezione da scrittura PPT, decodifica di una presentazione PPT, sblocca presentazione PPT, rimuovi protezione PPT
description: codice sorgente Python per rimuovere la protezione dalla presentazione PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Sblocca PPT utilizzando Python" h2="Crea le tue app Python per rimuovere le password da PowerPoint e decrittografare i file delle presentazioni utilizzando le API lato server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Rimozione della crittografia dalla presentazione PPT tramite Python" %}}
Utilizzando Aspose.Slides for Python via .NET, puoi rimuovere la crittografia o la protezione tramite password sulla presentazione PPT. In questo modo, gli utenti possono accedere o modificare la presentazione PPT senza restrizioni.
{{% blocks/products/pf/agp/code-block title="Disattivazione della protezione con password da PPT utilizzando Python" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.ppt", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Rimozione della protezione da scrittura dalla presentazione PPT utilizzando Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.ppt") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.ppt", slides.export.SaveFormat.PPT)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come rimuovere la password da PPT tramite Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per rimuovere la protezione dai file PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica PPT con un'istanza di Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Rimuovere la protezione da scrittura utilizzando la classe ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato nel formato PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Altri formati supportati" subTitle="Utilizzando Python, puoi anche rimuovere la protezione dai seguenti formati:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/python-net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}