---
title: Convertir PPSM en JPG en Python
weight: 1820
url: /fr/python-net/conversion/ppsm-to-jpg/ 
keywords: "Convert, PowerPoint, PPSM, JPG, Presentation, Python"
description: Exemple de code pour la conversion PPSM en JPG Python. Utilisez l'API PowerPoint Python pour la conversion par lots de fichiers PPSM en fichiers JPG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir PPSM en JPG en Python" h2="Puissante bibliothèque PowerPoint Python pour convertir PPSM en JPG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Convertir PPSM en JPG en Python" %}}

Besoin de convertir des fichiers PPSM en JPG par programmation ? En utilisant [*Aspose.Slides pour Python via .NET*](https://products.aspose.com/slides/fr/python-net/), n'importe quel développeur peut convertir PPSM au format JPG avec seulement quelques lignes de code Python.

En tant qu'API de traitement de présentation moderne, Aspose.Slides pour Python crée rapidement des fichiers JPG à partir de PPSM. Testez la qualité de la conversion PPSM en JPG directement dans votre [navigateur](https://products.aspose.app/slides/conversion/ppt-to-jpg). La bibliothèque Aspose PowerPoint PPTX vous permet de convertir des fichiers PPSM dans de nombreux formats populaires.

Vous pouvez installer la bibliothèque à partir de [PyPI](https://pypi.org/project/Aspose.Slides/) à l'aide de la commande pip suivante :

{{% blocks/products/pf/agp/code-block title="Console/Terminal" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Comment convertir PPSM en JPG en Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour convertir un fichier PPSM en JPG en utilisant Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Charger le fichier PPSM avec une instance de la classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Appelez la méthode `save` tout en spécifiant le chemin du fichier de sortie et SaveFormat.JPG comme paramètres
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Le fichier PPSM sera enregistré dans le chemin spécifié
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Avant d'exécuter l'exemple de code source de conversion Python, assurez-vous que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Système d'exploitation basé sur Microsoft Windows ou Linux (voir [plus](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 ou version ultérieure
- Aspose.Slides pour Python référencé dans votre projet.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cet exemple de code montre la conversion PPSM en JPG Python" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppsm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Enregistrer PPSM au format JPG en Python" %}}
Utilisez l'application gratuite pour voir une démonstration du processus de conversion PPSM en JPG. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Application gratuite pour convertir PPSM en JPG" 
        sectionDescription="[Essayez notre application gratuite pour convertir PPT en JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir PPSM en de nombreux autres formats de fichiers. Voir les autres conversions prises en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Image bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="Format de métafichier amélioré" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-fodp/" name="PPSM TO FODP" description="Présentation XML plate d'OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Format d'échange graphique" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Langage Signalétique Hyper Text" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="Format de présentation OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="Format standard OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Portable Document Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-png/" name="PPSM TO PNG" description="Portable Network Graphics" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Fichiers de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Fichier de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Modèle de présentation Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="Diaporama PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="Diaporama PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Fichier de présentation prenant en charge les macros" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Format de présentation XML ouvert" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Image Vectorielle" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Format d'image balisé" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="Spécifications papier XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}