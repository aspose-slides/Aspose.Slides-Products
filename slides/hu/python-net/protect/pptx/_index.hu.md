---
title: A PPTX prezentációs fájlok védelme a Python használatával
url: /hu/python-net/protect/pptx/
keywords: Írásvédelem PPTX, PPTX titkosítása, PPTX bemutató zárolása, PPTX védelme
description: Python forráskód a PPTX prezentáció védelmére.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Zárolás vagy jelszavas védelem PPTX a Python használatával" h2="Készítse el saját Python alkalmazásait a prezentációs fájlok védelméhez szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="A PPTX prezentáció védelme a Python segítségével" %}}
A Aspose.Slides for Python via .NET használatával jelszó megadásával megvédheti PPTX prezentációját a megnyitástól vagy módosítástól. Ezután a zárolt bemutató megnyitásához vagy módosításához a felhasználónak meg kell adnia a jelszót.
{{% blocks/products/pf/agp/code-block title="PPTX prezentáció titkosítása a Python használatával" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.pptx") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Írásvédelem beállítása PPTX prezentációra a Python használatával" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.pptx") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A PPTX jelszavas védelme a Python segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a PPTX fájlok védelméhez." >}}

{{< blocks/products/pf/agp/step-autogen >}}
A PPTX betöltése a Presentation egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Védje a prezentációt a ProtectionManager osztály segítségével
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PPTX formátumban
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott védelmi formátumok" subTitle="A Python használatával a következő formátumokat is védheti:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}