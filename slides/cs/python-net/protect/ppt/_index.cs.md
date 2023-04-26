---
title: Chraňte soubory prezentací PPT pomocí Python
url: /cs/python-net/protect/ppt/
keywords: Ochrana proti zápisu PPT, šifrování PPT, zámek PPT prezentace, ochrana PPT
description: Zdrojový kód Python k ochraně prezentace PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Uzamknout nebo chránit heslem PPT pomocí Python" h2="Vytvářejte si vlastní aplikace pro Python, abyste chránili prezentační soubory pomocí rozhraní API na straně serveru." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Ochrana PPT prezentace prostřednictvím Python" %}}
Pomocí Aspose.Slides for Python via .NET můžete chránit svou prezentaci PPT před otevřením nebo úpravou nastavením hesla. Poté, aby uživatel mohl otevřít nebo upravit zamčenou prezentaci, musí zadat heslo.
{{% blocks/products/pf/agp/code-block title="Šifrování prezentace ve formátu PPT pomocí Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Nastavení ochrany proti zápisu na prezentaci ve formátu PPT pomocí Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak chránit heslem PPT prostřednictvím Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k ochraně souborů PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte PPT s instancí Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chraňte prezentaci pomocí třídy ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledek ve formátu PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty ochrany" subTitle="Pomocí Python můžete chránit také následující formáty:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}