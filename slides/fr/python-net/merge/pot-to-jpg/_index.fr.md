---
title: Fusionner les fichiers POT vers JPG à l'aide de Python
url: /fr/python-net/merge/pot-to-jpg/
keywords: Fusionner POT à JPG, Joindre POT à JPG, Combiner POT à JPG, PowerPoint, Présentation, JPG, Python, Aspose
description: Fusionnez plusieurs fichiers POT en Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Fusionner les fichiers POT vers JPG ensemble en Python" h2="API Python haute vitesse et multiplateforme qui aide au développement d'applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Fusionner POT à JPG en Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fr/python-net/) est une puissante bibliothèque Python pour créer et manipuler des fichiers de présentation. De plus, il offre des moyens flexibles de combiner plusieurs présentations POT. Lorsque vous fusionnez une présentation avec une autre, vous combinez efficacement leurs diapositives dans une seule présentation pour obtenir un fichier. Aspose.Slides vous permet de fusionner deux présentations de différentes manières. Vous pouvez fusionner des présentations avec toutes leurs formes, styles, textes, mises en forme, commentaires, animations, etc. sans avoir à vous soucier de la perte de qualité ou de données.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Fusionner les fichiers POT vers JPG à l'aide de Python" %}}
Pour fusionner les présentations PowerPoint, vous devrez cloner les diapositives d'une présentation à l'autre.

{{% blocks/products/pf/agp/code-block title="Code Python pour fusionner plusieurs POT en un seul fichier JPG" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation1.pot") as pres1:
    with slides.Presentation("presentation2.pot") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment fusionner POT à JPG en utilisant Aspose.Slides pour l'API Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour fusionner deux fichiers POT et enregistrer le résultat sous JPG en Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fr/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet Python.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ouvrez les fichiers sources POT en Python.
```
pres1 = slides.Presentation('pres1.pot')
pres2 = slides.Presentation('pres2.pot')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combinez les fichiers POT à l'aide de la méthode [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez la présentation et obtenez le résultat en tant que fichier unique JPG.
```
for slide in pres1.slides:
    slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Exporter POT vers d'autres formats pris en charge" subTitle="Vous pouvez également combiner POT et enregistrer dans d'autres formats de fichier. Voir tous les formats pris en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-pptx/" name="POT TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-ppt/" name="POT TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-pdf/" name="POT TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-html/" name="POT TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-png/" name="POT TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-bmp/" name="POT TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-fodp/" name="POT TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-gif/" name="POT TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-odp/" name="POT TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-otp/" name="POT TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-potm/" name="POT TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-potx/" name="POT TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-pps/" name="POT TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-ppsm/" name="POT TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-ppsx/" name="POT TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-pptm/" name="POT TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-svg/" name="POT TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-tiff/" name="POT TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pot-to-xps/" name="POT TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}