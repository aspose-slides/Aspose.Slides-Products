---
title: Modifier un PDF en Python
url: /fr/python-net/editor/pdf/
keywords: Modifier PDF, PDF, API Python, Bibliothèque Python
description: Modifier le PDF en Python. Utiliser l'API de la bibliothèque Python pour modifier un document PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Modifier un PDF en Python" h2="Bibliothèque Python haute vitesse et multiplateforme pour l'édition de PDF à l'aide de code Python" >}}

{{% blocks/products/pf/feature-page-section h2="Modifier un PDF à l'aide d'Aspose.Slides" %}}

[**Aspose.Slides pour Python via .NET**](https://products.aspose.com/slides/fr/python-net/) est une puissante bibliothèque Python utilisée pour manipuler et modifier des présentations, des documents PDF et d'autres fichiers . Vous pouvez modifier un document PDF en y ajoutant une nouvelle ligne de texte. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Modifier un PDF en Python" %}}
En utilisant [**Aspose.Slides pour Python via .NET**](https://products.aspose.com/slides/fr/python-net/), vous pouvez ajouter une nouvelle ligne de texte à un document PDF avec seulement quelques lignes de code.

{{% blocks/products/pf/agp/code-block title="Code Python pour l'édition de PDF" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    pres.slides.add_from_pdf("document.pdf")

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("document.pdf", slides.export.SaveFormat.PDF)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Comment éditer un PDF en Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez la bibliothèque comme référence dans votre projet.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Créez une instance de la classe Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chargez le document PDF que vous souhaitez modifier.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une nouvelle ligne de texte.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le fichier PDF modifié.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Modifier d'autres fichiers" subTitle="Vous pouvez également modifier des fichiers dans d'autres formats" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}