---
title: Ontgrendel PPTX presentatiebestanden met Python
url: /nl/python-net/unlock/pptx/
keywords: Schrijfbeveiliging PPTX verwijderen, een PPTX ontsleutelen, presentatie PPTX ontgrendelen, beveiliging PPTX opheffen
description: Python broncode om de beveiliging van PPTX Presentatie te verwijderen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Ontgrendel PPTX met Python" h2="Bouw uw eigen Python-apps om wachtwoorden uit PowerPoint te verwijderen en presentatiebestanden te decoderen met behulp van server-side API's." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Versleuteling verwijderen uit PPTX-presentatie via Python" %}}
Met Aspose.Slides for Python via .NET kunt u de codering of wachtwoordbeveiliging op de PPTX-presentatie verwijderen. Op deze manier kunnen gebruikers de PPTX-presentatie zonder beperkingen openen of wijzigen.
{{% blocks/products/pf/agp/code-block title="Wachtwoordbeveiliging uitschakelen van PPTX met Python" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.pptx", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Schrijfbeveiliging verwijderen uit presentatie PPTX met behulp van Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.pptx") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.pptx", slides.export.SaveFormat.PPTX)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Wachtwoord verwijderen uit PPTX via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om de beveiliging van PPTX-bestanden te verwijderen." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad PPTX met een instantie van Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Verwijder schrijfbeveiliging met de klasse ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in PPTX formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde formaten" subTitle="Met Python kunt u ook de beveiliging van de volgende indelingen verwijderen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/unlock/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}