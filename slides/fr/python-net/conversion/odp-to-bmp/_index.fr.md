---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir ODP en BMP en Python
weight: 230
url: /fr/python-net/conversion/odp-to-bmp/ 
keywords: "Convert, PowerPoint, ODP, BMP, Presentation, Python"
description: Exemple de code pour la conversion ODP vers BMP Python. Utilisez l'API PowerPoint Python pour la conversion par lots de fichiers ODP en fichiers BMP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir ODP en BMP en Python" h2="Puissante bibliothèque PowerPoint Python pour convertir ODP en BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir ODP en BMP en Python" %}}

Besoin de convertir des fichiers ODP en BMP par programmation ? En utilisant [*Aspose.Slides pour Python via .NET*](https://products.aspose.com/slides/fr/python-net/), tout développeur peut convertir ODP au format BMP avec seulement quelques lignes de code Python.

En tant qu'API de traitement de présentation moderne, Aspose.Slides pour Python crée rapidement du BMP à partir d'ODP. Testez la qualité de la conversion ODP en BMP directement dans votre [navigateur](https://products.aspose.app/slides/conversion). La bibliothèque Aspose PowerPoint PPTX vous permet de convertir des fichiers ODP dans de nombreux formats populaires.

Vous pouvez installer la bibliothèque à partir de [PyPI](https://pypi.org/project/Aspose.Slides/) à l'aide de la commande pip suivante :

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Enregistrer ODP en tant que BMP en Python" %}}

Utilisez l'application gratuite pour voir une démonstration du processus de conversion ODP en BMP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cet exemple de code montre la conversion Python ODP en BMP" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.odp") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.bmp".format(str(slide.slide_number)), drawing.imaging.ImageFormat.bmp)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment convertir ODP en BMP en Python" intro="Voici les étapes pour convertir un fichier ODP en BMP en utilisant Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Charger le fichier ODP avec une instance de la classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode `save` tout en spécifiant le chemin du fichier de sortie et SaveFormat.BMP comme paramètres{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Le fichier ODP sera enregistré dans le chemin spécifié{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Configuration requise" intro="Avant d'exécuter l'exemple de code source de conversion Python, assurez-vous que vous disposez des prérequis suivants." %}}

- Système d'exploitation basé sur Microsoft Windows ou Linux (voir [plus](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 ou version ultérieure
- Aspose.Slides pour Python référencé dans votre projet.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="odp-to-bmp"
  title="Application gratuite pour convertir ODP en BMP"
  description="[Essayez notre application gratuite pour convertir PPT en BMP](https://products.aspose.app/slides/conversion/ppt-to-bmp)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir ODP en de nombreux autres formats de fichiers. Voir les autres conversions prises en charge ci-dessous" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-emf/" name="ODP TO EMF" description="Format de métafichier amélioré" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-fodp/" name="ODP TO FODP" description="Présentation XML plate d'OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-gif/" name="ODP TO GIF" description="Format d'échange graphique" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-html/" name="ODP TO HTML" description="Langage Signalétique Hyper Text" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-jpg/" name="ODP TO JPG" description="Images JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-otp/" name="ODP TO OTP" description="Format standard OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-pdf/" name="ODP TO PDF" description="Portable Document Format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-png/" name="ODP TO PNG" description="Portable Network Graphics" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-pot/" name="ODP TO POT" description="Fichiers de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-potm/" name="ODP TO POTM" description="Fichier de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-potx/" name="ODP TO POTX" description="Modèle de présentation Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-pps/" name="ODP TO PPS" description="Diaporama PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Diaporama compatible avec les macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="Diaporama PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Fichier de présentation prenant en charge les macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Format de présentation XML ouvert" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-svg/" name="ODP TO SVG" description="Image Vectorielle" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-swf/" name="ODP TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Format d'image balisé" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/odp-to-xps/" name="ODP TO XPS" description="Spécifications papier XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
