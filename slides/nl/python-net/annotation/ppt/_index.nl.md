---
title: Verwijder PPT-annotatie met behulp van Python
weight: 4380
url: /nl/python-net/annotation/ppt/ 
description: Python-broncode om opmerkingen over PPT-presentaties te verwijderen
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Verwijder opmerkingen en auteurs van opmerkingen uit PPT in Python" h2="Bouw uw eigen Python-scripts om opmerkingen en auteurs in documentbestanden te manipuleren met behulp van server-side API's." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Verwijder opmerkingen van PPT via Python" %}}
Om annotaties uit het PPT-bestand te verwijderen, gebruiken we [Aspose.Slides voor Python via .NET](https://products.aspose.com/slides/nl/python-net/) API, een feature-rijke, krachtige en gebruiksvriendelijke API voor documentmanipulatie voor het Python-platform.
{{% blocks/products/pf/agp/code-block title="Annotaties verwijderen uit PPT - Python" offSpacer="true" %}}

```python

import aspose.slides as slides

with slides.Presentation("example.ppt") as presentation:
    # Deletes all comments from the presentation
    for author in presentation.comment_authors:
        author.comments.clear()

    # Deletes all authors
    presentation.comment_authors.clear()

    presentation.save("example_out.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Opmerkingen van PPT verwijderen via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad PPT met een exemplaar van de Presentation-klasse
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Herhaal alle auteurs van geladen PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Verwijder alle opmerkingen van een auteur
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Verwijder alle auteurs aan het einde
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde annotatieformaten" subTitle="Met behulp van Python kan men eenvoudig andere formaten annoteren, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}