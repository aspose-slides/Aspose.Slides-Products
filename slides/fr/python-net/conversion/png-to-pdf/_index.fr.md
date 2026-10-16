---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PNG en PDF en Python
url: /fr/python-net/conversion/png-to-pdf/
keywords: PNG en PDF, Convertir PNG en PDF, API Python, Bibliothèque Python, PNG, PDF
description: Convertissez PNG en PDF en Python. Utilisez l'API de la bibliothèque Python pour convertir les fichiers PNG en PDFs
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir PNG en PDF en Python" h2="Bibliothèque Python haute vitesse et multiplateforme qui aide au développement d'applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PNG en PDF en utilisant Python" variant="code" %}}

Pour convertir le PNG en PDF, vous devrez créer une présentation à partir du fichier PNG et l'enregistrer sous le nom PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code Python pour convertir PNG en PDF" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    pres.save("index.pdf", slides.export.SaveFormat.PDF)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PNG en PDF en Python" %}}

[**Aspose.Slides pour Python via .NET**](https://products.aspose.com/slides/fr/python-net/) est une puissante bibliothèque Python pour créer et manipuler des fichiers de présentation. De plus, il fournit des moyens flexibles pour convertir PNG en PDF. En utilisant **Aspose.Slides pour Python via .NET**, n'importe quel développeur ou application peut convertir des fichiers PNG en fichiers PDF avec seulement quelques lignes de code Python.

En tant qu'API de traitement de documents moderne, Aspose.Slides pour Python exporte rapidement les fichiers PNG vers les formats de fichier PDF. La bibliothèque Aspose PowerPoint vous permet de convertir PNG en PDFs et de nombreux autres formats de fichiers

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment convertir PNG en PDF en utilisant Aspose.Slides pour l'API Python" intro="Voici les étapes pour convertir PNG en PDF en Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/fr/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez les fichiers sources PNG en Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le résultat en tant que fichier PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Convertisseur en ligne gratuit"
  description="[Comment convertir PPT en HTML en Python](https://products.aspose.com/slides/fr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convertir PNG vers d'autres formats pris en charge" subTitle="Vous pouvez également convertir PNG et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-net/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
