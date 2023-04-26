---
title: PPT-Präsentationsdateien mit Python schützen
url: /de/python-net/protect/ppt/
keywords: Schreibschutz PPT, Verschlüsseln einer PPT, Sperren von PPT Präsentation, Schützen von PPT
description: Python-Quellcode zum Schutz der PPT-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="PPT mit Python sperren oder mit Passwort schützen" h2="Erstellen Sie Ihre eigenen Python-Apps, um Präsentationsdateien mit serverseitigen APIs zu schützen." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Schützen einer PPT-Präsentation über Python" %}}
Mit Aspose.Slides for Python via .NET können Sie Ihre PPT-Präsentation vor dem Öffnen oder Ändern schützen, indem Sie ein Passwort festlegen. Um die gesperrte Präsentation zu öffnen oder zu ändern, muss ein Benutzer dann das Kennwort eingeben.
{{% blocks/products/pf/agp/code-block title="Verschlüsseln einer PPT-Präsentation mit Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Festlegen des Schreibschutzes für eine PPT-Präsentation mit Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So schützen Sie PPT über Python mit einem Passwort" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Schützen von PPT-Dateien." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie PPT mit einer Präsentationsinstanz
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Schützen Sie die Präsentation mit der ProtectionManager-Klasse
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis im Format PPT speichern
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte geschützte Formate" subTitle="Mit Python können Sie auch die folgenden Formate schützen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}