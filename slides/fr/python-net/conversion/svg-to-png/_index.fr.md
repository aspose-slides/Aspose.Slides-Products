---
title: Convertir SVG en PNG en Python
url: /fr/python-net/conversion/svg-to-png/
keywords: SVG en PNG, Convertir SVG en PNG, API Python, Bibliothèque Python, SVG, PNG
description: Convertissez SVG en PNG en Python. Utilisez l'API de la bibliothèque Python pour convertir les fichiers SVG en PNGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir SVG en PNG en Python" h2="Bibliothèque Python haute vitesse et multiplateforme qui aide au développement d'applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir SVG en PNG en Python" %}}

[**Aspose.Slides pour Python via .NET**](https://products.aspose.com/slides/fr/python-net/) est une puissante bibliothèque Python pour créer et manipuler des fichiers de présentation. De plus, il fournit des moyens flexibles pour convertir SVG en PNG. En utilisant **Aspose.Slides pour Python via .NET**, n'importe quel développeur ou application peut convertir des fichiers SVG en fichiers PNG avec seulement quelques lignes de code Python.

En tant qu'API de traitement de documents moderne, Aspose.Slides pour Python exporte rapidement les fichiers SVG vers les formats de fichier PNG. La bibliothèque Aspose PowerPoint vous permet de convertir SVG en PNGs et de nombreux autres formats de fichiers

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir SVG en PNG en utilisant Python" %}}
Pour convertir le SVG en PNG, vous devrez créer une présentation à partir du fichier SVG et l'enregistrer sous le nom PNG.

{{% blocks/products/pf/agp/code-block title="Code Python pour convertir SVG en PNG" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open("image.svg", "rb") as file:
        svgContent = file.read()
    svgImage = slides.SvgImage(svgContent)
    ppImage = pres.images.add_image(svgImage)
    pres.slides[0].shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, ppImage.width, ppImage.height, ppImage)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment convertir SVG en PNG en utilisant Aspose.Slides pour l'API Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour convertir SVG en PNG en Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fr/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ouvrez les fichiers sources SVG en Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le résultat en tant que fichier PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir SVG vers d'autres formats pris en charge" subTitle="Vous pouvez également convertir SVG et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}