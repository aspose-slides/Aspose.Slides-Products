---
title: Redigieren Sie PPT-Präsentationsdateien mit Python
url: /de/python-net/redaction/ppt/
keywords: PPT schwärzen, Text in PPT suchen und ersetzen, PPT-Präsentation aktualisieren
description: Python-Quellcode zum Suchen und Ersetzen von Text in der PPT-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="PPT mit Python redigieren" h2="Erstellen Sie Ihre eigenen Python-Apps, um mithilfe serverseitiger APIs Text in Präsentationsdateien zu suchen und zu ersetzen. Erfahren Sie, wie Sie Text in Inhalten, Kommentaren oder Metadaten von PPT-Präsentationen suchen und ersetzen" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Redigieren Sie die PPT-Präsentation über Python" %}}
Eine einfache Dokumentsuche und das Ersetzen von Text in Inhalten, Kommentaren, Foliennotizen oder Metadaten mit Aspose.Slides for Python via .NET-APIs kann mit nur wenigen Codezeilen durchgeführt werden. Suchen und ersetzen Sie Text in PowerPoint und OpenOffice. Bearbeiten Sie Text, Kommentare und Metadaten in der Präsentation über den Regexp-Datenabgleich.
{{% blocks/products/pf/agp/code-block title="PPT-Präsentation mit Python redigieren" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.ppt") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So redigieren Sie PPT über Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Schwärzen von PPT-Dateien." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie PPT mit einer Instanz von Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Verwenden Sie die Methode [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/), um Text zu suchen und zu ersetzen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis im Format PPT speichern
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online-Redaktions-Live-Demos von PPT" sectionDescription="Suchen und ersetzen Sie jetzt Text in Inhalten, Kommentaren oder Metadaten in PPT-Dokumenten." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Schwärzungsformate" subTitle="Mit Python können Sie auch die folgenden Formate redigieren:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}