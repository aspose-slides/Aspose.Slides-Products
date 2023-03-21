---
title: Convertir JPG en Image en Python
url: /fr/python-net/conversion/jpg-to-image/
keywords: JPG en Image, Convertir JPG en Image, API Python, Bibliothèque Python, JPG, Image
description: Convertissez JPG en Image en Python. Utilisez l'API de la bibliothèque Python pour convertir les fichiers JPG en Images
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir JPG en Image en Python" h2="Bibliothèque Python haute vitesse et multiplateforme qui aide au développement d'applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir JPG en Image en Python" %}}

[**Aspose.Slides pour Python via .NET**](https://products.aspose.com/slides/fr/python-net/) est une puissante bibliothèque Python pour créer et manipuler des fichiers de présentation. De plus, il fournit des moyens flexibles pour convertir JPG en Image. En utilisant **Aspose.Slides pour Python via .NET**, n'importe quel développeur ou application peut convertir des fichiers JPG en fichiers Image avec seulement quelques lignes de code Python.

En tant qu'API de traitement de documents moderne, Aspose.Slides pour Python exporte rapidement les fichiers JPG vers les formats de fichier Image. La bibliothèque Aspose PowerPoint vous permet de convertir JPG en Images et de nombreux autres formats de fichiers

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir JPG en Image en utilisant Python" %}}
Pour convertir le JPG en Image, vous devrez créer une présentation à partir du fichier JPG et l'enregistrer sous le nom Image.

{{% blocks/products/pf/agp/code-block title="Code Python pour convertir JPG en Image" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment convertir JPG en Image en utilisant Aspose.Slides pour l'API Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour convertir JPG en Image en Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fr/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ouvrez les fichiers sources JPG en Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le résultat en tant que fichier Image.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertisseur en ligne gratuit" sectionDescription="[Comment convertir PPT en HTML en Python](https://products.aspose.com/slides/fr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir JPG vers d'autres formats pris en charge" subTitle="Vous pouvez également convertir JPG et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}