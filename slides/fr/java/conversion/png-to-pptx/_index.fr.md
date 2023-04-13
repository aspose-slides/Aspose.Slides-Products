---
title: Convertir PNG en PPTX en Java
url: /fr/java/conversion/png-to-pptx/
keywords: Convertir PNG en PPTX, PNG en PPTX, PowerPoint, PNG, PPTX, Java API, Java Library
description: Convertir PNG en PPTX en Java. Utiliser l'API de la bibliothèque Java pour convertir des images PNG en PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir PNG en PPTX en Java" h2="API Java multiplateforme puissante pour convertir PNG en PPTX à l'aide de code Java" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir PNG en PPTX en utilisant Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/fr/java/) est une puissante bibliothèque Java utilisée pour créer, convertir et manipuler des présentations PowerPoint, des PDF, des documents HTML et d'autres des dossiers. Lorsque vous convertissez PNG en PPTX, vous créez essentiellement une présentation PowerPoint contenant des diapositives basées sur des images PNG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Convertir PNG en PPTX en Java" %}}
En utilisant [**Aspose.Slides pour Java**](https://products.aspose.com/slides/fr/java/), vous pouvez convertir une image PNG en présentation PowerPoint avec seulement quelques lignes de code :

{{% blocks/products/pf/agp/code-block title="Code Java pour convertir PNG en PPTX" offSpacer="true" %}}
```java
Presentation pres = new Presentation();
try {
	ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

	pres.save("pres.pptx", SaveFormat.Pptx);
} finally {
	if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Comment convertir PNG en PPTX en Java" >}}


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
Chargez l'image PNG que vous souhaitez convertir en PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le fichier résultant en tant que présentation PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertisseur en ligne gratuit" sectionDescription="[Comment convertir PPT en HTML en Python](https://products.aspose.com/slides/fr/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres conversions PowerPoint prises en charge" subTitle="Vous pouvez également convertir des fichiers dans d'autres formats en PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}