---
title: Modifier PPT en Java
url: /fr/java/editor/ppt/
keywords: Modifier PPT, Modifier PowerPoint, PPT, PowerPoint, API Java, Bibliothèque Java
description: Modifier PPT en Java. Utiliser l'API de la bibliothèque Java pour modifier la présentation PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Modifier PPT en Java" h2="Bibliothèque Java haute vitesse et multiplateforme pour l'édition de PPT à l'aide de code Java" >}}

{{% blocks/products/pf/feature-page-section h2="Modifier le PPT à l'aide d'Aspose.Slides" %}}

[**Aspose.Slides pour Java**](https://products.aspose.com/slides/fr/java/) est une puissante bibliothèque Java utilisée pour manipuler et modifier des présentations. Vous pouvez modifier une présentation PPT en y ajoutant une nouvelle ligne de texte. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Modifier PPT en Java" %}}
En utilisant [**Aspose.Slides pour Java**](https://products.aspose.com/slides/fr/java/), vous pouvez ajouter une nouvelle ligne de texte à un document PPT avec seulement quelques lignes de code.

{{% blocks/products/pf/agp/code-block title="Code Java pour l'édition de PPT" offSpacer="true" %}}
```java

Presentation pres = new Presentation("pres.ppt");
try {
    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Comment éditer PPT en Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installez **Aspose.Slides pour Java**. Voir [**Installation**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez la bibliothèque comme référence dans votre projet.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Créez une instance de la classe Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chargez la présentation PPT que vous souhaitez modifier.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une nouvelle ligne de texte.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le fichier PowerPoint modifié.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Modifier d'autres fichiers" subTitle="Vous pouvez également modifier des fichiers dans d'autres formats" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}