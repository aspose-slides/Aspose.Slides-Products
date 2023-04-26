---
title: Chraňte soubory prezentací ODP pomocí Python
url: /cs/python-net/protect/odp/
keywords: Ochrana proti zápisu ODP, šifrování ODP, zámek ODP prezentace, ochrana ODP
description: Zdrojový kód Python k ochraně prezentace ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Uzamknout nebo chránit heslem ODP pomocí Python" h2="Vytvářejte si vlastní aplikace pro Python, abyste chránili prezentační soubory pomocí rozhraní API na straně serveru." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Ochrana ODP prezentace prostřednictvím Python" %}}
Pomocí Aspose.Slides for Python via .NET můžete chránit svou prezentaci ODP před otevřením nebo úpravou nastavením hesla. Poté, aby uživatel mohl otevřít nebo upravit zamčenou prezentaci, musí zadat heslo.
{{% blocks/products/pf/agp/code-block title="Šifrování prezentace ve formátu ODP pomocí Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.odp") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Nastavení ochrany proti zápisu na prezentaci ve formátu ODP pomocí Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.odp") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak chránit heslem ODP prostřednictvím Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k ochraně souborů ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte ODP s instancí Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chraňte prezentaci pomocí třídy ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledek ve formátu ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty ochrany" subTitle="Pomocí Python můžete chránit také následující formáty:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}