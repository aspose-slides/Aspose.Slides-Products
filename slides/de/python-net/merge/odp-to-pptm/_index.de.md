---
title: ODP-Dateien mit Python in PPTM zusammenführen
url: /de/python-net/merge/odp-to-pptm/
keywords: ODP mit PPTM zusammenführen, ODP mit PPTM verbinden, ODP mit PPTM kombinieren, PowerPoint, Präsentation, PPTM, Python, Aspose
description: Führen Sie mehrere ODP-Dateien in Python zusammen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Führen Sie ODP-Dateien in PPTM in Python zusammen" h2="Hochgeschwindigkeits- und plattformübergreifende Python-API, die bei der Entwicklung von Anwendungen mit der Fähigkeit hilft, Microsoft PowerPoint- und OpenOffice-Präsentationsdateien ohne die Verwendung von Software wie Microsoft oder Open Office, Adobe PDF zu erstellen, zusammenzuführen, zu überprüfen oder zu konvertieren." >}}

{{% blocks/products/pf/feature-page-section h2="Führen Sie ODP in PPTM in Python zusammen" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/de/python-net/) ist eine leistungsstarke Python-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten, mehrere ODP-Präsentationen zu kombinieren. Wenn Sie eine Präsentation mit einer anderen zusammenführen, kombinieren Sie deren Folien effektiv in einer einzigen Präsentation, um eine Datei zu erhalten. Mit Aspose.Slides können Sie zwei Präsentationen auf unterschiedliche Weise zusammenführen. Sie können Präsentationen mit all ihren Formen, Stilen, Texten, Formatierungen, Kommentaren, Animationen usw. zusammenführen, ohne sich um Qualitäts- oder Datenverluste sorgen zu müssen.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ODP-Dateien mit Python in PPTM zusammenführen" %}}
Um die PowerPoint-Präsentationen zusammenzuführen, müssen Sie die Folien von einer Präsentation zur anderen klonen.

{{% blocks/products/pf/agp/code-block title="Python-Code zum Zusammenführen mehrerer ODP in einer einzigen PPTM-Datei" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.odp") as pres1:
    with slides.Presentation("presentation2.odp") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.pptm", slides.export.SaveFormat.PPTM)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So führen Sie ODP mit PPTM mithilfe von Aspose.Slides for Python API zusammen" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte, um zwei ODP-Dateien zusammenzuführen und das Ergebnis als PPTM in Python zu speichern." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/de/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Ihrem Python-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öffnen Sie die Quelldateien ODP in Python.
```
pres1 = slides.Presentation('pres1.odp')
pres2 = slides.Presentation('pres2.odp')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinieren Sie ODP-Dateien mit der Methode [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Speichern Sie die Präsentation und erhalten Sie das Ergebnis als einzelne PPTM-Datei.
```
pres1.save("presentation.pptm", slides.export.SaveFormat.PPTM)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="ODP in andere unterstützte Formate exportieren" subTitle="Sie können ODP auch kombinieren und in anderen Dateiformaten speichern. Siehe unten alle unterstützten Formate" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-pptx/" name="ODP TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-ppt/" name="ODP TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-pdf/" name="ODP TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-html/" name="ODP TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-png/" name="ODP TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-bmp/" name="ODP TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-jpg/" name="ODP TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-fodp/" name="ODP TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-gif/" name="ODP TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-otp/" name="ODP TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-pot/" name="ODP TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-potm/" name="ODP TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-potx/" name="ODP TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-pps/" name="ODP TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-ppsm/" name="ODP TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-ppsx/" name="ODP TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-svg/" name="ODP TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-tiff/" name="ODP TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/odp-to-xps/" name="ODP TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}