---
title: Fusionner des images PNG en Java
url: /fr/java/merger/png-to-png/
keywords: Fusionner PNG, PNG vers PNG, Joindre PNG, Combiner PNG, API Java, Bibliothèque Java
description: Fusionnez PNG à PNG en Java. Utiliser l'API de la bibliothèque Java pour combiner des fichiers PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Fusionner PNG en Java" h2="Bibliothèque Java haute vitesse et multiplateforme pour fusionner des images PNG à l'aide de code Java" >}}

{{% blocks/products/pf/feature-page-section h2="Fusionner PNG à PNG en utilisant Aspose.Slides" %}}

[**Aspose.Slides pour Java**](https://products.aspose.com/slides/fr/java/) est une puissante bibliothèque Java utilisée pour fusionner et manipuler des présentations, des images et d'autres fichiers. Lorsque vous fusionnez PNG à PNG, vous combinez effectivement deux images pour obtenir une image.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Fusionner PNG à PNG en Java" %}}
En utilisant [**Aspose.Slides pour Java**](https://products.aspose.com/slides/fr/java/), vous pouvez fusionner rapidement des fichiers PNG avec seulement quelques lignes de code

{{% blocks/products/pf/agp/code-block title="Code Java pour fusionner PNG à PNG" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    IPPImage image1 = pres.getImages().addImage(Files.readAllBytes("image1.png"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image1);

    IPPImage image2 = pres.getImages().addImage(Files.readAllBytes("image2.png"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail();
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Comment fusionner PNG en Java" >}}


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
Chargez les fichiers PNG que vous souhaitez fusionner en tant que cadres d'image.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez l'image PNG résultante.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Fusionner d'autres fichiers" subTitle="Vous pouvez également combiner des fichiers dans d'autres formats pour obtenir un seul fichier" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/png-to-pdf/" name="PNG TO PDF" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}