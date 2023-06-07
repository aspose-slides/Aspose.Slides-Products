---
title: Oldja fel a PPTX prezentációs fájlokat a Python használatával
url: /hu/python-net/unlock/pptx/
keywords: Írásvédelem eltávolítása PPTX, PPTX kód visszafejtése, PPTX bemutató feloldása, PPTX védelem feloldása
description: Python forráskód a PPTX prezentáció védelmének eltávolításához.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Oldja fel a PPTX zárolását a Python használatával" h2="Készítse el saját Python-alkalmazásait, amelyek segítségével eltávolíthatja a jelszavakat a PowerPointból, és dekódolhatja a prezentációs fájlokat szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Titkosítás eltávolítása a PPTX prezentációból a következőn keresztül: Python" %}}
A Aspose.Slides for Python via .NET használatával eltávolíthatja a titkosítást vagy a jelszavas védelmet a PPTX bemutatóról. Így a felhasználók korlátozás nélkül hozzáférhetnek vagy módosíthatják a PPTX prezentációt.
{{% blocks/products/pf/agp/code-block title="A jelszavas védelem letiltása a(z) PPTX alkalmazásban a(z) Python használatával" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.pptx", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Az írásvédelem eltávolítása a PPTX prezentációból a Python használatával" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.pptx") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.pptx", slides.export.SaveFormat.PPTX)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jelszó eltávolítása a(z) PPTX eszközről a(z) Python segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a PPTX fájlok védelmének eltávolítására." >}}

{{< blocks/products/pf/agp/step-autogen >}}
A PPTX betöltése a Presentation egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Távolítsa el az írásvédelmet a ProtectionManager osztály segítségével
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PPTX formátumban
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott formátumok" subTitle="A Python használatával a következő formátumokból is eltávolíthatja a védelmet:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/unlock/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}