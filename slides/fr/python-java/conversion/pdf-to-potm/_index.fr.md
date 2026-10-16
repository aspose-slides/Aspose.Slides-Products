---
lastmod: 2024-04-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PDF en POTM en Python
url: /fr/python-java/conversion/pdf-to-potm/
keywords: Conversion de présentation Python, conversion de présentations en Python, Python pour les présentations, Aspose.Slides Python, conversion PDF en POTM, bibliothèque de présentations Python
description: Convertissez PDF en POTM en Python. Utilisez l'API de la bibliothèque Python pour convertir les fichiers PDF en POTM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertissez sans effort PDF en POTM avec Python : Aspose.Slides à la rescousse !" h2="Donnez une nouvelle vie à vos présentations avec Python. Notre guide vous guide dans la conversion de diapositives PowerPoint existantes en présentations Python attrayantes." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PDF en POTM à l'aide de Python" variant="code" %}}

Pour convertir le PDF en POTM, vous devrez créer une présentation à partir du fichier PDF et l'enregistrer sous POTM.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tutoriel Python pour convertir PDF en POTM" >}}
```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation();

pres.getSlides().removeAt(0);
pres.getSlides().addFromPdf("welcome-to-powerpoint.{format_from}");

pres.save("output.potm", SaveFormat.Potm);

jpype.shutdownJVM()

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PDF en POTM en Python" %}}

Fatigué de lutter avec des logiciels de présentation complexes ? Ne cherchez pas plus loin que [**Aspose.Slides pour Python via Java**](https://products.aspose.com/slides/fr/python-java/) ! Cette puissante bibliothèque vous permet de créer, modifier et convertir facilement des présentations entre différents formats. Besoin de passer de PDF à POTM ? Aspose.Slides facilite la tâche, ne nécessitant que quelques lignes de code Python.

En tant qu'API de traitement de documents de pointe, **Aspose.Slides pour Python via Java** offre des vitesses de conversion ultra-rapides, garantissant une transformation rapide de vos présentations PDF au format POTM. Abandonnez les limitations des outils traditionnels - Aspose.Slides vous offre la flexibilité de convertir des présentations de PDF non seulement vers POTM mais également dans un large éventail d'autres formats, vous permettant d'adapter parfaitement vos présentations à n'importe quelle situation.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Tutoriel Python. Comment convertir PDF en POTM à l'aide d'Aspose.Slides pour Python via l'API Java." intro="Pour convertir PDF en POTM à l'aide d'Aspose.Slides pour Python via Java, vous devez importer le package dans votre script Python et créer une instance de la classe Présentation. La classe Présentation représente un document PowerPoint et fournit des méthodes pour accéder et manipuler ses éléments." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez [**Aspose.Slides pour Python via Java**](https://products.aspose.com/slides/fr/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez les fichiers sources PDF en Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le résultat dans un fichier POTM.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convertir PDF en d'autres formats pris en charge" subTitle="Vous pouvez également convertir PDF et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/python-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
