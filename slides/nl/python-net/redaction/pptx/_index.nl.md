---
title: Bewerk PPTX presentatiebestanden met Python
url: /nl/python-net/redaction/pptx/
keywords: Bewerk PPTX, zoek en vervang tekst in PPTX, update PPTX presentatie
description: Python broncode om tekst in PPTX Presentatie te zoeken en te vervangen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Bewerk PPTX met Python" h2="Bouw uw eigen Python-apps om tekst in presentatiebestanden te zoeken en te vervangen met behulp van server-side API's. Leer hoe u tekst kunt zoeken en vervangen in inhoud, opmerkingen of metadata van PPTX presentaties" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Presentatie PPTX redigeren via Python" %}}
Een basisdocument zoeken en tekst vervangen in inhoud, opmerkingen, dia-notities of metadata met Aspose.Slides for Python via .NET API's kan worden gedaan met slechts enkele regels code. Zoek en vervang tekst in PowerPoint en OpenOffice. Bewerk tekst, opmerkingen, metadata in presentatie via regexp data matching.
{{% blocks/products/pf/agp/code-block title="Bewerk PPTX presentatie met Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.pptx") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="PPTX redigeren via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om PPTX-bestanden te redigeren." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad PPTX met een instantie van Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gebruik de methode [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) om tekst te zoeken en te vervangen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in PPTX formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX redactie live demo's" sectionDescription="Zoek en vervang nu tekst in inhoud, opmerkingen of metadata in PPTX documenten." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde Redact-indelingen" subTitle="Met Python kunt u ook de volgende indelingen redigeren:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}