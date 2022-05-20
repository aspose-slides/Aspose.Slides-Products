---
title: Converteer POT naar SVG in Python
weight: 1070
url: /nl/python-net/conversion/pot-to-svg/ 
keywords: "Convert, PowerPoint, POT, SVG, Presentation, Python"
description: Voorbeeldcode voor POT naar SVG Python-conversie. Gebruik PowerPoint Python API voor batchconversie van POT-bestanden naar SVG-bestanden.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converteer POT naar SVG in Python" h2="Krachtige PowerPoint Python-bibliotheek voor het converteren van POT naar SVG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Converteer POT naar SVG in Python" %}}

Wilt u POT-bestanden programmatisch naar SVG converteren? Met behulp van [*Aspose.Slides voor Python via .NET*](https://products.aspose.com/slides/nl/python-net/) kan elke ontwikkelaar POT converteren naar SVG-indeling met slechts een paar regels Python-code.

Als een moderne API voor het verwerken van presentaties, maakt Aspose.Slides voor Python snel SVG van POT. Test de kwaliteit van POT naar SVG-conversie rechtstreeks in uw [browser](https://products.aspose.app/slides/conversion). Met de Aspose PowerPoint PPTX-bibliotheek kunt u POT-bestanden converteren naar veel populaire formaten.

U kunt de bibliotheek installeren vanaf [PyPI](https://pypi.org/project/Aspose.Slides/) met behulp van de volgende pip-opdracht:

{{% blocks/products/pf/agp/code-block title="Console/Terminal" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Hoe POT naar SVG te converteren in Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om een ​​POT-bestand naar SVG te converteren met Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad POT-bestand met een instantie van de klasse Presentatie
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Roep de `save`-methode aan terwijl u het pad van het uitvoerbestand en SaveFormat.SVG als parameters specificeert
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
POT-bestand wordt opgeslagen op het opgegeven pad
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Voordat u de broncode van het Python-conversievoorbeeld uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Op Microsoft Windows of Linux gebaseerd besturingssysteem (zie [meer](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 of hoger
- Aspose.Slides voor Python waarnaar in uw project wordt verwezen.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Deze voorbeeldcode toont POT naar SVG Python-conversie" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pot") as presentation:
    for slide in presentation.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="POT opslaan als SVG in Python" %}}
Gebruik de gratis app om een ​​demonstratie te zien van het POT naar SVG-conversieproces. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="pot-to-svg"
        sectionTitle="Gratis app om POT te converteren naar SVG" 
        sectionDescription="[Probeer onze gratis MP4 To MP3 app](https://products.aspose.app/slides/video/mp4-to-mp3/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="U kunt POT ook naar vele andere bestandsindelingen converteren. Bekijk hieronder andere ondersteunde conversies" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-bmp/" name="POT TO BMP" description="Bitmap afbeelding" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-emf/" name="POT TO EMF" description="Verbeterde metabestandsindeling" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-fodp/" name="POT TO FODP" description="OpenDocument Flat XML-presentatie" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-gif/" name="POT TO GIF" description="Grafisch uitwisselingsformaat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-html/" name="POT TO HTML" description="Hypertekst-opmaaktaal" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-jpg/" name="POT TO JPG" description="JPEG-afbeelding" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-odp/" name="POT TO ODP" description="OpenDocument-presentatie-indeling" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-otp/" name="POT TO OTP" description="Standaardformaat OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-pdf/" name="POT TO PDF" description="Draagbaar documentformaat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-png/" name="POT TO PNG" description="Draagbare netwerkgrafieken" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-potm/" name="POT TO POTM" description="Microsoft PowerPoint-sjabloonbestand" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-potx/" name="POT TO POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-pps/" name="POT TO PPS" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Diavoorstelling met macro's" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-ppsx/" name="POT TO PPSX" description="PowerPoint-diavoorstelling" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-pptm/" name="POT TO PPTM" description="Presentatiebestand met macro's" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-pptx/" name="POT TO PPTX" description="Open XML-presentatie-indeling" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-swf/" name="POT TO SWF" description="SWF-formaat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-tiff/" name="POT TO TIFF" description="Gelabelde afbeeldingsindeling" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/python-net/conversion/pot-to-xps/" name="POT TO XPS" description="XML-papierspecificaties" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}