---
title: Konvertieren Sie PPTM in Python in SVG
weight: 2610
url: /de/python-net/conversion/pptm-to-svg/ 
keywords: "Convert, PowerPoint, PPTM, SVG, Presentation, Python"
description: Beispielcode für die Umwandlung von PPTM in SVG Python. Verwenden Sie die PowerPoint-Python-API für die Stapelkonvertierung von PPTM-Dateien in SVG-Dateien.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie PPTM in Python in SVG" h2="Leistungsstarke PowerPoint-Python-Bibliothek zum Konvertieren von PPTM in SVG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Konvertieren Sie PPTM in Python in SVG" %}}

Müssen Sie PPTM-Dateien programmgesteuert in SVG konvertieren? Mit [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/python-net/) kann jeder Entwickler mit nur wenigen Zeilen Python-Code PPTM in das SVG-Format konvertieren.

Als moderne Präsentationsverarbeitungs-API erstellt Aspose.Slides für Python schnell SVG aus PPTM. Testen Sie die Qualität der Umwandlung von PPTM in SVG direkt in Ihrem [Browser](https://products.aspose.app/slides/conversion). Mit der Aspose PowerPoint PPTX-Bibliothek können Sie PPTM-Dateien in viele gängige Formate konvertieren.

Sie können die Bibliothek von [PyPI](https://pypi.org/project/Aspose.Slides/) mit dem folgenden Pip-Befehl installieren:

{{% blocks/products/pf/agp/code-block title="Konsole/Terminal" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="So konvertieren Sie PPTM in SVG in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Konvertieren einer PPTM-Datei in SVG mit Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie die PPTM-Datei mit einer Instanz der Präsentationsklasse
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Rufen Sie die Methode „save“ auf, während Sie den Pfad der Ausgabedatei und SaveFormat.SVG als Parameter angeben
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Die PPTM-Datei wird unter dem angegebenen Pfad gespeichert
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Stellen Sie vor dem Ausführen des Beispielquellcodes für die Python-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows- oder Linux-basiertes Betriebssystem (siehe [mehr](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 oder höher
- Aspose.Slides für Python, auf die in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dieser Beispielcode zeigt die PPTM-zu-SVG-Python-Konvertierung" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pptm") as presentation:
    for slide in presentation.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Speichern Sie PPTM als SVG in Python" %}}
Verwenden Sie die kostenlose App, um eine Demonstration des PPTM-zu-SVG-Konvertierungsprozesses zu sehen. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="pptm-to-svg"
        sectionTitle="Kostenlose App, um PPTM in SVG zu konvertieren" 
        sectionDescription="[Probieren Sie unsere kostenlose Video App aus](https://products.aspose.app/slides/video/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können PPTM auch in viele andere Dateiformate konvertieren. Weitere unterstützte Konvertierungen finden Sie weiter unten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Bitmap-Bild" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-emf/" name="PPTM TO EMF" description="Verbessertes Metafile-Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-fodp/" name="PPTM TO FODP" description="OpenDocument Flat XML-Präsentation" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Grafisches Austauschformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-html/" name="PPTM TO HTML" description="Hypertext-Auszeichnungssprache" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-jpg/" name="PPTM TO JPG" description="JPEG-Bild" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-odp/" name="PPTM TO ODP" description="OpenDocument-Präsentationsformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-otp/" name="PPTM TO OTP" description="OpenDocument-Standardformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Portables Dokumentenformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-png/" name="PPTM TO PNG" description="Portable Netzwerkgrafiken" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-pot/" name="PPTM TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-pps/" name="PPTM TO PPS" description="PowerPoint-Diashow" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Makrofähige Diashow" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="PowerPoint-Diashow" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Offenes XML-Präsentationsformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-swf/" name="PPTM TO SWF" description="SWF-Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Markiertes Bildformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/pptm-to-xps/" name="PPTM TO XPS" description="XML-Papierspezifikationen" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}