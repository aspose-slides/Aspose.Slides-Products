---
title: A PPT prezentációs fájlok szerkesztése a Python használatával
url: /hu/python-net/redaction/ppt/
keywords: PPT szerkesztése, szöveg keresése és cseréje a következőben PPT, PPT prezentáció frissítése
description: Python forráskód a PPT prezentáció szövegének megkereséséhez és cseréjéhez.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="A PPT szerkesztése a Python használatával" h2="Készítse el saját Python-alkalmazásait a prezentációs fájlok szövegének megtalálásához és cseréjéhez szerveroldali API-k segítségével. Ismerje meg, hogyan kereshet és cserélhet szöveget a PPT prezentációk tartalmában, megjegyzéseiben vagy metaadataiban" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="A PPT prezentáció szerkesztése a következőn keresztül: Python" %}}
A Aspose.Slides for Python via .NET API-kkal az alapvető dokumentumok keresése és szöveg cseréje a tartalomban, megjegyzésekben, diajegyzetekben vagy metaadatokban néhány sornyi kóddal elvégezhető. Szöveg keresése és cseréje a PowerPointban és az OpenOffice-ban. Szöveg, megjegyzések, metaadatok szerkesztése a prezentációban reguláris kifejezéssel.
{{% blocks/products/pf/agp/code-block title="A PPT prezentáció szerkesztése a Python használatával" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.ppt") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A PPT szerkesztése a Python segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a PPT fájlok szerkesztéséhez." >}}

{{< blocks/products/pf/agp/step-autogen >}}
A PPT betöltése a Presentation egy példányával.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
A [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) módszerrel kereshet és cserélhet szöveget.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PPT formátumban
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPT szerkesztés élő bemutatók" sectionDescription="Keressen és cseréljen szöveget a PPT dokumentumok tartalmában, megjegyzéseiben vagy metaadataiban." >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott Redact formátumok" subTitle="A Python használatával a következő formátumokat is szerkesztheti:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/python-net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}