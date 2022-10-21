---
title: Fusionner les fichiers POTX vers POTM à l'aide de Python
url: /fr/python-net/merge/potx-to-potm/
keywords: Fusionner POTX à POTM, Joindre POTX à POTM, Combiner POTX à POTM, PowerPoint, Présentation, POTM, Python, Aspose
description: Fusionnez plusieurs fichiers POTX en Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Fusionner les fichiers POTX vers POTM ensemble en Python" h2="API Python haute vitesse et multiplateforme qui aide au développement d'applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Fusionner POTX à POTM en Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fr/python-net/) est une puissante bibliothèque Python pour créer et manipuler des fichiers de présentation. De plus, il offre des moyens flexibles de combiner plusieurs présentations POTX. Lorsque vous fusionnez une présentation avec une autre, vous combinez efficacement leurs diapositives dans une seule présentation pour obtenir un fichier. Aspose.Slides vous permet de fusionner deux présentations de différentes manières. Vous pouvez fusionner des présentations avec toutes leurs formes, styles, textes, mises en forme, commentaires, animations, etc. sans avoir à vous soucier de la perte de qualité ou de données.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Fusionner les fichiers POTX vers POTM à l'aide de Python" %}}
Pour fusionner les présentations PowerPoint, vous devrez cloner les diapositives d'une présentation à l'autre.

{{% blocks/products/pf/agp/code-block title="Code Python pour fusionner plusieurs POTX en un seul fichier POTM" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.potx") as pres1:
    with slides.Presentation("presentation2.potx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.potm", slides.export.SaveFormat.POTM)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment fusionner POTX à POTM en utilisant Aspose.Slides pour l'API Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour fusionner deux fichiers POTX et enregistrer le résultat sous POTM en Python." >}}

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
Ouvrez les fichiers sources POTX en Python.
```
pres1 = slides.Presentation('pres1.potx')
pres2 = slides.Presentation('pres2.potx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combinez les fichiers POTX à l'aide de la méthode [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez la présentation et obtenez le résultat en tant que fichier unique POTM.
```
pres1.save("presentation.potm", slides.export.SaveFormat.POTM)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Exporter POTX vers d'autres formats pris en charge" subTitle="Vous pouvez également combiner POTX et enregistrer dans d'autres formats de fichier. Voir tous les formats pris en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-pptx/" name="POTX TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-ppt/" name="POTX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-pdf/" name="POTX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-html/" name="POTX TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-png/" name="POTX TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-bmp/" name="POTX TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-jpg/" name="POTX TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-fodp/" name="POTX TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-gif/" name="POTX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-odp/" name="POTX TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-otp/" name="POTX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-pot/" name="POTX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-pps/" name="POTX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-ppsm/" name="POTX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-ppsx/" name="POTX TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-pptm/" name="POTX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-svg/" name="POTX TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-tiff/" name="POTX TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/merge/potx-to-xps/" name="POTX TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}