---
title: Fusionner l'image au format PDF en Java
url: /fr/java/merger/image-to-pdf/
keywords: Image au format PDF, fusionner l'image au format PDF, joindre l'image au format PDF, PDF, image, API Java, bibliothèque Java
description: Fusionner l'image au format PDF en Java. Utilisez l'API de la bibliothèque Java pour combiner Image et PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Fusionner l'image au format PDF en Java" h2="Bibliothèque Java haute vitesse et multiplateforme pour fusionner des fichiers Image vers PDF à l'aide de code Java" >}}

{{% blocks/products/pf/feature-page-section h2="Fusionner l'image au format PDF à l'aide d'Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/fr/java/) est une puissante bibliothèque Java utilisée pour créer, convertir, fusionner et manipuler des présentations, des PDF, des images et d'autres des dossiers. Lorsque vous fusionnez une image au format PDF, vous combinez efficacement des images pour obtenir un seul fichier PDF.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Fusionner l'image au format PDF en Java" %}}
En utilisant [**Aspose.Slides pour Java**](https://products.aspose.com/slides/fr/java/), vous pouvez rapidement fusionner une image au format PDF avec seulement quelques lignes de code

{{% blocks/products/pf/agp/code-block title="Code Java pour fusionner Image en PDF" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    IPPImage image1 = pres.getImages().addImage(Files.readAllBytes("image1.png"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image1);

    IPPImage image2 = pres.getImages().addImage(Files.readAllBytes("image2.png"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    pres.save("pres.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Comment fusionner une image en PDF en Java" >}}


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
Chargez les images que vous souhaitez fusionner en tant que cadres photo.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le PDF obtenu.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Fusionner des fichiers PDF en ligne" sectionDescription="[Comment fusionner un PDF en Python](https://products.aspose.com/slides/fr/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Fusionner d'autres fichiers" subTitle="Vous pouvez également combiner des fichiers dans d'autres formats pour obtenir un seul fichier" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/jpg-to-jpg/" name="JPG to JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}