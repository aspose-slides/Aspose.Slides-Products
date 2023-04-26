---
title: Bescherm presentatiebestanden van ODP met Python
url: /nl/python-net/protect/odp/
keywords: Schrijfbeveiliging ODP, een ODP coderen, ODP-presentatie vergrendelen, ODP beschermen
description: Python broncode om ODP Presentatie te beschermen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Vergrendel of beveilig ODP met Python" h2="Bouw uw eigen Python-apps om presentatiebestanden te beschermen met behulp van server-side API's." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Een ODP-presentatie beveiligen via Python" %}}
Met Aspose.Slides for Python via .NET kunt u uw ODP-presentatie beschermen tegen openen of wijzigen door een wachtwoord in te stellen. Om vervolgens de vergrendelde presentatie te openen of te wijzigen, moet een gebruiker het wachtwoord opgeven.
{{% blocks/products/pf/agp/code-block title="Een ODP-presentatie versleutelen met Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.odp") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Schrijfbeveiliging instellen op een ODP-presentatie met Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.odp") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hoe ODP met een wachtwoord te beveiligen via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om ODP bestanden te beschermen." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad ODP met een instantie van Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bescherm de presentatie met de klasse ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in ODP formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde beveiligingsindelingen" subTitle="Met Python kunt u ook de volgende indelingen beveiligen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}