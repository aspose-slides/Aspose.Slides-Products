---
title: PPS-Dateien mit Python in JPG zusammenführen
url: /de/python-net/merge/pps-to-jpg/
keywords: PPS mit JPG zusammenführen, PPS mit JPG verbinden, PPS mit JPG kombinieren, PowerPoint, Präsentation, JPG, Python, Aspose
description: Führen Sie mehrere PPS-Dateien in Python zusammen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Führen Sie PPS-Dateien in JPG in Python zusammen" h2="Hochgeschwindigkeits- und plattformübergreifende Python-API, die bei der Entwicklung von Anwendungen mit der Fähigkeit hilft, Microsoft PowerPoint- und OpenOffice-Präsentationsdateien ohne die Verwendung von Software wie Microsoft oder Open Office, Adobe PDF zu erstellen, zusammenzuführen, zu überprüfen oder zu konvertieren." >}}

{{% blocks/products/pf/feature-page-section h2="Führen Sie PPS in JPG in Python zusammen" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/de/python-net/) ist eine leistungsstarke Python-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten, mehrere PPS-Präsentationen zu kombinieren. Wenn Sie eine Präsentation mit einer anderen zusammenführen, kombinieren Sie deren Folien effektiv in einer einzigen Präsentation, um eine Datei zu erhalten. Mit Aspose.Slides können Sie zwei Präsentationen auf unterschiedliche Weise zusammenführen. Sie können Präsentationen mit all ihren Formen, Stilen, Texten, Formatierungen, Kommentaren, Animationen usw. zusammenführen, ohne sich um Qualitäts- oder Datenverluste sorgen zu müssen.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PPS-Dateien mit Python in JPG zusammenführen" %}}
Um die PowerPoint-Präsentationen zusammenzuführen, müssen Sie die Folien von einer Präsentation zur anderen klonen.

{{% blocks/products/pf/agp/code-block title="Python-Code zum Zusammenführen mehrerer PPS in einer einzigen JPG-Datei" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation1.pps") as pres1:
    with slides.Presentation("presentation2.pps") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So führen Sie PPS mit JPG mithilfe von Aspose.Slides for Python API zusammen" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte, um zwei PPS-Dateien zusammenzuführen und das Ergebnis als JPG in Python zu speichern." >}}

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
Öffnen Sie die Quelldateien PPS in Python.
```
pres1 = slides.Presentation('pres1.pps')
pres2 = slides.Presentation('pres2.pps')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinieren Sie PPS-Dateien mit der Methode [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Speichern Sie die Präsentation und erhalten Sie das Ergebnis als einzelne JPG-Datei.
```
for slide in pres1.slides:
    slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="PDF-Dateien online zusammenführen" sectionDescription="[Wie man PDF in Python zusammenführt](https://products.aspose.com/slides/de/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="PPS in andere unterstützte Formate exportieren" subTitle="Sie können PPS auch kombinieren und in anderen Dateiformaten speichern. Siehe unten alle unterstützten Formate" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-pptx/" name="PPS TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-ppt/" name="PPS TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-pdf/" name="PPS TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-html/" name="PPS TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-png/" name="PPS TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-bmp/" name="PPS TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-fodp/" name="PPS TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-gif/" name="PPS TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-odp/" name="PPS TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-otp/" name="PPS TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-pot/" name="PPS TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-potm/" name="PPS TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-potx/" name="PPS TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-ppsm/" name="PPS TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-ppsx/" name="PPS TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-pptm/" name="PPS TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-svg/" name="PPS TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-tiff/" name="PPS TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-net/merge/pps-to-xps/" name="PPS TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}