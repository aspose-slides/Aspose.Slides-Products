---
title: Entfernen Sie die PPTX-Anmerkung mit Python
weight: 4380
url: /de/python-net/annotation/pptx/ 
description: Python-Quellcode zum Entfernen von PPTX-Präsentationskommentaren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Entfernen Sie Kommentare und Kommentarautoren aus PPTX in Python" h2="Erstellen Sie Ihre eigenen Python-Skripte, um Kommentare und Autoren in Dokumentdateien mithilfe serverseitiger APIs zu manipulieren." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Kommentare aus PPTX über Python entfernen" %}}
Um Anmerkungen aus der PPTX-Datei zu entfernen, verwenden wir die API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/de/python-net/), die eine funktionsreiche, leistungsstarke und benutzerfreundliche API zur Dokumentenbearbeitung für die Python-Plattform.
{{% blocks/products/pf/agp/code-block title="Löschen Sie Anmerkungen aus PPTX - Python" offSpacer="true" %}}

```python

import aspose.slides as slides

with slides.Presentation("example.pptx") as presentation:
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

{{< blocks/products/pf/feature-page-section  h2="So entfernen Sie Kommentare aus PPTX über Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie PPTX mit einer Instanz der Präsentationsklasse
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Über alle Autoren von geladenem PPTX iterieren
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Alle Kommentare eines Autors entfernen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Entfernen Sie am Ende alle Autoren
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Anmerkungsformate" subTitle="Mit Python kann man leicht andere Formate kommentieren, einschließlich." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}