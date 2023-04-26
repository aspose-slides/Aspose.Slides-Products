---
title: Bescherm presentatiebestanden van PPT met Python
url: /nl/python-net/protect/ppt/
keywords: Schrijfbeveiliging PPT, een PPT coderen, PPT-presentatie vergrendelen, PPT beschermen
description: Python broncode om PPT Presentatie te beschermen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Vergrendel of beveilig PPT met Python" h2="Bouw uw eigen Python-apps om presentatiebestanden te beschermen met behulp van server-side API's." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Een PPT-presentatie beveiligen via Python" %}}
Met Aspose.Slides for Python via .NET kunt u uw PPT-presentatie beschermen tegen openen of wijzigen door een wachtwoord in te stellen. Om vervolgens de vergrendelde presentatie te openen of te wijzigen, moet een gebruiker het wachtwoord opgeven.
{{% blocks/products/pf/agp/code-block title="Een PPT-presentatie versleutelen met Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Schrijfbeveiliging instellen op een PPT-presentatie met Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hoe PPT met een wachtwoord te beveiligen via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om PPT bestanden te beschermen." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad PPT met een instantie van Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bescherm de presentatie met de klasse ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in PPT formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde beveiligingsindelingen" subTitle="Met Python kunt u ook de volgende indelingen beveiligen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}