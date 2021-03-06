---
title: Convertir PPTM en JPG en Python
weight: 2480
url: /fr/python-net/conversion/pptm-to-jpg/ 
keywords: "Convert, PowerPoint, PPTM, JPG, Presentation, Python"
description: Exemple de code pour la conversion PPTM en JPG Python. Utilisez l'API PowerPoint Python pour la conversion par lots de fichiers PPTM en fichiers JPG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir PPTM en JPG en Python" h2="Puissante bibliothèque PowerPoint Python pour convertir PPTM en JPG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Convertir PPTM en JPG en Python" %}}

Besoin de convertir des fichiers PPTM en JPG par programmation ? En utilisant [*Aspose.Slides pour Python via .NET*](https://products.aspose.com/slides/fr/python-net/), tout développeur peut convertir PPTM au format JPG avec seulement quelques lignes de code Python.

En tant qu'API de traitement de présentation moderne, Aspose.Slides pour Python crée rapidement des fichiers JPG à partir de PPTM. Testez la qualité de la conversion PPTM en JPG directement dans votre [navigateur](https://products.aspose.app/slides/conversion/ppt-to-jpg). La bibliothèque Aspose PowerPoint PPTX vous permet de convertir des fichiers PPTM dans de nombreux formats populaires.

Vous pouvez installer la bibliothèque à partir de [PyPI](https://pypi.org/project/Aspose.Slides/) à l'aide de la commande pip suivante :

{{% blocks/products/pf/agp/code-block title="Console/Terminal" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Comment convertir PPTM en JPG en Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour convertir un fichier PPTM en JPG en utilisant Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Charger le fichier PPTM avec une instance de la classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Appelez la méthode `save` tout en spécifiant le chemin du fichier de sortie et SaveFormat.JPG comme paramètres
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Le fichier PPTM sera enregistré dans le chemin spécifié
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

{{% blocks/products/pf/agp/code-block title="Cet exemple de code montre la conversion PPTM en JPG Python" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pptm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Enregistrer PPTM au format JPG en Python" %}}
Utilisez l'application gratuite pour voir une démonstration du processus de conversion PPTM en JPG. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Application gratuite pour convertir PPTM en JPG" 
        sectionDescription="[Essayez notre application gratuite pour convertir PPT en JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir PPTM en de nombreux autres formats de fichiers. Voir les autres conversions prises en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Image bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-emf/" name="PPTM TO EMF" description="Format de métafichier amélioré" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-fodp/" name="PPTM TO FODP" description="Présentation XML plate d'OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Format d'échange graphique" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-html/" name="PPTM TO HTML" description="Langage Signalétique Hyper Text" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Format de présentation OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-otp/" name="PPTM TO OTP" description="Format standard OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Portable Document Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-png/" name="PPTM TO PNG" description="Portable Network Graphics" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-pot/" name="PPTM TO POT" description="Fichiers de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Fichier de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Modèle de présentation Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Diaporama PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Diaporama compatible avec les macros" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Diaporama PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Format de présentation XML ouvert" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Image Vectorielle" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-swf/" name="PPTM TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Format d'image balisé" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Spécifications papier XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}