---
title: Odemkněte ODP prezentační soubory pomocí Python
url: /cs/python-net/unlock/odp/
keywords: Odebrat ochranu proti zápisu ODP, dešifrovat ODP, odemknout prezentaci ODP, zrušit ochranu ODP
description: Zdrojový kód Python pro odstranění ochrany z prezentace ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Odemkněte ODP pomocí Python" h2="Sestavte si vlastní aplikace pro Python, abyste mohli odstraňovat hesla z PowerPointu a dešifrovat soubory prezentací pomocí rozhraní API na straně serveru." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Odstranění šifrování z prezentace ODP prostřednictvím Python" %}}
Pomocí Aspose.Slides for Python via .NET můžete z prezentace ODP odstranit šifrování nebo ochranu heslem. Tímto způsobem mohou uživatelé přistupovat k prezentaci ODP nebo ji upravovat bez omezení.
{{% blocks/products/pf/agp/code-block title="Deaktivace ochrany heslem z ODP pomocí Python" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.odp", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Odebrání ochrany proti zápisu z prezentace ODP pomocí Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.odp") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.odp", slides.export.SaveFormat.ODP)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak odstranit heslo z ODP prostřednictvím Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k odstranění ochrany ze souborů ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte ODP s instancí Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Odstraňte ochranu proti zápisu pomocí třídy ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledek ve formátu ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty" subTitle="Pomocí Python můžete také odebrat ochranu z následujících formátů:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}