---
title: Fusionner des fichiers PPTM à l'aide de Python
url: /fr/python-net/merge/pptm/
keywords: Fusionner PPTM, Joindre PPTM, Combiner PPTM, PowerPoint, Présentation, Python, Aspose
description: Fusionnez plusieurs fichiers PPTM en Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Fusionner les fichiers PPTM ensemble en Python" h2="API Python haute vitesse et multiplateforme qui aide au développement d'applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Fusionner PPTM en Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fr/python-net/) est une puissante bibliothèque Python pour créer et manipuler des fichiers de présentation. De plus, il offre des moyens flexibles de combiner plusieurs présentations PPTM. Lorsque vous fusionnez une présentation avec une autre, vous combinez efficacement leurs diapositives dans une seule présentation pour obtenir un fichier. Aspose.Slides vous permet de fusionner deux présentations de différentes manières. Vous pouvez fusionner des présentations avec toutes leurs formes, styles, textes, mises en forme, commentaires, animations, etc. sans avoir à vous soucier de la perte de qualité ou de données.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Fusionner les fichiers PPTM à l'aide de Python" %}}
Pour fusionner les présentations PowerPoint, vous devrez cloner les diapositives d'une présentation à l'autre.

{{% blocks/products/pf/agp/code-block title="Code Python pour fusionner plusieurs PPTM en un seul fichier" offSpacer="true" %}}


```python

import aspose.slides as slides


with slides.Presentation("presentation1.pptm") as pres1:
    with slides.Presentation("presentation2.pptm") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.pptm", slides.export.SaveFormat.PPTM)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment fusionner PPTM à l'aide d'Aspose.Slides pour l'API Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour fusionner deux fichiers PPTM et enregistrer le résultat sous PPTM en Python." >}}

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
Ouvrez les fichiers sources PPTM en Python.
```
pres1 = slides.Presentation('pres1.pptm')
pres2 = slides.Presentation('pres2.pptm')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combinez les fichiers PPTM à l'aide de la méthode [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez la présentation et obtenez le résultat en tant que fichier unique PPTM.
```
pres1.save("result.pptm", slides.export.SaveFormat.PPTM)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Exporter PPTM vers d'autres formats pris en charge" subTitle="Vous pouvez également combiner PPTM et enregistrer dans d'autres formats de fichier. Voir tous les formats pris en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-pptx/" name="PPTM TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-ppt/" name="PPTM TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-pdf/" name="PPTM TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-html/" name="PPTM TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-png/" name="PPTM TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-bmp/" name="PPTM TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-jpg/" name="PPTM TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-fodp/" name="PPTM TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-gif/" name="PPTM TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-odp/" name="PPTM TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-otp/" name="PPTM TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-pot/" name="PPTM TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-potm/" name="PPTM TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-potx/" name="PPTM TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-pps/" name="PPTM TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-ppsm/" name="PPTM TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-ppsx/" name="PPTM TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-svg/" name="PPTM TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-tiff/" name="PPTM TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/pptm-to-xps/" name="PPTM TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}